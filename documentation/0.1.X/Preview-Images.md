## Add preview images for faster webpage speed
1. Add #preview to the end of the Image url.
2. Add a smaller preview Image to the same path ({original_name}-preview.{original_file_extension})

.jpeg/.png/.jpg and .webp are supported

```javascript
json = '{ "Entry": { "Title": "Gallery Demo", '+
'"Image": ["{your URL}/test.jpg",'+
'"{your URL}/test.jpg#preview",'+
'"{your URL}/test.jpg#preview",'+
'"{your URL}/test.jpg#preview",'+
'"{your URL}/test.jpg#preview",'+
'"{your URL}/test.jpg#preview" ] } }';
addGallery(json);
```
