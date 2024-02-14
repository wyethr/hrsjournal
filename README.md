# hrsjournal

## To Ask Dr. Kessner

1. How do we fix the .ccs file not showing up in the web version?
2. How can I make the book show up in .html? (Because I need to be able to resize)


## Use Sphinx for images

```{image} ./images/book1.png
:width: 50%
:align: center
```

## Potential Font

Montserrat

## Brand Guide

dark purple: #3B1072
link purple: #5D00C6
light purple: #E7D2FF

## To Test Journal Locally

jb clean journal
jb build journal

## To Publish Journal Online

### in hrsjournal directory:

ghp-import -n -p -f journal/_build/html