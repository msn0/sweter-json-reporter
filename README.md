# JSON reporter for Sweter

This project refers to ``sweter``. If you are not familiar with ``sweter`` then take a look at [Sweter](https://github.com/msn0/sweter) first.

> `sweter-json-reporter` reports web performance timings in json format.

## Installation

Just install `sweter`

```sh
$ npm install sweter -g
```

## Usage

```
$ sweter google.com --reporter json
```

## Output

```
{"timeToFirstByte":210,"domInteractive":570,"domComplete":1664}
```

All timings in milliseconds.
