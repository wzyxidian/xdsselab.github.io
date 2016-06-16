# sselab.org

sselab.org - a static website build with angular

# Getting Started

```sh
$ cd sselab.org
# install npm packages
$ npm install
# compile
$ grunt build:dist -v > grunt.log
# test
$ node web-server.js
```

# How To Write Blog

1. add blog info to `src/app/blog/blog.controller.js`
1. create blog markdown file in `src/data/blog/[blog_title].md`

Example:

1.`src/app/blog/blog.controller.js`
```
{"title": "blog template demo", "author": "x-web", "date": "2016-04-15", "digest": "This is a simple blog demo by angular-sap.", "tags": ["angular"]}
```
2.`src/data/blog/2016-04-15-blog-template-demo.md`
```md
# This is a blog demo

Powered by markdown(marked).
```
3.browser `http://path/to/blog/2016-04-15-blog-template-demo`

# Issue Tracker

* [issues](https://github.com/xdsselab/sselab.org/issues)

# TODO LIST

- add disqus comment module
- add test
 

# LICENSE

MIT
