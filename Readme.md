Sample Markdown Slide
=========================
### Overview

[reveal.js](https://github.com/hakimel/reveal.js/) lets you to create
beautiful interactive slides using HTML. This presentation will show/demo you
how to use reveal.js and write your presentations in style with [Jekyll](http://jekyllrb.com/)

### Features

    - Easy to install
    - Stupidly easy to use
    - Supports all Github-supported .gitignore files
    - Works on Mac, Linux and Windows
    


### Sub-modules

`reveal.js` is already included as a `git submodule`, so that we can use it in our layouts.

`footer.html` `head.html` `header.html` are sub-modules listed in `_includes` folder.

`custom.css` and `main.css` are sub-modules inside css.

 `_sass` folder contains following sub-modules `_base.scss` `_layout.scss` `_syntax-highlighting.scss`

Also a `slide.html` `default.html` `page.html` `post.html`  layout has been added into the `_layouts` folder which would be the base layout for all our slides.

### Creating Slide

Now, in your page/post YAML front matter, use `slide` for the layout.

You can define *title*, *author*, *description* as well as the slide's *theme* and
*transition*

    --
    layout: slide
    title: Jekyll&#58; Make presentation page with reveal.js
    description: A presentation slide for how to use reveal.js in Jekyll
    theme: black
    transition: slide
    --

### Slide

Each slide is enclosed in a `&lt;section&gt;` tag.

If you prefer markdown then use

`&lt;section data-markdown&gt;`

### Instruction to add new slides to `http://redpanthers.github.io/slides/`


- Clone the slide using  git clone git@github.com:redpanthers/slides.git – recursive
- Create a 'new branch' with your name
- Open it in the sublime editor and edit the content listed inside posts (2016-01-12-create-slides-with-   revealjs-and-jekyll.html).
- Create new post in the newly created branch
- Push this branch to remote (git push origin 'newbranch')
- Create a pull request to master branch with a message to review the slides (tag sibinx7,pooja-r,manusajith)
- On successfull merging of this branch with master, pull master branch.
- From master branch give command `octopress deploy`  

### Contact info

Website : www.redpanthers.co

Company name : Red Panthers Software Solutions (P) Ltd

Address : Vijaya complex, Chembumukku, Kakkanad, Kochi 682030

### Thanks

redpanthers©2016