# Anbani Noto
This is a fork of a popular fontface Noto developed by Google in colaboration with native font designers. 

## Installation
For personal use simply [download](https://github.com/Anbani/noto/archive/refs/heads/main.zip) the archive from this repository. 

For web developers you may use Anbani Noto fonts by including jsdelivr cdn links into your `.html`:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Anbani/noto@latest/css/AnbaniNotoSans.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Anbani/noto@latest/css/AnbaniNotoSerif.css">
```
or `@import` the css directly into your `.css`
```css
@import url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/css/AnbaniNotoSans.css');
@import url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/css/AnbaniNotoSerif.css');
```
or inject `@font-face` snippet into your `.css` file to minify number of requests.
```css
@font-face {
    font-family: 'Anbani Noto Sans';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.eot');
    src: url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.ttf') format('truetype'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSans-Regular.svg#anbani_noto_sans_regular') format('svg');
}

@font-face {
    font-family: 'Anbani Noto Serif';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.eot');
    src: url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.ttf') format('truetype'),
         url('https://cdn.jsdelivr.net/gh/Anbani/noto@latest/fonts/AnbaniNotoSerif-Regular.svg#anbani_noto_serif_regular') format('svg');
}

```

If you're having trouble delivering font files from jsdelivr CDN you may find GitHub source links useful. 
```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/Anbani/noto/main/css/AnbaniNotoSans.css">
<link rel="stylesheet" href="https://raw.githubusercontent.com/Anbani/noto/main/css/AnbaniNotoSerif.css">
```



## Why?
It is Noto's policy not to overlap their font files of different languages, which results in fonts like `Google Noto Sans Georgian` having absent not just Latin letters but even something as mandatory as a dot (`.`) or comma (`,`). This repository remedies the problem and contains a merged font families of `Google Noto` and `Google Noto Georgian`. This fork also fixes some of the longstanding bugs in Noto Sans Georgian tracked [here](https://github.com/googlefonts/noto-fonts/labels/Script-Georgian) more specifically [this](https://github.com/googlefonts/noto-fonts/issues/2046) one.


## LICENSE
This fontface is shared under the SIL OPEN FONT LICENSE Version 1.1 same as Google Noto and all of its modifications. Refer to https://github.com/Anbani/noto/blob/latest/LICENSE for more info.
