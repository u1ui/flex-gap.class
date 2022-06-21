# flex-gap.class

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

