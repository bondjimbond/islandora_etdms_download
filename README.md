# Islandora ETDMS Download

## Introduction
Creates a download link for Thesis and Citation objects in the OAI-PMH results using the oai_etdms metadata prefix.

## Requirements

* [Islandora OAI](https://github.com/Islandora/islandora_oai)

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Just enable the module. Any OAI-PMH requests with the oai_etdms metadataPrefix will include an `<identifier>` element with a link to the PDF datastream. This link only appears for Thesis and Citation objects, and only if the PDF exists.

![Screenshot](https://i.imgur.com/0STIZ9z.png)

## Maintainer

* [Brandon Weigel](https://github.com/bondjimbond)

## License

* [GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
