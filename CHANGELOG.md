# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][keepachangelog], and this project adheres to [Semantic Versioning][semver].

## [0.1.0] – 2023-05-17

### Added

- A [Jinja2 extension][jinja-extensions] providing a [Jinja2 filter][jinja-filter] for validating data against a JSON/YAML schema within [Jinja2][jinja] templates.

- A [Jinja2 test][jinja-test] provided via the Jinja2 extension for validating data against a JSON/YAML schema within [Jinja2][jinja] templates.

- Make `typing-extensions` a runtime dependency to fix Python 3.7 usage as some `typing` backports are imported from `typing-extensions`. Python 3.8+ was not affected.

[jinja]: https://jinja.palletsprojects.com
[jinja-extensions]: https://jinja.palletsprojects.com/en/latest/extensions
[jinja-filter]: https://jinja.palletsprojects.com/en/latest/templates/#filters
[jinja-test]: https://jinja.palletsprojects.com/en/latest/templates/#tests
[keepachangelog]: https://keepachangelog.com/en/1.0.0
[semver]: https://semver.org/spec/v2.0.0.html

[0.1.0]: https://github.com/Krunal-Kevadiya/jinja2-jsonschema/releases/tag/v0.1.0
