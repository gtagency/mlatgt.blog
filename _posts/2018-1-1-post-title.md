---
title:  "Post Title"
date:   2018-1-1 00:00:00
description: Some information to appear in the front page
<!-- THE FOLLOWING ARE OPTIONAL LINES: -->
<!-- thumbnail (width=100px, min-height=60px can be more): -->
thumbnail: 2018/PostTitle_thumbnail.png
authors:
- Author 1: Institution 1
- Author 2: Instutition 2
- Author with no institution:
paper: arxiv.org
web: https://google.com
code: github.com
---

This is a header
================
This is a paragraph. This is a paragraph. This is a paragraph. This is a
paragraph. This is a paragraph. This is a paragraph. This is a paragraph. This
is a paragraph. This is a paragraph. This is a paragraph. This is a paragraph.

# This is a header as well
This is another paragraph. This is another paragraph. This is another
paragraph. This is another paragraph. This is another paragraph. This is
another paragraph. This is another paragraph. This is another paragraph.

An empty line between text creates a new paragraph.
The lack of an empty line stays in the same paragraph.

## This is a sub header
**This is bold**. _This is italics_.
Alright you're getting the hang of this.

This is also a sub header
-------------------------
You can go even further:

### This is a sub sub header
### This is another one, right after
That's a lot of substructure.

> This is a quote

# Adding media
## Code snippets
The below is a code snippet:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

4 spaces indentation also create a code snippet:

    some code

## Links
This is a [link](google.com). You can also define [links][google] after the
fact, especially if you're reusing them.

[google]: https://google.com

## Images
This is how you add an image:

<center>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/1200px-Cat03.jpg" alt="this is the alt text, you should describe the image here for acessibility" height="200px" width="200px"/>
</center>

You can use images hosted anywhere on the internet, or place images in the
`assets/images/201X/...` directory of this repo (where 201X is the current
year) and do:

<center>
  <img src="{{ "/" | relative_url  }}assets/images/2018/cat.jpg" alt="this is the alt text, you should describe the image here for acessibility" width="200px"/>
</center>
<figcaption>This is how you'd add a caption</figcaption>

## LaTeX
For in-line TeX: \\(f(x)\\). For displayed mathematics:

$$\alpha = f (a b) \implies \frac{a}{b} = 0$$

## References
You can add references [[^referencetag]] and footnotes [^anothertag], [^onelasttag].

[^referencetag]: This is a reference. AUTHOR, First Name; Paper Title, arxiv/123.1234
[^anothertag]:
    This is a footnote

    That has multiple paragraphs.

[^onelasttag]:
    This footnote has
    > a quote

    $$some = \LaTeX$$

        and a code block (8 spaces indentation)

## Buttons
If you want to add centered buttons, you may do so like this:
<buttons>
  <a href="https://google.com" target="_blank">google</a>
  <a href="http://youtube.com">youtube</a>
</buttons>

The "http" or "https" is required. `target="_blank"` forces the button to open
a new tab.

## Video embeddings
Go on youtube, find the video you want to embed, click on "Share" > "Embed" and
copy the html onto here, surrounded by `<center>` tags. It should look like this:

<center>
  <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/dQw4w9WgXcQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>

## HTML
<p>You can add html directly on here too</p>
<p>This is especially useful if you want to create interactive visualizations</p>

If you're adding visualizations, please put any javascript required in
`assets/js/201X/...js` where 201X is the current year.

## Emojis :poop:
You can add :kissing_heart: emojis by checking their markups
[here](https://gist.github.com/rxaviers/7360908).

# Getting help
For more help with this syntax, check out the [markdown documentation][mddocs].

For help with the LaTeX syntax, check out the [mathjax documentation][mjxdocs].

[mddocs]: https://help.github.com/articles/basic-writing-and-formatting-syntax/ 
[mjxdocs]: https://docs.mathjax.org/en/latest/
