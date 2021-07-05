# Changelog

The present file will list all changes made to the project; according to the
[Keep a Changelog](http://keepachangelog.com/) project.

## [1.1.0] - 2021-06-28

Various schema update/fixes/improvements, including:

List instances under related database, makes updates easier
Do not allow additional properties
Handle no longer existing nodes; rename old networks/macaddr
Fix OS installation date
Various fixes
Disable replacements that should not exists (no if(in|out)(octets|bytes) in connections
Fix examples, missing backup date in dbs specs
Network compoonents can have ip and mac (wifi access points), and firmwares versions
Rework DB schema, rename main node
No ifalias on connections

## [1.0.9] - 2021-06-11

Add databases support
Few fixes on lod data
Add timezone support on datetime

## [1.0.8] - 2021-05-17

Missed conversions

## [1.0.7] - 2021-05-17

Fix invalid schema properties

## [1.0.6] - 2021-04-29

Schema validation was not effective

## [1.0.5] - 2021-03-24

Add partial inventory support

## [1.0.4] - 2021-03-19

Fix camera formats specs
Add designation on cameras

## [1.0.3] - 2021-03-11

Fix conversion in some cases
Fix conversion whith only one camera
Add remote management version

## [1.0.2] - 2021-01-20

Split download source files and conversion
Add separate download command

## [1.0.1] - 2021-01-20

Fix issue downloading iftypes source file
Add license

## [1.0.0] - 2021-01-18

First release; compatible with fusioninventory agent
