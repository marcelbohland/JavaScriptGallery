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
