# Portfolio

My github user page(https://s-horiguchi.github.io) is generated by [Hugo](https://gohugo.io/), a static site generator written in Go.

This is the main repository for this site.

* `public` directory is linked to the [s-horiguchi.github.io repository](https://github.com/s-horiguchi/s-horiguchi.github.io)
  * which is the generated content and hosted on the site

* `thems/resume` is linked to the [hugo-resume repository](https://github.com/s-horiguchi/hugo-resume)
  * The theme of [hugo-resume](https://github.com/eddiewebb/hugo-resume) is used but I modified some parts
  * Note that I use `green` branch.


## How to update the site

Ref: https://gohugo.io/hosting-and-deployment/hosting-on-github/


1. Edit the source codes
2. Check it on the local server
```
$ hugo server -D -t resume
```
3. Clear & Build static pages
```
$ rm -rf public/*
$ hugo -t resume
```
4. Publish the generated pages
```
$ cd public
$ git add .
$ git commit -m "hoge"
$ git push -u origin master
```
5. Commit the changes in source code for this repository(portfolio) and hugo-resume repo.

That's all!
