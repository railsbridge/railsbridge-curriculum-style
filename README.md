# Railsbridge Curriculum Style

This repository serves as a style guide and toolbox for writing railsbridge
curriculum.

Its is to be used to:

1. Maintain a consistent look and feel across each railsbridge tutorial
2. Provide CSS, JavaScript, images, and other assets that may be embedded into
   plain HTML pages to create a railsbridge-styled tutorial

## Usage

Ultimately we would like to distribute these assets using some kind of
cross-platform asset packaging system; such as bower. Until then:

1. Download a tagged release from github (or the master zip file)
2. Copy the `/dist` directory into your repo and ensure they're available via
   whichever web server you are using
3. Embed `railsbridge-curriculum-style/railsbridge.css` and
   `railsbridge-curriculum-style/railsbridge.js` into your HTML pages

To see appropriate html structure; browse `src/examples` directory.

## Compatibility

We're targeting HTML5 ready browsers only.

## Contributing

Contributions are welcome! We follow the [Contributor Code of
Conduct](CODE_OF_CONDUCT.md).

### Starting Development

1. Fork and clone the repo
1. Run `bin/setup` to install dependencies.

### Adding Features
1. Run `bin/serve` to launch a web server in the `generated` directory
1. Change the code
1. Ensure an example demonstrating your change exists in the `/src/examples`
1. Run `bin/build` to compile assets into the `generated` directory
1. Spot check to prove everything is amazing.
1. Submit a pull request describing your awesome feature.

### Releasing

6. Run `bin/release X.X.X` to build and minify assets into the `dist` directory
   and tag a release.


## License

Documentation is licensed under Creative Commons 3.0 Attribution.
Source code is licensed under the MIT license.

See [LICENSE.md](LICENSE.md) for more details.
