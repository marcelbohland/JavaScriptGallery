# Optional settings:
All settings parameters must be inserted before the addGallery() function


Transitions:


```javascript
setGalleryTransition("opacity");
setGalleryTransition("zoomin");
setGalleryTransition("slide");
setGalleryTransition("slideAndZoom");
setGalleryTransition("slideZoom");
setGalleryTransition("ZoominFast");
setGalleryTransition("bounce");
setGalleryTransition("puffzoom");
```
Enable double click in gallery viewer
```javascript
enableDoubleClick();
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
setGalleryStyle("mosaic");
```
# Image viewer
Add "galleryJS" to img tags!
For a full Viewer add "addToGallery" too

# Add preview Images
1. Add #preview to the end of the Image url.
2. Add a smaller preview Image to the same path ({original_name}-preview.{original_file_extension})

.jpeg; .png; .jpg and .webp are supported
# Galery Slider
1. Add the following HTML code to your website
```html
     <div class="GallerySlide">
                <svg onClick="gallerySlideLeft()" class="nav_left" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="48px" height="48px"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M15.41 16.59L10.83 12l4.58-4.59L14 6l-6 6 6 6 1.41-1.41z"/></svg>
                <img class="codeImage galleryJS" width="600px" height="324px" src="https://dummyimage.com/800x400/aa550/fff000" alt="source code">
                <img class="codeImage galleryJS addFill" width="600px" height="324px" src="https://dummyimage.com/800x400/ff0000/000" alt="source code">
                <img class="codeImage galleryJS" width="600px" height="324px" src="https://dummyimage.com/800x400/00ff00/00ff00" alt="source code">
                <img class="codeImage galleryJS" width="600px" height="324px" src="https://dummyimage.com/800x400/0000ff/0000ff" alt="source code">
                <svg onClick="gallerySlideRight()" class="nav_right" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="48px" height="48px"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M8.59 16.59L13.17 12 8.59 7.41 10 6l6 6-6 6-1.41-1.41z"/></svg>
     </div>
     <div class="GallerySlideDots"></div>
```

2. Initialize the gallery slide
```javascript
   //animation duration, enable/disable animation , enable/disable dots under the slider
   initGallerySlide(300, true, true);
````

# Move Elemets

If you want to move an element between two other elements on a web page, this is often very difficult if the element was not originally between these two elements...

1. Add the following Tag to the move position
```html
[element1]
<move id="move_2155" mediaquery="768" ></move>
[element2]
```
2. Add a id like this example to a element on your website (the id behind element_ must be the same as behind move_)
```html
 <img id="element_2155" src="https://via.placeholder.com/150" >
```
3. Initialize the move
```javascript
   initMove();
````
4. Now the element is moved at a resolution of 768 pixels between the two elements

# Debug

Get a lot information for debuging
```javascript
   //run this in the webbrowser console
   Debug()
````
   
