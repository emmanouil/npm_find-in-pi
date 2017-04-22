Find in Pi
=========
A small library that returns the location (index) of a number in the first ~1.5m decimal digits of Pi.
Supported commands:
 - `.findInPi(<number>)` (returns index of _number_, starting counting after the decimal. i.e. for n=1 returns 1)
 - `.getPi()` (returns, as `String` the Pi series used for any search)


## Installation

  `npm install find-in-pi`

## Usage

    var fip = require('find-in-pi');

    var numIndex = fip.findInPi(1900);
  
  
  Output should be `4791`


## Tests

  `npm test`

## Contributing

...is welcome :)
