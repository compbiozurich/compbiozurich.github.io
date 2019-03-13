---
title:  "Howto: Local Jekyll site creation"
permalink: /howto/jekyllinstructions/
layout: default
date:   2018-04-08
category:
  - howto
---

## Local Jekyll based website generation, starting from the Github "minimal" theme

In an ideal scenario, your Github served website could be build locally, with the same output structure and layout.

However, you need to install a local version of the theme first & get this to be compiled by [Jekyll](https://jekyllrb.com). And there may be differences - e.g. custom css links may not be added to the Github site, but recognised in your custom build etc. Still working on this... The [Github page](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#keeping-your-site-up-to-date-with-the-github-pages-gem) has some more information (but see OS X comment below).

The `sudo` in the following commands may not be rtequired, depending on your setup.

```bash
sudo gem install jekyll bundler rouge
sudo gem install github-pages
```

On OS X with homebrew there is (was? encountered 2018-04-06, OS X 10.13.4) a configuration problem when building the "nokogiri" component. A workaround is to de-install "xz", and run the install again (thanks to the comments by _halostatue_ on [Github nokogiri](https://github.com/sparklemotion/nokogiri/issues/1483)!).

```bash
brew uninstall --ignore-dependencies --force xz
sudo gem install github-pages
brew install xz
```

Change to your site's source directory, and then:

```bash
bundle install
```
... to install the specific components.

From this site directory, you issue:

```bash
jekyll build
```
... to generate the html file structure, or 
```bash
jekyll serve --incremental
```
... to run a server. Which should then answer with (more stuff) and

```bash
Server address: http://127.0.0.1:4000
```

Please see the [Jekyll](https://jekyllrb.com) documentation for more options (e.g. how to generate your site into a specific target directory).
