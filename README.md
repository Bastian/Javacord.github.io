# Javacord Website
This is Javacord's github.io page, which hosts our website.

## I just want to use Javacord :\(
In this case you are wrong here. Just head over to the [Javacord repository](https://github.com/Javacord/Javacord).

# How to run the website locally
Make sure you have [RubyGems](https://rubygems.org/) installed.
```
gem install bundler jekyll
git clone https://github.com/Javacord/javacord.github.io
cd javacord.github.io
bundle exec jekyll serve
```

# How to edit wiki articles
Wiki articles are located in the `_wiki` folder.
They are using simple markdown, which should make it fairly easy to modify them.

# How to create wiki articles
A wiki article has the following structure:
```
---
title: "Article title"
headline: "Article headline"
---

The content of the article.
```
* `title`: The title of the article, which will be used for the `<title>` html tag and the side navigation
* `headline`: The headline of the article, displayed as `<h1>`. If not set, the title is used.

# How to create changelogs
Wiki articles are located in the `_changelog` folder. They have the following structure:
```
---
title: "Version x.y.z"
version: x.y.z
---

The content of the changelog.
```
* `title`: The title of the changelog, which will be used for the `<title>` html tag, usually `Version :version:`
* `version`: The version number