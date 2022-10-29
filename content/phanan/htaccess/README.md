# Track Htaccess Updates Daily

✂A collection of useful .htaccess snippets.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/phanan/htaccess/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 phanan/htaccess](https://github.com/phanan/htaccess) · ⭐ 12K · 🏷️ Back-End Development

[ Daily / [Weekly](/content/phanan/htaccess/week/README.md) / [Overview](/content/phanan/htaccess/readme/README.md) ]

## [Oct 28, 2018](/content/2018/10/28/README.md)

### Security / Exclude URL from Redirection

### Exclude URL from Redirection

This snippet allows you to exclude a URL from redirection.  For example, if you have redirection rules setup but want to exclude robots.txt so search engines can access that URL as expected.

```apacheconf
RewriteEngine On
RewriteRule ^robots.txt - [L]
```

## [Aug 21, 2015](/content/2015/08/21/README.md)

### Rewrite and Redirection / Redirect an Entire Site

### Redirect an Entire Site

```apacheconf
Redirect 301 / http://newsite.com/
```

This way does it with links intact. That is `www.oldsite.com/some/crazy/link.html` will become `www.newsite.com/some/crazy/link.html`. This is extremely helpful when you are just “moving” a site to a new domain. [Source](http://css-tricks.com/snippets/htaccess/301-redirects/)

### Rewrite and Redirection / Redirect Using RedirectMatch

### Redirect Using RedirectMatch

```apacheconf
RedirectMatch 301 /subdirectory(.*) http://www.newsite.com/newfolder/$1
RedirectMatch 301 ^/(.*).htm$ /$1.html
RedirectMatch 301 ^/200([0-9])/([^01])(.*)$ /$2$3
RedirectMatch 301 ^/category/(.*)$ /$1
RedirectMatch 301 ^/(.*)/htaccesselite-ultimate-htaccess-article.html(.*) /htaccess/htaccess.html
RedirectMatch 301 ^/(.*).html/1/(.*) /$1.html$2
RedirectMatch 301 ^/manual/(.*)$ http://www.php.net/manual/$1
RedirectMatch 301 ^/dreamweaver/(.*)$ /tools/$1
RedirectMatch 301 ^/z/(.*)$ http://static.askapache.com/$1
```

[Source](http://www.askapache.com/htaccess/301-redirect-with-mod_rewrite-or-redirectmatch.html#301_Redirects_RedirectMatch)

### Rewrite and Redirection / Alias Paths to Script

### Alias Paths to Script

```apacheconf
FallbackResource /index.fcgi
```

This example has an `index.fcgi` file in some directory, and any requests within that directory that fail to resolve a filename/directory will be sent to the `index.fcgi` script. It’s good if you want `baz.foo/some/cool/path` to be handled by `baz.foo/index.fcgi` (which also supports requests to `baz.foo`) while maintaining `baz.foo/css/style.css` and the like. Get access to the original path from the PATH\_INFO environment variable, as exposed to your scripting environment.

```apacheconf
RewriteEngine On
RewriteRule ^$ index.fcgi/ [QSA,L]
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ index.fcgi/$1 [QSA,L]
```

This is a less efficient version of the FallbackResource directive (because using `mod_rewrite` is more complex than just handling the `FallbackResource` directive), but it’s also more flexible.

## [Apr 09, 2015](/content/2015/04/09/README.md)

### Rewrite and Redirection / Remove Trailing Slash

### Remove Trailing Slash

This snippet will redirect paths ending in slashes to their non-slash-terminated counterparts (except for actual directories), e.g. `http://www.example.com/blog/` to `http://www.example.com/blog`. This is important for SEO, since it’s [recommended](http://overit.com/blog/canonical-urls) to have a canonical URL for every page.

```apacheconf
RewriteCond %{REQUEST_FILENAME} !-d
RewriteCond %{REQUEST_URI} (.+)/$
RewriteRule ^ %1 [R=301,L]
```

[Source](https://stackoverflow.com/questions/21417263/htaccess-add-remove-trailing-slash-from-url#27264788)

## [Feb 26, 2015](/content/2015/02/26/README.md)

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

## [Feb 23, 2015](/content/2015/02/23/README.md)

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

## [Feb 16, 2015](/content/2015/02/16/README.md)

### Miscellaneous / Disable Internet Explorer Compatibility View

### Disable Internet Explorer Compatibility View

Compatibility View in IE may affect how some websites are displayed. The following snippet should force IE to use the Edge Rendering Engine and disable the Compatibility View.

```apacheconf
<IfModule mod_headers.c>
    BrowserMatch MSIE is-msie
    Header set X-UA-Compatible IE=edge env=is-msie
</IfModule>
```

## [Feb 12, 2015](/content/2015/02/12/README.md)

### Rewrite and Redirection / Force non-www in a Generic Way

### Force non-www in a Generic Way

```apacheconf
RewriteEngine on
RewriteCond %{HTTP_HOST} ^www\.
RewriteCond %{HTTPS}s ^on(s)|off
RewriteCond http%1://%{HTTP_HOST} ^(https?://)(www\.)?(.+)$
RewriteRule ^ %1%3%{REQUEST_URI} [R=301,L]
```

## [Feb 11, 2015](/content/2015/02/11/README.md)

### Miscellaneous / Force Downloading

### Force Downloading

Sometimes you want to force the browser to download some content instead of displaying it.

```apacheconf
<Files *.md>
    ForceType application/octet-stream
    Header set Content-Disposition attachment
</Files>
```

Now there is a yang to this yin:

## [Feb 10, 2015](/content/2015/02/10/README.md)

### Miscellaneous / Auto UTF-8 Encode

### Auto UTF-8 Encode

Your text content should always be UTF-8 encoded, no?

```apacheconf
# Use UTF-8 encoding for anything served text/plain or text/html
AddDefaultCharset utf-8

# Force UTF-8 for a number of file formats
AddCharset utf-8 .atom .css .js .json .rss .vtt .xml
```

[Source (⭐3k)](https://github.com/h5bp/server-configs-apache)

### Miscellaneous / Prevent Downloading

### Prevent Downloading

Sometimes you want to force the browser to display some content instead of downloading it.

```apacheconf
<FilesMatch "\.(tex|log|aux)$">
    Header set Content-Type text/plain
</FilesMatch>
```

## [Feb 09, 2015](/content/2015/02/09/README.md)

### Rewrite and Redirection / Force HTTPS Behind a Proxy

### Force HTTPS Behind a Proxy

Useful if you have a proxy in front of your server performing TLS termination.

```apacheconf
RewriteCond %{HTTP:X-Forwarded-Proto} !https
RewriteRule (.*) https://%{HTTP_HOST}%{REQUEST_URI}
```

### Rewrite and Redirection / Alias a Single Directory

### Alias a Single Directory

```apacheconf
RewriteEngine On
RewriteRule ^source-directory/(.*) /target-directory/$1 [R=301,L]
```

### Rewrite and Redirection / Alias “Clean” URLs

### Alias “Clean” URLs

This snippet lets you use “clean” URLs -- those without a PHP extension, e.g. `example.com/users` instead of `example.com/users.php`.

```apacheconf
RewriteEngine On
RewriteCond %{SCRIPT_FILENAME} !-d
RewriteRule ^([^.]+)$ $1.php [NC,L]
```

[Source](http://www.abeautifulsite.net/access-pages-without-the-php-extension-using-htaccess/)

### Security / Deny Access to Hidden Files and Directories

### Deny Access to Hidden Files and Directories

Hidden files and directories (those whose names start with a dot `.`) should most, if not all, of the time be secured. For example: `.htaccess`, `.htpasswd`, `.git`, `.hg`...

```apacheconf
RewriteCond %{SCRIPT_FILENAME} -d [OR]
RewriteCond %{SCRIPT_FILENAME} -f
RewriteRule "(^|/)\." - [F]
```

Alternatively, you can just raise a “Not Found” error, giving the attacker no clue:

```apacheconf
RedirectMatch 404 /\..*$
```

### Miscellaneous / Switch to Another PHP Version

### Switch to Another PHP Version

If you’re on a shared host, chances are there are more than one version of PHP installed, and sometimes you want a specific version for your website. The following snippet should switch the PHP version for you.

```apacheconf
AddHandler application/x-httpd-php56 .php

# Alternatively, you can use AddType
AddType application/x-httpd-php56 .php
```

## [Jan 27, 2015](/content/2015/01/27/README.md)

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