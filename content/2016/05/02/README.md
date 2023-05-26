# Awesome List Updates on May 02, 2016

8 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Jquery Tips Everyone Should Know](/content/AllThingsSmitty/jquery-tips-everyone-should-know/README.md)

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

## [2. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### ORM and Datamapping

*   [ddb\_client (⭐11)](https://github.com/dalmatinerdb/ddb_client) - DalmatinerDB client.

### Websites

*   [Elixir Quiz](http://elixirquiz.github.io/) - Weekly programming problems to help you learn Elixir.

## [3. Awesome Pyramid](/content/uralbash/awesome-pyramid/README.md)

### Services

*   [pyramid\_sms (⭐6)](https://github.com/websauna/pyramid_sms) -
    SMS services for Pyramid web framework.

## [4. Awesome Swift](/content/matteocrippa/awesome-swift/README.md)

### StackView / Barcode

*   [StackViewController (⭐866)](https://github.com/seedco/StackViewController) - Simplify the use of UIStackView.
*   [TZStackView (⭐1.2k)](https://github.com/tomvanzummeren/TZStackView) - An iOS9 UIStackView layout component re-implemented for iOS 7 and 8.

## [5. Awesome Remote Job](/content/lukasz-madon/awesome-remote-job/README.md)

### Job boards aggregators

*   [Work Remotely](https://workremotely.io/) - Crawls and curates many job board feeds for remote positions

## [6. Awesome Micro Npm Packages](/content/parro-it/awesome-micro-npm-packages/README.md)

### Modules / Stream

*   [through2-map-promise (⭐3)](https://github.com/RangerMauve/through2-map-promise) - A small promise-based wrapper for through2.

## [7. Awesome Knockout](/content/dnbard/awesome-knockout/README.md)

### Plugins and libraries

*   [Projections (⭐4)](https://github.com/profiscience/ko-projections) - Adds lodash FP chainability to observable arrays
*   [Router (⭐67)](https://github.com/profiscience/ko-component-router) - Router for single-page apps

## [8. Colorful](/content/Siddharth11/Colorful/README.md)

### Articles / Web App

*   [Principles of Color and the Color Wheel](http://tympanus.net/codrops/2012/02/28/principles-of-color-and-the-color-wheel/)
*   [Introduction to Color Theory](http://www.tigercolor.com/color-lab/color-theory/color-theory-intro.htm)

---

- Prev: [May 03, 2016](/content/2016/05/03/README.md)
- Next: [May 01, 2016](/content/2016/05/01/README.md)