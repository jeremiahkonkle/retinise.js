# retinise.js

Retinise.js is a really simple jQuery plugin which 'retinises' your inline images, and because it uses 'data-src' instead of 'src' it means it only ever serves up the image you need, saving you and your users bandwidth. It's really small and really easy, just follow the steps below.


## Head
```html
<script src=”/path/to/jquery.js”></script>
<script src=”/path/to/retinise.js”></script>
```

## HTML
```html
<img data-src=”/img/path/non-retina.jpg” data-alt="My Image" class=”retina” />
<noscript>
  <img src=”/img/path/non-retina.jpg” alt="My Image” />
</noscript>
```

## JS
```js
$(’.retina’).retinise();
```

## Options
```js
suffix: “@2x”
srcattr: "data-src"
altattr: "data-alt"
```

## License

Copyright (c) 2012+ Simon Sturgess

## Support

[Website](http://www.dahliacreative.com/retinisejs/)
[Twitter](http://www.twitter.com/dahliacreative)
