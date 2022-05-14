# Add Event Listener

Using the browser console, attach an event listener of any type to [this page](http://www.republiquedesmangues.fr/). Be creative! Here is one example (click the mango after running this code):

```js
const mango = document.querySelector('#mangue');
mango.addEventListener('click', function (event) {
  mango.style.animation = 'spin'
  mango.style.animationDuration = '0.5s'
  mango.style.animationIterationCount = 'infinite'
  mango.style.animationTimingFunction = 'linear'
})
mango.addEventListener('click', event => {
  console.log ("MAAANNNNNNNGOOOOOOOO")
})
```
