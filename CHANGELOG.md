# Gerapy Auto Extractor Changelog

## 0.0.4 (2020-07-09)

### Bug Fixes

* Fix missed extraction of list extractor
* Removed unnecessary logs unless set `APP_DEBUG` to `true`
* Fix extraction of content from `<footer>` tag

### Features

* Add support for `base_url` arg of `extract_list` method
* Add test cases in `tests` folder
* Add more samples in `samples` folder
* Add `jsonify` method for converting json format
* Remove blank lines from result of `extract_content` method
* Add property `nth` in Element Class
* Add `nth` suffix of `alias` property in Element Class