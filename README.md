# JavaScriptGallery

# Implementation
### step 1 - include JS/CSS File:
JQuery and JQuery UI is required!
```
<script src="{your URL}/gallery.js"></script>
<link rel="stylesheet" type="text/css" href="{your URL}/gallery.css" media="screen" />
```
### step 2 - include Gallery Script:
```javascript
json = '{ "Entry": { "Title": "Gallery Demo", '+
'"Image": ["{your URL}/f.jpg",'+
'"{your URL}/g.jpg",'+
'"{your URL}/f.jpg",'+
'"{your URL}/g.jpg",'+
'"{your URL}/f.jpg",'+
'"{your URL}/g.jpg" ] } }';
addGallery(json);
json = '{ "Entry": { "Title": "Gallery 2", "Image": ["{your URL}/f.jpg", "{your URL}/g.jpg" ] } }';
addGallery(json);
```
### step 3 - include settings (optional):
All settings parameters must be inserted before the addGallery() function


Transitions:

opacity
zoomin
slide
slideAndZoom
slideZoom
ZoominFast
bounce
puffzoom
```javascript
setGalleryTransition("opacity");
```
Enable optional buttons like share
```javascript
enableExtraButtons();
```
Change backgroundcolor
```javascript
backgroundColor("#000000f7");
```
Change Gallery Style
```javascript
setGalleryStyle("tiles");
setGalleryStyle("center");
setGalleryStyle("Circles");
setGalleryStyle("full");
```
# Image viewer
Add "galleryJS" to img tags!
For a full Viewer add "addToGallery" too

# License
Copyright 2021 Marcel Bohland - https://github.com/marcelbohland/JavaScriptGallery/

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
