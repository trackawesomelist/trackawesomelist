# Awesome List Updates on Feb 26, 2015

3 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c)



## [1. Htaccess](/content/phanan/htaccess/README.md)

### Miscellaneous / Allow Cross-Domain Fonts

### Allow Cross-Domain Fonts

CDN-served webfonts might not work in Firefox or IE due to [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing). This snippet solves the problem.

```apacheconf
<IfModule mod_headers.c>
    <FilesMatch "\.(eot|otf|ttc|ttf|woff|woff2)$">
        Header set Access-Control-Allow-Origin "*"
    </FilesMatch>
</IfModule>
```

[Source (⭐3k)](https://github.com/h5bp/server-configs-apache/issues/32)

## [2. Awesome Lua](/content/LewisJEllis/awesome-lua/README.md)

### Resources / Implementations, Interpreters, and Bindings

*   [GopherLua (⭐5.1k)](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler implemented in Go with Go APIs.

## [3. Awesome Computer Vision](/content/jbhuang0604/awesome-computer-vision/README.md)

### Intrinsic Images / Edge-preserving image processing

*   [Recovering Intrinsic Images with a global Sparsity Prior on Reflectance](http://people.tuebingen.mpg.de/mkiefel/projects/intrinsic/)
*   [Intrinsic Images by Clustering](http://giga.cps.unizar.es/\~elenag/projects/EGSR2012_intrinsic/)

### Contour Detection and Image Segmentation / Edge-preserving image processing

*   [SEEDS](http://www.mvdblive.org/seeds/)

### Video Segmentation / Edge-preserving image processing

*   [Streaming hierarchical video segmentation](http://www.cse.buffalo.edu/\~jcorso/r/supervoxels/)

---

- Prev: [Feb 27, 2015](/content/2015/02/27/README.md)
- Next: [Feb 25, 2015](/content/2015/02/25/README.md)