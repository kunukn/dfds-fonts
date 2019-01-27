# DFDS fonts

## main font from CDN

load the font by inluding this in html

```html
 <link rel="stylesheet" 
       href="https://unpkg.com/@kunukn/dfds-fonts/fonts/main/font.css">
```

or import it from css

```html
<style>
  @import "https://unpkg.com/@kunukn/dfds-fonts/fonts/main/font.css";
</style>
```

or load it dynamically from javascript
```html
<script 
  src="https://unpkg.com/@kunukn/dfds-fonts/fonts/main/font.js">
</script>
```

apply the font in css

```css
body {
  font-family: DFDS, sans-serif;
}
.font-bold {
  font-weight: bold;
}
.font-light {
  font-weight: 300;
}
.font-italic {
  font-style: italic;
}
```

use the font

```html
<p>this is a normal font</p>
<p class="font-bold">this is a bold font</p>
<p class="font-light">this is a light font</p>
<p class="font-italic">this is a italic style</p>
```


## main font from npm

* npm install @kunukn/dfds-fonts
* the files are in node_modules/@kunukn/dfds-fonts/fonts

load the font by inluding this in html

```html
<link rel="stylesheet" 
      href="node_modules/@kunukn/dfds-fonts/fonts/main/font.css">
```


## demo

* https://codepen.io/kunukn/pen/a9b31a0efb571cc6eadfa79d15a02501
* https://codesandbox.io/s/4x9496jqm4
* https://codepen.io/kunukn/pen/6f88297701bf62e8a4118015e02a507b?editors=0010


## more

To see all the available CDN files go to 

https://unpkg.com/@kunukn/dfds-fonts/


## url shortened link alternative

```html
 <link rel="stylesheet" href="https://bit.do/dfds-font">
```
