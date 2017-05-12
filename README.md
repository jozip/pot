# Pile o' Text

A pint-sized data shoveler for the modern txt-wrangler.

## Synopsis

    pot add|add-page|build

Examples:

    pot add my_cool_article.txt

    pot add-page about.txt

    pot build

## Description

...in other words, it's a minimal viable product, blog-centric static-site generator written as a self-contained Bash script, designed to be dropped into a folder containing text-files waiting to be published.

Everything needed to build a site -- templates, styles, images, configs, etc -- are contained within the script.

## Options

* **add**
Add a given text file to the articles index (`.articles.csv`). The publication date is when the article was added.
* **add-page**
Add a given text file to the pages index (`.pages.csv`). A page is an article without the publication date.
* **build**
Build articles, pages and index, and put them in the specified output folder.

## Installation

	cd <your text directory of choice>
	cp <path to where you cloned the repo>/pot .

## Author

Johan Persson <jzp@bahnhof.se>