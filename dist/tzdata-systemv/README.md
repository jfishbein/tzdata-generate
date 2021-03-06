
## Synopsis

This is (a portion of) the [IANA TZ database](https://www.iana.org/time-zones), represented as JSON. Use this module in combination with [timezonecomplete](https://www.npmjs.com/package/timezonecomplete).
It is part of a set of similar modules:
* tzdata
* tzdata-africa
* tzdata-antarctica
* tzdata-asia
* tzdata-australasia
* tzdata-backward
* tzdata-etcetera
* tzdata-europe
* tzdata-factory
* tzdata-northamerica
* tzdata-pacificnew
* tzdata-southamerica
* tzdata-systemv
* tzdata-backward-utc

This module contains all zones of IANA TZ database file 'systemv'.



## TZ Database Version

2020a

## Use

In Node.JS, to get at the JSON data, simply do:

```javascript
var jsonData = require('tzdata-systemv');
```

In a browser, use the bundled UMD module provided in tzdata-systemv.js.

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>tzdata-systemv example</title>
    <script src="./tzdata-systemv.js"></script>
    <script>
        function onLoad() {
            var data = tzdataSystemv;
        }
    </script>
</head>
<body onLoad="onLoad()">
</body>
</html>
```

## License

MIT

## Zones in This Module


