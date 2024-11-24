---
layout: page
title: Make a pull request
permalink: /git
search_exclude: false
page_id: git
sidebar: about
---

This contribution guide is adapted from the [RDMKit knowledge contribution guide](https://rdmkit.elixir-europe.org/how_to_contribute "How to contribute to RDMkit ") by [ELIXIR Europe](https://elixir-europe.org/ "ELIXIR Europe main page")  [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This guide tells you how to request and edit a page using Git and GitHub.

Prerequisites:
* Basic knowledge of Markdown. All you need to know is in the [markdown cheat sheet](https://kramdown.gettalong.org/quickref.html)
* Technical knowledge about Git.
* A GitHub account. If you do not have one, [create a free GitHub account](https://github.com/join) before you start.


## Forking - branching - changing - pushing - PR

This is a general workflow in how to work on your own fork (copy) of the plan.research-data.no repo and request changes through a pull request:
NOTE: if you already did these steps in the past, start from the `git fetch upstream` command.

- Make a fork of this repository, using the fork button.
- Open a terminal and clone your fork using:
    ```
    git clone git@github.com:USERNAME/pages.git
    cd rdmkit
    ```
    NOTE: Make sure you clone the fork and not the original DHP-stottepakke/pages one.
- Keep your fork up to date (IMPORTANT!).
    ```
    git remote add upstream https://github.com/DHP-stottepakke/pages
    git fetch upstream
    git checkout master (if you are not already on the master branch, check with `git branch`)
    git pull upstream master
    ```
- Create a new branch named after your feature/edit.
    ```
    git checkout -b 'FEATURE_NAME'
    ```
- Make the changes you want to make using an editor of choice
- Save.
- Open terminal and stage your changes:
    ```
    git add .
    ```
- Committing changes
    ```
    git commit -m "Changing the tool-resource file"
    ```
- Pushing you changes to your fork
    ```
    git push origin 'FEATURE_NAME'
    ```
- Go to [https://github.com/DHP-stottepakke/pages](https://github.com/DHP-stottepakke/pages) and click on *Compare & pull request*
- Open the pull request an describe your changes.
- Wait for review by other editors. Editors that are responsible for the sections you make changes to will be assigned as reviewer automatically.

## The advantage of working locally: previewing your changes through your web browser

The website is build on GitHub using Jekyll, a simple, static site generator based on ruby. When you have a local copy cloned onto your computer, it is possible to generate the website based on this repo. This makes it possible to preview changes live, every time you save a file from within the GitHub plan.research-data.no repo. Follow these steps to deploy the website based on your local clone (copy) of the plan.research-data.no repo:

Make sure you have cloned the plan.research-data.no repo:

    git clone git@github.com:USERNAME/pages.git
    cd pages


To run the website locally, you can either use docker or use Jekyll directly after installing various dependencies.

### Run using Docker

1. If not already installed on your machine, install Docker. From the root of the ``plan.research-data.no`` directory, run:
    ```
    docker run -it --rm -p 4000:4000 -v $PWD:/srv/jekyll jekyll/jekyll:4 /bin/bash -c "chmod -R 777 /srv/jekyll && bundle install && bundle exec jekyll serve -w - --host 0.0.0.0 --livereload"
    ```
This will start the docker container and serve the website locally.

### Run using Jekyll directly

1. If not already present on your machine, install ruby. Note that incompatibility issues may arise with ruby 3.0.0 (released 25.12.20) or newer versions.


1. Install Jekyll
If you have never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:
   * Install Jekyll on MacOS/Ubuntu/Other_Linux/Windows: [https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/)

1. Install Jekyll and Bundler

    ```
    gem install jekyll
    gem install bundler
    ```
2. Install dependencies using Bundler

    ```
    bundle install
    ```

2. Serve website locally

    ```
    bundle exec jekyll serve
    ```

Additional information can be found at the following link: [https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

