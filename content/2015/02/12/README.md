# Awesome List Updates on Feb 12, 2015

2 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Scalable Css Reading List](/content/davidtheclark/scalable-css-reading-list/README.md)

### CSS Styleguides

*   [Trello](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80)

## [2. Htaccess](/content/phanan/htaccess/README.md)

### Rewrite and Redirection / Force non-www in a Generic Way

### Force non-www in a Generic Way

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^www\.
RewriteCond %{HTTPS}s ^on(s)|off
RewriteCond http%1://%{HTTP_HOST} ^(https?://)(www\.)?(.+)$
RewriteRule ^ %1%3%{REQUEST_URI} [R=301,L]
```

---

- Prev: [Feb 14, 2015](/content/2015/02/14/README.md)
- Next: [Feb 11, 2015](/content/2015/02/11/README.md)