# Islandora Usage Stats [![Build Status](https://travis-ci.org/Islandora/islandora_usage_stats.png?branch=7.x)](https://travis-ci.org/Islandora/islandora_usage_stats)

## Introduction

A module for Drupal 7 to track views and downloads of Islandora items.

## Requirements

This module requires the following modules/libraries:

* [Tuque](https://github.com/islandora/tuque)
* [Islandora](https://github.com/islandora/islandora)
* [Islandora basic collection](https://github.com/Islandora/islandora_solution_pack_collection)
* [Views (3.x)](https://www.drupal.org/project/views)
* [Datepicker](https://www.drupal.org/project/datepicker)

## Configuration

Configuration options available at `admin/islandora/tools/islandora_usage_stats`.

## Features

* Toggle to ignore common bots
* View count uses session variables and defaults to a 5 minute cooldown for repeated requests
* Access log for all views and downloads
* IP Exclusion list to prevent artificially inflating counts while testing/developing/administrating
* Several customizable blocks to display metrics
* Report generating interface
* Object log views integration

## Notes

* Does not respect XACML.
* This is a server-side tracking solution, as such a caching layer could impact it.  If this is impacting you a [solution](https://github.com/discoverygarden/islandora_ga_reports) using JavaScript may work better.

## Troubleshooting/Issues

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## Maintainers/Sponsors

Work based on code from https://github.com/roblib/islandora_scholar_upei and the scholar_tracking module for Drupal 6. Iterated on by Ryerson University Library and Archives (RULA) and discoverygarden inc.

Current maintainers:

* [William Panting](https://github.com/willtp87)

Sponsors:

* [METRO](http://metro.org/)

## Development

If you would like to contribute to this module, please check out our helpful [Documentation for Developers](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers) info, as well as our [Developers](http://islandora.ca/developers) section on the Islandora.ca site.

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
