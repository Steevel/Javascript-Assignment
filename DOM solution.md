# Dom Manipulation Assignment Solutions

## Assignment 1

```javascript
var element = document.getElementsByClassName("crayons-card crayons-card--secondary p-4")[1];
element.firstElementChild.innerText = "Steevel Sharon Salis";
document.getElementsByClassName("color-base-70 mb-4")[1].innerText = "I Love Coding!!"
```

![solution screenshot](./Solutions/assignment%201.PNG)

## Assignment 2

```javascript
let products = document.getElementsByClassName("as-imagegrid-item-title")
let productNames = []
for (let i = 0; i < products.length; i++) {
    let productName = products[i].innerText
    productNames.push(productName.split("\n")[0])
}
console.log(productNames)
```

![solution screenshot](./Solutions/assignment%202.PNG)

## Assignment 3

```javascript
let accordian = document.getElementsByClassName("accordion-homepage")[0];
let myFAQ = document.createElement("section");
myFAQ.className = "parent"
let h3 = document.createElement("h3");
h3.textContent = "My New FAQ"
myFAQ.appendChild(h3);
accordian.appendChild(myFAQ);
```

![solution screenshot](./Solutions/assignment%203.PNG)

## Assignment 4

```javascript
document.querySelector(".one-tel-number.service-number").innerText = "123 456 7891"
```

![solution screenshot](./Solutions/assignment%204.PNG)

## Assignment 5

```javascript
let card = document.querySelector(".product-card-v2__item").children[1]
card.children[4].children[0].innerText = "Check out"
```

![solution screenshot](./Solutions/assignment%205.PNG)

## Assignment 6

```javascript
let searchbox = document.querySelector(".searchinput___zXLAR")
searchbox.addEventListener('mouseover', function changeColor(event) {
    searchbox.style.background = 'red';
})
searchbox.addEventListener('mouseout', function changeColor(event) {
    searchbox.style.background = '';
})
```

![solution screenshot](./Solutions/assignment%206.PNG)

## Assignment 7

```javascript
function search() {
    document.getElementById("hp-search-input").value = "CSS Selectors"
    document.querySelector("#hp-search-form").submit()
}
search()
```

![solution screenshot](./Solutions/assignment%207.PNG)

## Assignment 8

```javascript
let length = document.getElementById("SIvCob").children.length
for(let i = 0; i < length; i++){
    if(i % 2 == 0){
        document.getElementById("SIvCob").children[i].innerText = ""
    }
}

for(let i = 0; i < length-i; i++){
    let text = document.getElementById("SIvCob").children[i].innerText
    if(text === ""){
        document.getElementById("SIvCob").children[i].remove()
    }
}
```

![solution screenshot](./Solutions/assignment%208.PNG)

## Assignment 9

```javascript
document.querySelector(".display-heading-1").style.fontFamily = "monospace"
document.querySelector(".display-heading-1").style.color = "#B1361E"
```

![solution screenshot](./Solutions/assignment%209.PNG)

## Assignment 10

```javascript
let btnText = document.querySelector(".btn-cta-big.btn-block.signup-btn.btn-cta.btn.btn-default").children[1]
btnText.addEventListener("mouseover", () => (
    btnText.style.background = "red"
))
```

![solution screenshot](./Solutions/assignment%2010.PNG)

## Assignment 11

```javascript
document.querySelector(".icon.icon-logo.in").remove()
document.querySelector(".logo.gtag").appendChild(document.createElement("img"))
document.querySelector(".logo.gtag").children[0].setAttribute("src", "https://learn.ineuron.ai/_next/image?url=%2Fimages%2Fineuron-logo.png&w=750&q=75")
document.querySelector(".logo.gtag").children[0].style.width = "6em"
```

![solution screenshot](./Solutions/assignment%2011.PNG)

## Assignment 12

```javascript
document.querySelector(".btn-primary.btn").style.backgroundColor = "blue"
```

![solution screenshot](./Solutions/assignment%2012.PNG)

## Assignment 13

```javascript
document.querySelector(".fl-heading-text").innerText = "JSBOOTCAMP"
```

![solution screenshot](./Solutions/assignment%2013.PNG)

## Assignment 14

```javascript
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = '80px'
```

![solution screenshot](./Solutions/assignment%2014.PNG)

## Assignment 15

```javascript
document.querySelectorAll(".ps-title")[6].style.textAlign = "right"
```

![solution screenshot](./Solutions/assignment%2015.PNG)

## Assignment 16

```javascript
document.querySelectorAll(".section-title_title__VEDfK")[0].innerText = "Start with Scratch"
```

![solution screenshot](./Solutions/assignment%2016.PNG)

## Assignment 17

```javascript
let date = new Date().toString();
document.querySelector(".btn-container").firstChild.remove()
document.querySelector(".btn-container").innerHTML = `<p>${date.slice(0,25)} <br><br> ${date.slice(25)}</p>`
```

![solution screenshot](./Solutions/assignment%2017.PNG)

## Assignment 18

```javascript
document.querySelector(".p-f03-footer-container ").style.background = "orange"
```

![solution screenshot](./Solutions/assignment%2018.PNG)

## Assignment 19

```javascript
let source = document.querySelector(".logo").src
console.log(source)
```

![solution screenshot](./Solutions/assignment%2019.PNG)

## Assignment 20

```javascript
document.querySelector(".desc").style.color = "orange"
```

![solution screenshot](./Solutions/assignment%2020.PNG)
