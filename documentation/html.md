# Add Gallery over HTML instead of JavaScript

```html
    <h2>Gallery with video</h2>
      <div class="Gallery">
        <img src="https://dummyimage.com/800x400/00ff00/00ff00" />
        <img src="https://dummyimage.com/800x400/ffff00/00ff00" />
        <img src="https://dummyimage.com/800x400/00ffff/00ff00" />
        <img src="https://dummyimage.com/800x400/0fff00/00ff00" />
        <img src="https://dummyimage.com/800x400/0000ff/00ff00" />
        <img src="https://dummyimage.com/800x400/ff0000/00ffff" />
        <img src="https://dummyimage.com/800x400/0000ff/ffff66" />
        <img src="https://dummyimage.com/800x400/00ff00/ff3300" />
        <video width="320" height="240" autoplay="" muted="" loop="">
          <source
            src="https://www.w3schools.com/html/movie.mp4"
            type="video/mp4"
          />
        </video>
        <video width="320" height="240" autoplay="" muted="" loop="">
          <source
            src="https://www.w3schools.com/html/mov_bbb.mp4"
            type="video/mp4"
          />
        </video>
      </div>
    <script>
      setGalleryTransition("slideAndZoom");
      enableExtraButtons();
      enableDoubleClick();
      initGallery();
    </script>
```
