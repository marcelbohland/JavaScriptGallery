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
