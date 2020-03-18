# cities1000

This is a dataset with the latitude and longitude of all cities on planet earth
with greater than 1000 people.

**Last Updated at 18 March 2020**

You can find the original on
[geonames.org](http://download.geonames.org/export/dump/).

# example

```
var fs = require('fs');
var cities = require('cities-with-1000');
var lines = fs.readFileSync(cities.file, 'utf8').split('\n');
// ...
```

# attributes

``` js
var cities = require('cities-with-1000');
```

## cities.file

Open the `cities.file` for reading as a tab-separated text file.

## cities.fields

This is the array of fields in the `cities.file` text file.

# license

copyright [geonames.org](http://www.geonames.org/)

creative commons attribution 3.0
([CC-BY](http://creativecommons.org/licenses/by/3.0/))