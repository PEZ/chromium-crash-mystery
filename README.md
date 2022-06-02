# Mysterious Chromium Crash

On My Machine™

This HTML crashes Chromium browsers on M1 Macbook Pro 2021 when I click the 'X'.

``` html
<html>
  <body>
    <select>
      <option>11 1</option>
    </select>
    X
  </body>
</html>
```

I need to have at least 'cc c' ('c' being any character). 'c c' doesn't make browsers crash, neither does 'cccc', or 'c cc'.

## My Machine

* Model Name:	MacBook Pro
* Model Identifier:	MacBookPro18,2
* Chip:	Apple M1 Max
* Total Number of Cores:	10 (8 performance and 2 efficiency)
* Memory:	32 GB
* System Firmware Version:	7459.101.3
* OS Loader Version:	7459.101.3

## Browsers:

Chromium browsers I've tried:

* Chrome
* Brave Intel
* Brave Apple Silicon
* Edge

It doesn't crash VS Code

It doesn't crash:

* Safari
* Firefox

## Tweet

* https://twitter.com/pappapez/status/1532365130679439360
