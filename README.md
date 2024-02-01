# Time Zone Field

Time Zone Field (tzfield) provides an autocomplete or select field for storing
time zones. It could be useful if, for example, you have a node type
representing a location such as city, office, station, etc., and you wish to
associate a time zone with these nodes. Time zone data is stored in the standard
[tz database](https://en.wikipedia.org/wiki/Tz_database) format, e.g.
`Europe/London`.


## Requirements

No special requirements.


## Installation

Install as you would normally install a contributed Backdrop module.


## Configuration

This module has no configuration, aside from field settings. For each time zone
field you create, you can select time zones to exclude from the allowed values,
enable either the autocomplete or select widget, and choose between the time
zone name and formatted current date formatters.

## Maintainers

The [Drupal version of this module]((https://www.drupal.org/project/issues/tzfield)) is maintained by [mfb](https://www.drupal.org/u/mfb).
