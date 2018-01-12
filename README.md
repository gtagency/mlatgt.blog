# ML@GT Blog

Welcome to the ML@GT blog repository. 


## Contributing

We have two ways in which you can contribute posts so we can publish your amazing work for the whole world to see. At the end of the day, all posts are simply Markdown and we **highly recommend** learning Markdown so you can make your posts as great as you want them to be.

>Pro-tip: Markdown is a superset of HTML so you can add HTML elements and visualizations directly.


### I like to do things manually

Perfect! The only thing we assume is basic familiarity with [git](https://git-scm.com). If you know how to fork, commit and push, you're good to go.

To get started, simply clone this repo, and copy the file `_drafts/template.md` to the `_posts`
directory with the name convention `YYYY-MM-DD-post-title.md`. This is the template you can update with your content.

You can add any images you have in your post to `assets/images/201*/` (where `201*` is the current year) being careful to avoid name clashes with previous files.

If you have any `javascript` you need to add (such as for D3 visualizations), you should add the JS files to `assets/js/201*` (following the same convention as for images).

In order to preview your post, you will need to install Jekyll. To install Jekyll follow our guide [here](#installing-jekyll). Preview your post by running `jekyll serve` from the root of the directory and
navigating to the IP it outputs.

You can publish your post by making a pull request to this repo. We'll get back to you in case your post needs any modification.


### I don't like Github

You can write your post in Word or Google Docs and send it over to our editors for conversion and publishing.


## Help

Here are some resources to help you get started with editing Markdown.

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code-and-syntax-highlighting)
- [Markdown Specs](https://github.github.com/gfm/)
- [Latex support](https://www.mathjax.org)

## Installing Jekyll

Jekyll is designed to be super easy to install and use. The only dependency is a Ruby interpreter, but you don't need to know any Ruby syntax to work with Jekyll.

To install Jekyll, please follow the instructions specific to your operating system [here](https://jekyllrb.com/docs/installation/).

You'll also want to add some of the extra features listed [here](https://jekyllrb.com/docs/extras/).