# Consent Code Schemas [![](https://travis-ci.org/ga4gh/ga4gh-consent-policy.svg?branch=develop)](https://travis-ci.org/ga4gh/ga4gh-consent-policy) [![](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/ga4gh/ga4gh-consent-policy/develop/LICENSE) [![](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.com)

Data model for the data use conditions based on consent codes as introduced in [Consent Codes: Upholding Standard Data Use Conditions](http://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005772).

## How to contribute

Guidelines for contributing to this repository are listed in the [CONTRIBUTING.md](CONTRIBUTING.md) document.

## How to build

Prerequisites: Maven 3+, Java 1.6+.

To generate Java code, run `mvn package` and check the output in the `target` directory. 

## How to test

Prerequisites: Python 2.7 (incl. Pip 7+).

Install dependencies with `pip install -r requirements.txt`. To run the test suite, use `nosetests -v`.
