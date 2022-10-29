# Track Jquery Tips Everyone Should Know Updates Daily

A collection of tips to help up your jQuery game 🎮

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/AllThingsSmitty/jquery-tips-everyone-should-know/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 AllThingsSmitty/jquery-tips-everyone-should-know](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know) · ⭐ 4.2K · 🏷️ Front-End Development

[ Daily / [Weekly](/content/AllThingsSmitty/jquery-tips-everyone-should-know/week/README.md) / [Overview](/content/AllThingsSmitty/jquery-tips-everyone-should-know/readme/README.md) ]

## [Jun 22, 2017](/content/2017/06/22/README.md)

### Disable Right-Click

If you want to disable right-click, you can do it for an entire page...

```javascript
$(document).ready(function () {
  $(document).bind('contextmenu', function (e) {
    return false;
  })
})
```

...and you can also do the same for a specific element:

```javascript
$(document).ready(function () {
  $('#submit').bind('contextmenu', function (e) {
    return false;
  })
})
```

<sup>[back to table of contents](#table-of-contents)</sup>

Current versions of Chrome, Firefox, Safari, Opera, Edge, and IE11.

<sup>[back to table of contents](#table-of-contents)</sup>

*   [български (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/bg-BG)
*   [Español (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/es-ES)
*   [Français (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/fr-FR)
*   [Magyar (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/hu-HU)
*   [한국어 (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ko-KR)
*   [Português do Europe (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/pt-PT)
*   [Pусский (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/ru-RU)
*   [简体中文 (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-CN)
*   [繁體中文 (⭐4.2k)](https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know/tree/master/translations/zh-TW)

<sup>[back to table of contents](#table-of-contents)</sup>

## [May 02, 2016](/content/2016/05/02/README.md)

### Back to Top Button

By using the `animate` and `scrollTop` methods in jQuery you don't need a plugin to create a simple scroll-to-top animation:

```javascript
// Back to top
$('.container').on('click', '.back-to-top', function (e) {
  e.preventDefault();
  $('html, body').animate({scrollTop: 0}, 800);
});
```

```html
<!-- Create an anchor tag -->
<div class="container">
  <a href="#" class="back-to-top">Back to top</a>
</div>
```

Changing the `scrollTop` value changes where you wants the scrollbar to land. All you're really doing is animating the body of the document throughout the course of 800 milliseconds until it scrolls to the top of the document.

**Note:** Watch for some [buggy behavior (⭐320)](https://github.com/jquery/api.jquery.com/issues/417) with `scrollTop`.

<sup>[back to table of contents](#table-of-contents)</sup>
### Make Two Divs the Same Height

Sometimes you'll want two divs to have the same height no matter what content they have in them:

```javascript
$('.div').css('min-height', $('.main-div').height());
```

This example sets the `min-height` which means that it can be bigger than the main div but never smaller. However, a more flexible method would be to loop over a set of elements and set `height` to the height of the tallest element:

```javascript
var $columns = $('.column');
var height = 0;
$columns.each(function () {
  if ($(this).height() > height) {
    height = $(this).height();
  }
});
$columns.height(height);
```

If you want *all* columns to have the same height:

```javascript
var $rows = $('.same-height-columns');
$rows.each(function () {
  $(this).find('.column').height($(this).height());
});
```

**Note:** This can be done several ways [in CSS](http://codepen.io/AllThingsSmitty/pen/KMPqoO) but depending on what your needs are, knowing how to do this in jQuery is handy.

<sup>[back to table of contents](#table-of-contents)</sup>
### Open External Links in New Tab/Window

Open external links in a new browser tab or window and ensure links on the same origin open in the same tab or window:

```javascript
$('a[href^="http"]').attr('target', '_blank');
$('a[href^="//"]').attr('target', '_blank');
$('a[href^="' + window.location.origin + '"]').attr('target', '_self');
```

**Note:** `window.location.origin` doesn't work in IE10. [This fix](http://tosbourn.com/a-fix-for-window-location-origin-in-internet-explorer/) takes care of the issue.

<sup>[back to table of contents](#table-of-contents)</sup>
### Chain Plugin Calls

jQuery allows for the "chaining" of plugin method calls to mitigate the process of repeatedly querying the DOM and creating multiple jQuery objects. Let's say the following snippet represents your plugin method calls:

```javascript
$('#elem').show();
$('#elem').html('bla');
$('#elem').otherStuff();
```

This could be vastly improved by using chaining:

```javascript
$('#elem')
  .show()
  .html('bla')
  .otherStuff();
```

An alternative is to cache the element in a variable (prefixed with `$`):

```javascript
var $elem = $('#elem');
$elem.hide();
$elem.html('bla');
$elem.otherStuff();
```

Both chaining and [caching](#cache-jquery-selectors) methods in jQuery are best practices that lead to shorter and faster code.

<sup>[back to table of contents](#table-of-contents)</sup>