# bash-static-stie-generator
A rudimentary static site generator written in bash.

## Features

* Chicken Theme
* Converts blog posts to markdown
* Homepage and other files handwritten for enhanced control
* Dead Simple

## Example file layout
```
├── articles # These are the articles
│   ├── over-easy
│   │   └── index.md
│   ├── scrambled
│   │   └── index.md
│   └── sunny-side-up
│       └── index.md
├── files # This is where all the staic files are located
│   ├── egg.jpg
│   └── style.css
├── output # This is where all the files are exported to
├── templates.sh # This has templates for the Homepage the article pages and index pages
└── gen.sh # This is the configuration file and where everything is run
```
# How to use
First install [lowdown](https://kristaps.bsd.lv/lowdown/) It should be available from your package manager.

Next make gen.sh and templates.sh executable.
To generate your site run ./gen

## To Do
* Convert project into a makefile
* Add support for the gemini protocol
