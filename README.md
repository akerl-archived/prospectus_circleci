prospectus_circleci
=========

[![Gem Version](https://img.shields.io/gem/v/prospectus_circleci.svg)](https://rubygems.org/gems/prospectus_circleci)
[![Dependency Status](https://img.shields.io/gemnasium/akerl/prospectus_circleci.svg)](https://gemnasium.com/akerl/prospectus_circleci)
[![Build Status](https://img.shields.io/circleci/project/akerl/prospectus_circleci.svg)](https://circleci.com/gh/akerl/prospectus_circleci)
[![Coverage Status](https://img.shields.io/codecov/c/github/akerl/prospectus_circleci.svg)](https://codecov.io/github/akerl/prospectus_circleci)
[![Code Quality](https://img.shields.io/codacy/c5623564a4034ece993510d28edb19de.svg)](https://www.codacy.com/app/akerl/prospectus_circleci)
[![MIT Licensed](https://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)

[Prospectus](https://github.com/akerl/prospectus) helpers for checking CircleCI build status

## Usage

Add the following 2 lines to the .prospectus:

```
## Add this at the top
Prospectus.extra_dep('file', 'prospectus_circleci')

## Add this inside your item that has a build
extend ProspectusCircleci.build('ORG/REPO')
```

## Installation

    gem install prospectus_circleci

## License

prospectus_circleci is released under the MIT License. See the bundled LICENSE file for details.

