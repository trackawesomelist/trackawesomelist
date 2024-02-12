# Awesome List Updates on Feb 09, 2015

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Javascript](/content/sorrycc/awesome-javascript/README.md)

### Loaders

*   [ESL (⭐838)](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD.

## [2. Awesome Remote Job](/content/lukasz-madon/awesome-remote-job/README.md)

### Articles & Posts

*   [Rethinking Agile in an office-less world](https://signalvnoise.com/posts/3641-rethinking-agile-in-an-office-less-world)
*   [The Pros & Cons of Being a Remote Team (& How We Do It)](https://www.groovehq.com/blog/being-a-remote-team)
*   [Why Remote Workers Are More (Yes, More) Engaged](https://hbr.org/2012/08/are-you-taking-your-people-for)

## [3. Awesome Ruby](/content/markets/awesome-ruby/README.md)

### Natural Language Processing

*   [Pragmatic Segmenter (⭐530)](https://github.com/diasks2/pragmatic_segmenter) - Pragmatic Segmenter is a rule-based sentence boundary detection gem that works out-of-the-box across many languages.

## [4. Awesome Talks](/content/JanVanRyswyck/awesome-talks/README.md)

### Functional Programming

*   [Extreme Cleverness: Functional Data Structures in Scala](https://www.youtube.com/watch?v=pNhBQJN44YQ) by **Daniel Spiewak** \[39:24]

## [5. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Eventhandling

*   [reaxive (⭐277)](https://github.com/alfert/reaxive) - Reaxive is a reactive event handling library, inspired by [Elm](http://elm-lang.org) and Reactive Extensions.

### Examples and funny stuff

*   [dice (⭐15)](https://github.com/stocks29/dice) - Roll the dice, in Elixir.

### HTTP

*   [http (⭐12)](https://github.com/slogsdon/http) - HTTP server for Elixir.

## [6. Htaccess](/content/phanan/htaccess/README.md)

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

## [7. Awesome Courses](/content/prakhar1989/awesome-courses/README.md)

### Courses / Machine Learning

*   [CS 231n](http://cs231n.stanford.edu/) **Convolutional Neural Networks for Visual Recognition** *Stanford University* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4f9.png" width="20" height="20" alt="Lecture Videos" title="Lecture Videos" />
    *   Computer Vision has become ubiquitous in our society, with applications in search, image understanding, apps, mapping, medicine, drones, and self-driving cars. This course is a deep dive into details of the deep learning architectures with a focus on learning end-to-end models for these tasks, particularly image classification. During the 10-week course, students will learn to implement, train and debug their own neural networks and gain a detailed understanding of cutting-edge research in computer vision.
    *   [Lecture Notes](http://cs231n.stanford.edu/syllabus.html)
    *   [Lecture Videos](https://www.youtube.com/watch?v=NfnWJUyUJYU\&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
    *   [Github Page](http://cs231n.github.io/)

---

- Prev: [Feb 10, 2015](/content/2015/02/10/README.md)
- Next: [Feb 08, 2015](/content/2015/02/08/README.md)