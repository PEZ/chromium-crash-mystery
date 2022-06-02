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

https://user-images.githubusercontent.com/30010/171657274-9fafff3d-6436-4b7c-b5a0-ac11d8b8af02.mp4

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

https://user-images.githubusercontent.com/30010/171657400-bc9c0c03-f099-43e9-bb06-dee12531da03.mp4

And it doesn't crash:

* Safari
* Firefox

## Tweet

* https://twitter.com/pappapez/status/1532365130679439360
