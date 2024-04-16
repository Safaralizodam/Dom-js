# Bom in JavaScript
 _The Browser Object Model __(BOM)__ is a collection of objects exposed by the browser that allow JavaScript to interact with the browser window, document, and other browser-specific functionalities._
![](https://learn.javascript.ru/article/browser-environment/windowObjects.svg)
_________
# Dom in JavaScript
 _A Document Object Model __(DOM)__ tree is a hierarchical representation of an HTML or XML document. It consists of a root node, which is the document itself, and a series of child nodes that represent the elements, attributes, and text content of the document._
![](https://media.licdn.com/dms/image/D5612AQH5fmP-swTDzA/article-cover_image-shrink_600_2000/0/1708162086067?e=2147483647&v=beta&t=OXUyP9RF5ir-eyB6Nwjp_Lr2iR9diwL-Fwa1dsp9lD0)

`innerHTML` -this property completely provides an easy way replace the elementary element. For example, all requirements
the element's body can be removed
```
document.body.innerHTML=''
```
**The Style object represents
an individual style statement.**
```
let box= document.quareselector('.box')
box.stule.color ='black'
box.stule.backgrandColor ='greey'
```
# Dom events
DOM Events allow JavaScript to add event listener or event handlers to HTML elements.
```
Examples

In HTML onclick is the event listener, myFunction is the event handler:

<button onclick="myFunction()">Click me</button>

In JavaScript click is the event, myFunction is the event handler:

button.addEventListener("click", myFunction);

```

