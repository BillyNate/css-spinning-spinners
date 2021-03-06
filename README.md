# CSS Spinning Spinners

This is a collection of loading spinners animated by CSS only.

Each spinner is applied to elements with a class of `loading` by utilizing the :before pseudo-element.

The aim of this project was to create a set of minimal loading spinners that are visually appealing and also convey their intended meaning.

A strict limit of no additional elements was placed on this project based on the belief that something as simple as a loader shouldn't need more.

Each loader is given a font size of 10px and all other sizes are in ems. To change the size of a loader, just adjust the font-size.

## Usage

Load the stylesheet of the spinner you want into the head of your page:
```html
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/css-spinning-spinners/1.1.0/load2.css" />
```

Apply the class `loading` to any element within the body of your page:
```html
<div class="loading"></div>
```

Or when doing an AJAX request in jQuery:
```javascript
$('el').addClass('loading').load('someurl.ext', function() {
	$(this).removeClass('loading');
});
```

&nbsp;

To change the size of the spinner set the font-size in your stylesheet:
```css
.loading:before { font-size: 20px; }
```

&nbsp;

## Demo

[![css-loaders-screenshot](http://billynate.github.io/css-spinning-spinners/images/css-loaders-screenshot.jpg)](http://billynate.github.io/css-spinning-spinners)

> [Check it live](http://billynate.github.io/css-spinning-spinners).

## Browser Support

![IE](https://raw.github.com/alrra/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Chrome 4.0+ ✔ | Firefox 16.0+ ✔ | Opera 15.0+ ✔ | Safari 4.0+ ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :)

## History

For detailed changelog, check [Releases](https://github.com/BillyNate/css-spinning-spinners/releases).

## License

[MIT License](LICENSE)