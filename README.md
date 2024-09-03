# MERN-CODING-QnA




```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Increment Value on Button Click</title>
    
</head>
<body>
    <div class="counter" id="counter">0</div>
    <button class="button" id="incrementButton">Increase</button>
    <script src="script.js"></script>
</body>
</html>
```



```javascript


  let counterValue = 0;
  const counterElement = document.getElementById("counter");
  const incrementButton = document.getElementById("incrementButton");

  function increment() {
    counterValue++;
    counterElement.textContent = counterValue;
  }

  incrementButton.addEventListener("click", increment);


  

```

![alt text]("./image1.png")




```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1 id="output">0</h1>
    <button id="inc">increase</button>
    <button id="dec">decrease</button>
  </body>
</html>
```


```javascript

let one = document.getElementById("output");
let two = document.getElementById("inc");
let three = document.getElementById("dec");

let count = 0;

function increment() {
  count++;
  // one.textContent = count;
  one.innerHTML =count;
  // one.innerText = count;
}

function decrement() {
  count--;
  one.textContent = count;
}

two.addEventListener("click", increment);
three.addEventListener("click", decrement);

```


![alt text](./image2.png")
























