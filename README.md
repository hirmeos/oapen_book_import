# OAPEN book import
[![Build Status](https://travis-ci.org/OpenBookPublishers/oapen_book_import.svg?branch=master)](https://travis-ci.org/OpenBookPublishers/oapen_book_import)


Take OAPEN's metadata CSV file containing title and URIs associated to a DOI and submit new findings to the identifier translation service.

## Run via crontab
```
0 13,21 * * * docker run --rm --name "book_importer" --env-file /path/to/config.env openbookpublishers/oapen_book_import
```
