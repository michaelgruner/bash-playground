# Bash Playground

> An embeddable, fully-functional Bash component for websites.

This project is meant to provide an embeddable Bash component for your
website / presentation. It works by running an emmulator entirely on
the browser, running Alpine Linux and actual Bash. This means that
absolutely all bash features should be present and functional.

## Testing the Playground

The test the playground you can simply navigate to https://bash.mgruner.io

### Embedding in your Website

TODO

## Customizing

The following query params allow you to customize the presentation of
the bash terminal:

| Parameter | Description                      | Default |
|-----------|----------------------------------|---------|
| cols      | Number of colums of the terminal | 80      |
| rows      | Number of rows of the terminal   | 30      |
| font_size | Font size in pixels              | 15      |

If you're not familiar with query params, here's how you'd use them:
```
https://bash.mgruner.io?cols=50&rows=10&font-size=10
```
Each of them are optional and, if not included, the default value will be used.

## Acknowledgements

This project is a very thin layer on top of the awesome JSLinux from
Fabrice Bellard. Check out his project at https://bellard.org/jslinux/

