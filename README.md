# gittip-badge

GitHub styled badge for [Gittip][]

![Gittip badge][]

[Gittip]: https://www.gittip.com/
[Gittip badge]: dist/gittip.png

## Usage
To ensure you are using a stable badge, it is suggested you use a semver'd badge.

### Markdown

```md
[![Support via Gittip](https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png)](https://www.gittip.com/USERNAME/)
```

### HTML

```html
<a href="https://www.gittip.com/USERNAME/">
  <img alt="Support via Gittip" src="https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png"/>
</a>
```

### Raw URL

```
https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png
```

## Documentation
The latest image is located under `dist/gittip.png`. If you would like to build your own, run `./build.sh`.

You must have [PhantomJS][] and [pngcrush][] installed for the build script to work. We require [pngcrush][] since the output from [PhantomJS][] is approximately 12x larger.

If you would like to adjust the image, you can find the HTML reference page in `lib/index.html`. It is suggested that you use [serve][] and [livereload][] to host and develop against the image.

[PhantomJS]: http://phantomjs.org/
[pngcrush]: http://pmt.sourceforge.net/pngcrush/
[serve]: https://npmjs.org/package/serve
[livereload]: https://github.com/lepture/python-livereload

## Donating
Support this project and [others by twolfson][gittip-twolfson] via [gittip][gittip-twolfson].

[![Support via Gittip][gittip-badge]][gittip-twolfson]

[gittip-badge]: https://rawgithub.com/twolfson/gittip-badge/master/dist/gittip.png
[gittip-twolfson]: https://www.gittip.com/twolfson/

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## License
As of Feb 19 2014, Todd Wolfson has released this repository and its contents to the public domain.

It has been released under the [UNLICENSE][].

[UNLICENSE]: UNLICENSE

Previous to this, it was licensed under the [MIT license][].

[MIT license]: https://github.com/twolfson/gittip-badge/blob/ee5cc0ad6573ef6e80048c7229bc1b7c01942b4c/README.md#license