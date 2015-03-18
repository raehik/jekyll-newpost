jekyll-newpost
==============

*NOTE: This script is now deprecated by my [new-from-template][]
program.*

[new-from-template]: https://github.com/raehik/new-from-template

Creates a template Jekyll post with frontmatter based on given
arguments. For example:

    jekyll-newpost This is the title of the post

would create a file called `$(date +%F)-this-is-the-title-of-the-post.md`
and insert this into it:

```
---
title: This is the title of the post
date: $(date "+%F %T")
---


```

See the usage for more help.
