# OAPEN book import
[![Build Status](https://travis-ci.org/hirmeos/oapen_book_import.svg?branch=master)](https://travis-ci.org/hirmeos/oapen_book_import) [![Release](https://img.shields.io/github/release/hirmeos/oapen_book_import.svg?colorB=58839b)](https://github.com/hirmeos/oapen_book_import/releases) [![License](https://img.shields.io/github/license/hirmeos/oapen_book_import.svg?colorB=ff0000)](https://github.com/hirmeos/oapen_book_import/blob/master/LICENSE)


Take OAPEN's metadata CSV file containing title and URIs associated to a DOI and submit new findings to the identifier translation service.

## Run via crontab
```
0 13,21 * * * docker run --rm --name "book_importer" --env-file /path/to/config.env openbookpublishers/oapen_book_import
```
