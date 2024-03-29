![JavaScriptGallery Logo](ressources/Logo.png)

  
[![current version](https://img.shields.io/badge/current%20version-0.2.0-green.svg)](https://github.com/marcelbohland/JavaScriptGallery/releases/tag/0.2.0)
[![last version](https://img.shields.io/badge/last%20version-0.1.7-blue.svg)](https://github.com/marcelbohland/JavaScriptGallery/releases/tag/0.1.7)
[![license](https://img.shields.io/badge/license-Apache%20License%202.0-red.svg)](https://github.com/marcelbohland/JavaScriptGallery/blob/main/LICENSE)


# Implementation
### Step 1 - include JS/CSS File:
JQuery and JQuery UI is required!
```html
<script src="{your URL}/gallery.js"></script>
<link rel="stylesheet" type="text/css" href="{your URL}/gallery.css" media="screen" />
```
### Step 2 - include HTML Tag:
```html
<div class="Gallery"></div>
```
### Step 3 - include Gallery Script:
```javascript
json = '{ "Entry": { "Title": "Gallery Demo", '+
'"Image": ["{your URL}/test.jpg",'+
'"{your URL}/test.jpg",'+
'"{your URL}/test.jpg",'+
'"{your URL}/test.jpg",'+
'"{your URL}/test.jpg",'+
'"{your URL}/test.jpg" ] } }';
addGallery(json);
json = '{ "Entry": { "Title": "Gallery 2", "Image": ["{your URL}/test.jpg", "{your URL}/test.jpg" ] } }';
addGallery(json);
```
# Implementation over HTML
[Documentation>>HTML](https://github.com/marcelbohland/JavaScriptGallery/blob/main/documentation/html.md)

# Documentation
[Documentation](https://github.com/marcelbohland/JavaScriptGallery/blob/main/documentation/documentation.md)

# License
Copyright 2021 Marcel Bohland - https://github.com/marcelbohland/JavaScriptGallery/

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
