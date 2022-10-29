# Awesome List Updates on Feb 23, 2015

6 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c)



## [1. Awesome Deep Learning](/content/ChristosChristofidis/awesome-deep-learning/README.md)

### Researchers / Miscellaneous

*   [Wiki2Vec. Getting Word2vec vectors for entities and word from Wikipedia Dumps (⭐598)](https://github.com/idio/wiki2vec)

## [2. Htaccess](/content/phanan/htaccess/README.md)

### Security / Block Visitors by Referrer

### Block Visitors by Referrer

This denies access for all users who are coming from (referred by) a specific domain.
[Source](http://www.htaccess-guide.com/deny-visitors-by-referrer/)

```apacheconf
RewriteEngine on
# Options +FollowSymlinks
RewriteCond %{HTTP_REFERER} somedomain\.com [NC,OR]
RewriteCond %{HTTP_REFERER} anotherdomain\.com
RewriteRule .* - [F]
```

### Performance / Prevent Framing the Site

### Prevent Framing the Site

This prevents the website to be framed (i.e. put into an `iframe` tag), when still allows framing for a specific URI.

```apacheconf
SetEnvIf Request_URI "/starry-night" allow_framing=true
Header set X-Frame-Options SAMEORIGIN env=!allow_framing
```

### Miscellaneous / Serve WebP Images

### Serve WebP Images

If [WebP images](https://developers.google.com/speed/webp/?csw=1) are supported and an image with a .webp extension and the same name is found at the same place as the jpg/png image that is going to be served, then the WebP image is served instead.

```apacheconf
RewriteEngine On
RewriteCond %{HTTP_ACCEPT} image/webp
RewriteCond %{DOCUMENT_ROOT}/$1.webp -f
RewriteRule (.+)\.(jpe?g|png)$ $1.webp [T=image/webp,E=accept:1]
```

[Source (⭐198)](https://github.com/vincentorback/WebP-images-with-htaccess)

## [3. Awesome IoT Hybrid](/content/weblancaster/awesome-IoT-hybrid/README.md)

### Hybrid Mobile / Resources-websites-projects

*   [Ionic](http://ionicframework.com/)

## [4. Awesome Dojo](/content/petk/awesome-dojo/README.md)

### Themes / Dojo 2

*   [Flat Dojo Theme](http://yiweima.github.io/flatdojo/) - Esri Flat Dijit Design

## [5. Awesome Erlang](/content/drobakowski/awesome-erlang/README.md)

### Text and Numbers

*   [jiffy (⭐827)](https://github.com/davisp/jiffy) - JSON NIFs for Erlang.

## [6. Awesome Computer Vision](/content/jbhuang0604/awesome-computer-vision/README.md)

### OpenCV Programming

*   [OpenCV Essentials](http://www.amazon.com/OpenCV-Essentials-Oscar-Deniz-Suarez/dp/1783984244/ref=sr_1_1?s=books\&ie=UTF8\&qid=1424594237\&sr=1-1\&keywords=opencv+essentials#) - Oscar Deniz Suarez, Mª del Milagro Fernandez Carrobles, Noelia Vallez Enano, Gloria Bueno Garcia, Ismael Serrano Gracia

---

- Prev: [Feb 24, 2015](/content/2015/02/24/README.md)
- Next: [Feb 22, 2015](/content/2015/02/22/README.md)