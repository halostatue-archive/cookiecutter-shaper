# cookiecutter-shaper

[![Travis CI - Build Status][travis.svg]][travis]
[![Github - Last tag][tags.svg]][tags]

A [Cookiecutter][] template for creating a cookiecutter template. Requires
Cookiecutter 1.3 or better.

## Usage

Create a new cookiecutter template from cookiecutter-shaper:

```bash
cookiecutter gh:halostatue/cookiecutter-shaper
```

## Special Features

### Copy hooks

> since 0.1.1    
Setting: `copy_hooks`    
Default value: `no`    
If set to `yes` the hooks directory is copied to the generated template.


## History

cookiecutter-shaper is based on [eviweb/cookiecutter-template][] and
[FGtatsuro/cookiecutter-cookiecutter-template][].

## Contributing

1.  If you'd like to contribute, fork this [repository][], and send a pull
    request.

2.  To install dev requirements: `pip install -r requirements-dev.txt`.

3.  To run tests from the root of the project directory: `mamba`

4.  New features require specifications. Specifications are done using
    [Mamba][] and lie under the `./specs` directory.

License
-------
This project is licensed under the terms of the [MIT License](LICENSE.md)

[travis.svg]: https://travis-ci.org/halostatue/cookiecutter-shaper.svg
[travis]: https://travis-ci.org/halostatue/cookiecutter-shaper
[tags.svg]: https://img.shields.io/github/tag/halostatue/cookiecutter-shaper.svg
[tags]: https://github.com/halostatue/cookiecutter-shaper/tags
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[eviweb/cookiecutter-template]: https://github.com/eviweb/cookiecutter-template
[FGtatsuro/cookiecutter-cookiecutter-template]: https://github.com/FGtatsuro/cookiecutter-cookiecutter-template
[Mamba]: http://nestorsalceda.github.io/mamba/
[repository]: https://github.com/halostatue/cookiecutter-shaper
