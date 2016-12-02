# {{ cookiecutter.project_name }}

[![Travis CI - Build Status][travis.svg]][travis]
[![Github - Last tag][tags.svg]][tags]

{{ cookiecutter.project_short_description }}

## Requirements

Install the `cookiecutter` command line: `pip install cookiecutter`.

## Usage

Generate a new Cookiecutter template layout:

```bash
cookiecutter gh:{{cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
```

## Contributing

1.  If you'd like to contribute, fork this [repository][], and send a pull
    request.

2.  To install dev requirements: `pip install -r requirements-dev.txt`.

3.  To run tests from the root of the project directory: `mamba`

4.  New features require specifications. Specifications are done using
    [Mamba][] and lie under the `./specs` directory.

## License

This project is licensed under the terms of the [MIT License](LICENSE.md)

[travis.svg]: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg
[travis]: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
[tags.svg]: https://img.shields.io/github/tag/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg
[tags]: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tags
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[Mamba]: http://nestorsalceda.github.io/mamba/
[repository]: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
