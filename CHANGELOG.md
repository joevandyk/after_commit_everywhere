# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 0.1.3 (2019-02-18)

- Make `in_transaction?` helper method public. ([@Envek])

## 0.1.2 (2018-05-01)

- [PR [#1](https://github.com/Envek/after_commit_everywhere/pull/1)] Enable ActiveRecord 4.2 support. ([@arjun810], [@Envek])

## 0.1.1 (2018-03-29)

- Do not issue warning on `after_commit` invocation outside of transaction as it is expected behaviour. ([@Envek])

## 0.1.0 (2018-03-18)

- Initial version with `after_commit`, `before_commit`. and `after_rollback` callbacks. ([@Envek])

[@Envek]: https://github.com/Envek "Andrey Novikov"
[@arjun810]: https://github.com/arjun810 "Arjun Singh" 
