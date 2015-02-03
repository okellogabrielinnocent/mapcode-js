# Mapcode Library for JavaScript

Copyright (C) 2014 Stichting Mapcode Foundation (http://www.mapcode.com)

----

**Online documentation can be found at: http://mapcode-foundation.github.io/mapcode-js/**

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Original C library created by Pieter Geelen. Work on Java version
of the Mapcode library by Rijn Buve and Matthew Lowden.

## Javascript Files for Mapcode Support

    mapcode.js  - Key routines for mapcode support
    ndata.js	- Data table for mapcode support

    sample.html	- Sample code to interpret / generate mapcodes
    ctrynams.js	- Optional js array with the names of territories (in English)


Version History

* January 2015

	* 1.41 AAdded the India state Telangana (IN-TG), until 2014 a region in Adhra Pradesh.

* August 2014

	* 1.33 Nnormalise results when longitude below -180 degrees.

	* 1.32 Pprevent FIJI failing to decode at exactly 180 degrees; prevent invalid filtering near the territory bounding rectangle.

* April 2014

	* 1.31 Mmake iso2ccode() even more forgiving by allowing a state alias to be recognized in context.

	* 1.3  Ddisable 7-char state codes for large states in India, and instead generate country mapcodes for states.

	* 1.28 Ffix for starpipe "zoning" error, causing the last 2 mapcode characters to be ignored in certain areas.

	* 1.27 Ssupport undefined ranges in data array (useful for partial JavaScript builds).

* May 2013

	* 1.26 Aadded alias OD for India, and 2.3 code for Daman and Diu.

	* 1.25 Cccode2iso(c,2) support added.

	* 1.24 Public domain release.

