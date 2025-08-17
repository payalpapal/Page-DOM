window.open();

document.body.style.backgroundColor=pink;
VM151:1 Uncaught ReferenceError: pink is not defined
    at <anonymous>:1:37
(anonymous) @ VM151:1Understand this error
document.body.style.backgroundColor="pink";
'pink'
let img = document.createElement("img");
undefined
img.src = "[https://images.contentstack.io/v3/assets/bltcedd8dbd5891265b/blt5f18c2119ce26485/6668df65db90945e0caf9be6/beautiful-flowers-lotus.jpg?q=70&width=3840&auto=webp](https://hanablogs.azurewebsites.net/Content/BlogUpload/202402291148547768.jpg)";
img.style.width = "100vw";
'100vw'
img.style.height = "50vh";
'50vh'
img.style.objectFit = "cover";
'cover'
img.style.display = "block";
'block'
img.style.margin = "0 auto";
'0 auto'
document.body.appendChild(img);
<img src=​"[https:​/​/​images.contentstack.io/​v3/​assets/​bltcedd8dbd5891265b/​blt5f18c2119ce26485/​6668df65db90945e0caf9be6/​beautiful-flowers-lotus.jpg?q=70&width=3840&auto=webp](https://hanablogs.azurewebsites.net/Content/BlogUpload/202402291148547768.jpg)" style=​"width:​ 100vw;​ height:​ 50vh;​ object-fit:​ cover;​ display:​ block;​ margin:​ 0px auto;​">​


let heading = document.createElement("h1");
undefined
heading.textContent = "October Born Flower!!";
'October Born Flower!!'
heading.style.color = "black";
'black'
heading.style.textAlign = "center";
'center'
heading.style.fontSize = "2rem";
'2rem'
heading.style.marginTop = "20px";
'20px'
document.body.appendChild(heading);
<h1 style=​"color:​ black;​ text-align:​ center;​ font-size:​ 2rem;​ margin-top:​ 20px;​">​October Born Flower!!​</h1>

​let para = document.createElement("p");
undefined
para.textContent = "Octobers birth flowers are the Marigold and Cosmos.";
'Octobers birth flowers are the Marigold and Cosmos.'
para.style.color = "#ddd";
'#ddd'
para.style.fontSize = "1.2rem";
'1.2rem'
para.style.textAlign = "center";
'center'
para.style.maxWidth = "600px";
'600px'
para.style.margin = "20px auto";
'20px auto'
para.style.lineHeight = "1.6";
'1.6'
document.body.appendChild(para);
<p style=​"color:​ rgb(221, 221, 221)​;​ font-size:​ 1.2rem;​ text-align:​ center;​ max-width:​ 600px;​ margin:​ 20px auto;​ line-height:​ 1.6;​">​Octobers birth flowers are the Marigold and Cosmos.​</p>​
para.textContent = "The March birth flowers are daffodils and jonquils. These cheerful, yellow flowers are known for symbolizing rebirth, new beginnings, and unparalleled love, reflecting the start of spring in many parts of the world. Daffodils are particularly associated with hope and new opportunities. ";
The March birth flowers are daffodils and jonquils. These cheerful, yellow flowers are known for symbolizing rebirth, new beginnings, and unparalleled love, reflecting the start of spring in many parts of the world. Daffodils are particularly associated with hope and new opportunities. 
para.style.color = "black";
'black'


let button = document.createElement("button");
undefined
button.textContent = "Click Me";
'Click Me'
button.style.display = "block";
'block'
button.style.margin = "20px auto";
'20px auto'
button.style.padding = "20px 24px";
'20px 24px'
button.style.fontSize = "1.2rem";
'1.2rem'
button.style.border = "none";
'none'
button.style.borderRadius = "8px";
'8px'
button.style.cursor = "pointer";
'pointer'
button.style.backgroundColor = "orange";
'orange'
button.style.color ="
VM3802:1 Uncaught SyntaxError: Invalid or unexpected tokenUnderstand this error
button.style.color = "black";
'black'

button.style.boxShadow = "2px 2px 10px gray";
'2px 2px 10px gray'
document.body.appendChild(button);
<button style=​"display:​ block;​ margin:​ 20px auto;​ padding:​ 20px 24px;​ font-size:​ 1.2rem;​ border:​ none;​ border-radius:​ 8px;​ cursor:​ pointer;​ background-color:​ orange;​ color:​ black;​ box-shadow:​ gray 2px 2px 10px;​">​Click Me​</button>

let card = document.createElement("div");
undefined
card.style.width = "300";
'300'
card.style.margin = "20px auto";
'20px auto'
card.style.pad = "20px";
'20px'
card.style.padding = "20px";
'20px'
card.style.borderRadius  = "12px";
'12px'
card.style.boxShadow = "0 5px 15px black";
'0 5px 15px black'
card.style.backgroundColor = "#333";
'#333'
card
<div style=​"width:​ 300px;​ margin:​ 20px auto;​ padding:​ 20px;​ border-radius:​ 12px;​ box-shadow:​ black 0px 5px 15px;​ background-color:​ rgb(51, 51, 51)​;​">​</div>​
card.style.textAlign = "center";
'center'
document.body.appendChild(card);
<div style=​"width:​ 300px;​ margin:​ 20px auto;​ padding:​ 20px;​ border-radius:​ 12px;​ box-shadow:​ black 0px 5px 15px;​ background-color:​ rgb(51, 51, 51)​;​ text-align:​ center;​">​</div>

let cardTitle = document.createElement("h2");
undefined
cardTitle.textContent = "javaScript Rocks!";
'javaScript Rocks!'
cardTitle.style.color = "white";
'white'
card.appendChild(cardTitle);
<h2 style=​"color:​ white;​">​javaScript Rocks!​</h2>

let cardText = document.createElement("p");
undefined
cardText.textContent = "This card was created using javaScript! ";
'This card was created using javaScript! '
cardText.style.color = "white";
'white'
cardText.style.fontSize= "1rem";
'1rem'
cardText.style.marginTop= "10px";
'10px'
card.appendChild(cardText);
<p style=​"color:​ white;​ font-size:​ 1rem;​ margin-top:​ 10px;​">​This card was created using javaScript! ​</p>

document.body.style.display = "flex";
'flex'
document.body.style.flexDirection = "column";
'column'
document.body.style.alignItems = "center";
'center'
document.body.style.justifyContent = "center";
'center'
document.body.style.height = "100vh";
'100vh'
document.body.style.fontFamily = "Arial,sans-serif";
'Arial,sans-serif'​​​​
