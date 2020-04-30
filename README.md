# Heater

A warm and friendly CSS framework, written in and compiled from Sass.

## Aesthetics and Design Philosophy:

1. Warm, friendly and comforting.
2. Modern and efficient HTML5 and CSS3 wherever possible.
3. Modern and efficient pure JS by choice only, and only where required.

## Quickstart

To use Heater in your projects, you can simply copy and paste the minified css from `dist.css` into your HTML files (inline).

You will need to install the fonts yourself, they're available for download under the SIL Open Font License at the URLs listed in `fonts.sass`.

The *rest* of the project is licensed under the MIT License (see `LICENSE`).

## Documentation

The closest thing to documentation at the moment is in `examples/demo.html`, which serves as a showcase for all the features currently available.

## Building

There are two options for building your own versions of Heater:

```
./build-dev.sh
```

This will watch the input files in the `styles` folder, and output them one-to-one to the `dist` folder. This is most useful for development purposes.

```
./build-deploy.sh
```

This generates the `dist.css` file, which is already present in the repo. This is most useful for customised installations.

## Customisation

Most of the customisation takes place in the `fonts.sass` and `colours.sass` files. Here you can customise the colour scheme, and the fonts used.

The default colour scheme and font stack is a big part of what makes Heater the framework it is, but you're welcome to change it to something else you prefer.

## TODO

There are several things left to do before this becomes usable by any means:

* Better customisation
* More elements to handle media, particularly more images and audio and video
* JS-powered widgets such as modals, carousels, etc.
* A more efficiently handled font stack
* Accessibility and usability improvements
* Better documentation
* Screenshots!

Heater is designed to be independent of JS wherever possible, and will always provide reasonably good styling with pure, modern HTML5 and CSS. However there will be cases where JS is optionally needed for some components, and where JS can be used optionally to improve the styling of some component.