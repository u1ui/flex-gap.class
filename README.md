# .u1-flex-gap - class
Most wanted flexbox case (also gaps in safari)


`u1-flex-gap` class to allow gaps in flex-boxes.

## Features

- Wrap by default
- Gaps by default (1rem)
- No overflow:hidden
- No minus margin on the right (prevents overflows)
- Margins are made using !important to prevent confusion

## Note

Uses margin and negative margin needed because of safari.  
Top, bottom and right margins are not allowed / overwritten.
Add a wrapper element if you like to add margin to the container

```html
<div style="margin:2rem">
  <ul class=u1-flex-gap>
    <li> first
    <li> second  
  </u1>
<div>
```

## Demos

https://raw.githack.com/u1ui/flex-gap.class/main/tests/minimal.html  
https://raw.githack.com/u1ui/flex-gap.class/main/tests/test.html

## Ussage

```html
<div class=u1-flex-gap>
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
    <div>Item 4</div>
    <div style="margin-right:auto">Item 5</div>
    <div>Item 6</div>
</div>
```

## Install

```html
<link href="https://cdn.jsdelivr.net/gh/u1ui/flex-gap.class@3.0.0/flex-gap.min.css" rel=stylesheet>
```

## Demo

https://raw.githack.com/u1ui/flex-gap.class/main/tests/minimal.html  
https://raw.githack.com/u1ui/flex-gap.class/main/tests/test.html  

## About

- MIT License, Copyright (c) 2022 <u1> (like all repositories in this organization) <br>
- Suggestions, ideas, finding bugs and making pull requests make us very happy. ♥

