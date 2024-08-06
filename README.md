# markdown-cv

A curriculum vitae maintained in plain text and rendered to HTML and PDF using CSS.

***

## Distribution

To transform your plain text CV into a beautiful and shareable HTML page, you have two options:

### I. Use Github Pages to publish it online

1. Delete the existing `gh-pages` branch from your fork. It will only contain this webpage. You can either use git or [the Github web interface](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/#deleting-a-branch).
2. Create a new branch called `gh-pages`.
3. Head to *yourusername*.github.io/markdown-cv to see your CV live.

Any change you want to make to your CV from then on would have to be done on the `gh-pages` branch and will be immediately rendered by Github Pages.

### II. Build it locally and print a PDF

1. To [install jekyll](https://jekyllrb.com/docs/installation/), run `gem install bundler jekyll` from the command line.
3. [Clone](https://help.github.com/en/articles/cloning-a-repository) your fork of markdown-cv to your local machine.
3. Type `jekyll serve` to render your CV at http://localhost:4000.
4. You can edit the `index.md` file and see the changes live in your browser.
5. To print a PDF, press <kbd>⌘</kbd> + <kbd>p</kbd>. Print and web CSS media queries should take care of the styling.

## Styling

The included CSS will render your CV in two styles:
s
1. `kjhealy` the original default, inspired by [kjhealy's vita
template](https://github.com/kjhealy/kjh-vita).
2. `davewhipp` is a tweaked version of `kjhealy`, with bigger fonts and dates
  right aligned.

To change the default style, simply change the variable in the
`_config.yml` file.

Any other styling is possible. More CSS style contributions and forks are welcome!

### License

[MIT License](https://github.com/elipapa/markdown-cv/blob/master/LICENSE)
