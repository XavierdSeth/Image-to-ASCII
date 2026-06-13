# ascii art converter
 
converts any image into ascii art in your browser.
 
## why
 
i thought it was a cool little project and wanted to see if i could get it working with just vanilla html/css/js — no frameworks, no backend, nothing to install.
 
## what it does
 
- upload any image
- adjust the character width with a slider
- toggle colour mode to keep the original image colours
- runs entirely in the browser, works on any device
## how it works
 
uses a hidden `<canvas>` to sample pixel brightness from the image, maps each pixel to a character from a preset string (dark → light), then renders it as a `<pre>` block. colour mode wraps each character in a span with the original rgb value.
 
## setup
 
no install needed. just open `index.html` in a browser, or visit the live site at https://xaviers.website.

if you want to run it locally just clone the repo:
 
```
git clone https://github.com/XavierdSeth/Image-to-ASCII
```
 
then open `index.html`.
 
## files
 
```
index.html   - markup and js
style.css    - all the styling
CNAME        - for the website
LICENCE      - MIT Licence
README.md    - this file your reading
```
 
