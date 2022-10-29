# Awesome List Updates on Jan 27, 2015

3 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c)



## [1. Awesome Artificial Intelligence](/content/owainlewis/awesome-artificial-intelligence/README.md)

### Courses

*   [Intro to Artificial Intelligence](https://www.udacity.com/course/cs271) - Learn the Fundamentals of AI. Course run by Peter Norvig
*   [EdX Artificial Intelligence](https://www.edx.org/course/artificial-intelligence-uc-berkeleyx-cs188-1x-0#.VMeIsmSsVkg) - The course will introduce the basic ideas and techniques underlying the design of intelligent computer systems
*   [The Emotion Machine: Commonsense Thinking, Artificial Intelligence, and the Future of the Human Mind ](http://www.amazon.com/gp/product/0743276647) - In this mind-expanding book, scientific pioneer Marvin Minsky continues his groundbreaking research, offering a fascinating new model for how our minds work
*   [Artificial Intelligence: A New Synthesis](http://www.amazon.com/Artificial-Intelligence-Synthesis-Nils-Nilsson/dp/1558604677) - Beginning with elementary reactive agents, Nilsson gradually increases their cognitive horsepower to illustrate the most important and lasting ideas in AI

## [2. Htaccess](/content/phanan/htaccess/README.md)

### Rewrite and Redirection

What we are doing here is mostly collecting useful snippets from all over the interwebs (for example, a good chunk is from [Apache Server Configs (⭐3k)](https://github.com/h5bp/server-configs-apache)) into one place. While we’ve been trying to credit where due, things might be missing. If you believe anything here is your work and credits should be given, let us know, or just send a PR.

Note: It is assumed that you have `mod_rewrite` installed and enabled.

### Rewrite and Redirection / Force www

### Force www

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^example\.com [NC]
RewriteRule ^(.*)$ http://www.example.com/$1 [L,R=301,NC]
```

### Rewrite and Redirection / Force www in a Generic Way

### Force www in a Generic Way

```apacheconf
RewriteCond %{HTTP_HOST} !^$
RewriteCond %{HTTP_HOST} !^www\. [NC]
RewriteCond %{HTTPS}s ^on(s)|
RewriteRule ^ http%1://www.%{HTTP_HOST}%{REQUEST_URI} [R=301,L]
```

This works for *any* domain. [Source](https://stackoverflow.com/questions/4916222/htaccess-how-to-force-www-in-a-generic-way)

### Rewrite and Redirection / Force non-www

### Force non-www

It’s [still](http://www.sitepoint.com/domain-www-or-no-www/) [open](https://devcenter.heroku.com/articles/apex-domains) [for](http://yes-www.org/) [debate](http://no-www.org/) whether www or non-www is the way to go, so if you happen to be a fan of bare domains, here you go:

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^www\.example\.com [NC]
RewriteRule ^(.*)$ http://example.com/$1 [L,R=301]
```

### Rewrite and Redirection / Force HTTPS

### Force HTTPS

```apacheconf
RewriteEngine on
RewriteCond %{HTTPS} !on
RewriteRule (.*) https://%{HTTP_HOST}%{REQUEST_URI}

# Note: It’s also recommended to enable HTTP Strict Transport Security (HSTS)
# on your HTTPS website to help prevent man-in-the-middle attacks.
# See https://developer.mozilla.org/en-US/docs/Web/Security/HTTP_strict_transport_security
<IfModule mod_headers.c>
    # Remove "includeSubDomains" if you don't want to enforce HSTS on all subdomains
    Header always set Strict-Transport-Security "max-age=31536000;includeSubDomains"
</IfModule>
```

### Rewrite and Redirection / Force Trailing Slash

### Force Trailing Slash

```apacheconf
RewriteCond %{REQUEST_URI} /+[^\.]+$
RewriteRule ^(.+[^/])$ %{REQUEST_URI}/ [R=301,L]
```

### Security / Deny All Access

### Deny All Access

```apacheconf
## Apache 2.2
Deny from all

## Apache 2.4
# Require all denied
```

But wait, this will lock you out from your content as well! Thus introducing...

### Security / Deny All Access Except Yours

### Deny All Access Except Yours

```apacheconf
## Apache 2.2
Order deny,allow
Deny from all
Allow from xxx.xxx.xxx.xxx

## Apache 2.4
# Require all denied
# Require ip xxx.xxx.xxx.xxx
```

`xxx.xxx.xxx.xxx` is your IP. If you replace the last three digits with `0/12` for example, this will specify a range of IPs within the same network, thus saving you the trouble to list all allowed IPs separately. [Source](http://speckyboy.com/2013/01/08/useful-htaccess-snippets-and-hacks/)

Now of course there's a reversed version:

### Security / Allow All Access Except Spammers'

### Allow All Access Except Spammers'

```apacheconf
## Apache 2.2
Order deny,allow
Deny from xxx.xxx.xxx.xxx
Deny from xxx.xxx.xxx.xxy

## Apache 2.4
# Require all granted
# Require not ip xxx.xxx.xxx.xxx
# Require not ip xxx.xxx.xxx.xxy
```

### Security / Disable Directory Browsing

### Disable Directory Browsing

```apacheconf
Options All -Indexes
```

### Security / Disable Image Hotlinking

### Disable Image Hotlinking

```apacheconf
RewriteEngine on
# Remove the following line if you want to block blank referrer too
RewriteCond %{HTTP_REFERER} !^$

RewriteCond %{HTTP_REFERER} !^https?://(.+\.)?example.com [NC]
RewriteRule \.(jpe?g|png|gif|bmp)$ - [NC,F,L]

# If you want to display a “blocked” banner in place of the hotlinked image,
# replace the above rule with:
# RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Security / Disable Image Hotlinking for Specific Domains

### Disable Image Hotlinking for Specific Domains

Sometimes you want to disable image hotlinking from some bad guys only.

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite\.com [NC,OR]
RewriteCond %{HTTP_REFERER} ^https?://(.+\.)?badsite2\.com [NC,OR]
RewriteRule \.(jpe?g|png|gif|bmp)$ - [NC,F,L]

# If you want to display a “blocked” banner in place of the hotlinked image,
# replace the above rule with:
# RewriteRule \.(jpe?g|png|gif|bmp) http://example.com/blocked.png [R,L]
```

### Security / Password Protect a Directory

### Password Protect a Directory

First you need to create a `.htpasswd` file somewhere in the system:

```bash
htpasswd -c /home/fellowship/.htpasswd boromir
```

Then you can use it for authentication:

```apacheconf
AuthType Basic
AuthName "One does not simply"
AuthUserFile /home/fellowship/.htpasswd
Require valid-user
```

### Security / Password Protect a File or Several Files

### Password Protect a File or Several Files

```apacheconf
AuthName "One still does not simply"
AuthType Basic
AuthUserFile /home/fellowship/.htpasswd

<Files "one-ring.o">
Require valid-user
</Files>

<FilesMatch ^((one|two|three)-rings?\.o)$>
Require valid-user
</FilesMatch>
```

### Miscellaneous / Turn eTags Off

### Turn eTags Off

By removing the `ETag` header, you disable caches and browsers from being able to validate files, so they are forced to rely on your `Cache-Control` and `Expires` header. [Source](http://www.askapache.com/htaccess/apache-speed-etags.html)

```apacheconf
<IfModule mod_headers.c>
    Header unset ETag
</IfModule>
FileETag None
```

### Miscellaneous / Set PHP Variables

### Set PHP Variables

```apacheconf
php_value <key> <val>

# For example:
php_value upload_max_filesize 50M
php_value max_execution_time 240
```

### Miscellaneous / Custom Error Pages

### Custom Error Pages

```apacheconf
ErrorDocument 500 "Houston, we have a problem."
ErrorDocument 401 http://error.example.com/mordor.html
ErrorDocument 404 /errors/halflife3.html
```

## [3. Awesome Perl](/content/hachiojipm/awesome-perl/README.md)

### List Manipulation / NoSQL Databases

*   [Array::Unique](https://metacpan.org/pod/Array::Unique) - Tie-able array that allows only unique values
*   [List::Compare](https://metacpan.org/pod/List::Compare) - Compare elements of two or more lists
*   [List::Gen](https://metacpan.org/pod/List::Gen) - Provides functions for generating lists
*   [List::Util](https://metacpan.org/pod/List::Util) - A selection of general-utility list subroutines

---

- Prev: [Jan 28, 2015](/content/2015/01/28/README.md)
- Next: [Jan 26, 2015](/content/2015/01/26/README.md)