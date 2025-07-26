
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>copps.com</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- my css -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fontawesome/6.6.0/css/all.min.css"/>
<!-- signin/signup starts-->
<section id="search">
    
  <style>
    

    *{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: "poppins",Sans-Serif;
}

html, body {
  height: 100%;
  width: 100%;
  background-color: #cad6ff;
  background: #c9d6ff;
}

.all{
width: 900px;
height: 600px;
align-items: center;
margin: 20px auto;
}
#signuppage{
background: #fff;
width: 450px;
padding: 1.5rem;
margin: 50px auto;
border-radius: 10px;
box-shadow: 0 20px 35px rgb(0,0,1,0.9);
}
#signinpage{
background: #fff;
width: 450px;
padding: 1.5rem;
margin: 50px auto;
border-radius: 10px;
box-shadow: 0 20px 35px rgb(0,0,1,0.9);
}
form {
margin: 0, 2rem;
}
.form-title{
font-size: 1.5rem;
font-weight: bold;
text-align: center;
padding: 1.3rem;
margin-bottom: 0.4rem;
}
input{
color: inherit;
width: 100%;
background-color: transparent;
border: none;
border-bottom: 1px solid #757575;
font-size: 15px;
}
.input-group{
padding: 1% 0;
position: relative;
}
.input-group:{
position: absolute;
color: black;
}
input:focus{
background-color: transparent;
outline: transparent;
border-bottom: 2px solid hst(327, 90%) ;
}
input:: placeholder{
color:transparent;
}
}
label{
color: 757575;
position: relative;
left: 1.2em;
top: -1.3em;
cursor: auto;
transition: 0.3s ease all;
}
input:focus-label,input:not(placeholder-shown) label{
top: -3em;
color: hsl(327,90%, 28%);
font-size: 15px;
}
.recover{
text-align: right;
font-size: 1rem;
margin-bottom: 1rem;
}
.recover a {
text-decoration: none;
color: rgb(125,125,125);
}
.recover a:hover{
color: blue;
text-decoration: underline;
}
.btn{
font-size: 1.1rem;
padding: 8px 0;
border-radius: 5px;
outline: none;
border: none;
width: 100%;
background: rgb(125,125,125,235);
color: white;
cursor: pointer;
transition: 0.85s;
}
.btn:hover{
background: #07001f;
}

.btn2 {
font-size: 1.1rem;
padding: 8px 0;
border-radius: 5px;
outline: none;
border: none;
width: 100%;
background: rgb(125,125,125,235);
color: white;
cursor: pointer;
transition: 0.85s;
}
.or{
font-size: 1.1rem;
margin-top: 0.5rem;
text-align: center;
}
.icons{
text-align: center;
}
.icon i {
color: rgb(125,125,235);
padding: 0.8rem 1.5rem;
border-radius: 10px;
font-size: 1.5rem;
cursor: pointer;
border: 2px solid #dfe9f5;
margin: 0 15px;
transition: 1s;
}
.icon i: hover{
background: #07001f;
font-size: 1.6rem;
border: 2px solid rgb(125125,235);
}
.links{
display: flex;
justify-content: soace-around;
padding: 0 4rem;
margin-top: 0.9rem;
font-weight: bold;
}
button{
color: rgb(125,125,235);
border: none;
font-size: 1rem;
font-weight: bold;
}
button:hover{
text-decoration: underline;
color: blue;
}
  </style>
</head>

<body>

<div id="signuppage">

<div class="card p-4" id="signupPage">
  <h1 class="form-title">Sign Up</h1>
  <div class="mb-3 position-relative">
    <input type="text" class="form-control" id="signupUsername" placeholder="Choose Username">
  </div>

  <div class="mb-3 position-relative">
    <input type="password" class="form-control" id="signupPassword" placeholder="Choose Password">
    <span class="toggle-password" onclick="togglePassword('signupPassword', this)"></span>
  </div>

  <button class="btn btn-success w-100" onclick="signup()">Sign Up</button>

  <div class="text-center mt-3">
    <button class="toggle-link" onclick="showLogin()">Already have an account?</button>
  </div>
</div>



<div class="card p-4" id="loginPage" style="display:none;">

  <h3 class="form-title">Login</h3>
  <div class="mb-3 position-relative">
    <input type="text" class="form-control" id="loginUsername" placeholder="Enter Username">
  </div>

  <div class="mb-3 position-relative">
    <input type="password" class="form-control" id="loginPassword" placeholder="Enter Password">
    <span class="toggle-password" onclick="togglePassword('loginPassword', this)">👁️</span>
  </div>

  <button class="btn btn-primary w-100" onclick="login()">Login</button>

  <div class="text-center mt-3">
    <button class="toggle-link" onclick="showSignup()">Don't have an account?</button>
  </div>
</div>

<div class="card p-4" id="shopPage" style="display:none;">
  <h4>Hello <span id="userDisplay"></span>!</h4>

  <div id="products" class="mt-3">
    



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>copps.com</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>
<body>
<header>
<div class="menu-toggle">
<div class="menu-icon">
<span></span>
<span></span>
<span></span>
</div>
<div class="close-icon" style="display: none;">
<div class="exit">
<i class="fa fa-times" ></i>
</div>
</div>
</div>
<div class="menu" style="display: none;">
<!-- menu content here -->
<section id="header">
<ul id="navbar">
<li> <a class="actie" href="home.html">
<i class="fa fa-home" aria-hidden="true"></i> HOME
</a></li>
<li> <a href="#products">PRODUCTS</a></li>
<li> <a href="#cartList">
<i class="fa fa-shopping-basket" aria-hidden="false"></i>CART LIST
</a></li>
<li> <a href="about.html">ABOUT</a></li>
<li> <a href="
https://www.google.com/maps/@-15.4140672,28.2984448,9z?force=qVTs2FOxxTmHHo79-
pwa&source=mlapk
">
<i class="fa fa-map-marker" aria-hidden="true"></i>LOCATION
</a></li>
<li> <a

onclick="viewOrders()">HISTORY</a></li>
<li> <a href="file:///C:/Users/ADMIN/Desktop/COPPS/project defence/QUIZ/QUIZ.html">TAKE A QUIZ</a></li>
<li> <a href="status.html">STATUS
<i class="fa fa-handshake-o" aria-hidden="true"></i>
</a></li>
</ul>
</section>
</div>
</header>
<!-- Search bar starts-->
<div class="all">
<section id="search">
<h1>WELCOME TO COPPS</h1>
<p>where high customer satisfaction is priotised</p>
</head>
<body>
<div class="search-container">
<input type="text" id="searchInput" class="search-input" placeholder="Search in COPPS">
<button onclick="searchGoogle()" class="search-button">Search</button>
</div>
<div class="ad-container">
<div class="ad-text active"><p id="ad">EVERY TRANSACTION <br>INCREASES <br>YOUR
LOYALTY POINTS</p></div>
<div class="ad-text"><p id="ad">SHOP NOW AND <br>EARN MORE POINTS</p></div>
<div class="ad-text"> <p id="ad">MAKE YOUR 5 POINTS AND <br>GET 50% DISCOUNT<br>
ON YOUR NEXT<br>ORDER</p></div>
<div class="ad-text"><p id="ad">GET YOUR FREE PRIZES <br>ON WEEKENDS</p></div>
<div class="ad-text"><h1>COPPS!</h1><p id="ad">ACHIEVING HIGH <br>CUSTOMER
SATISFACTION!!</p></div>
<div class="flowers">
<div class="flower"></div>
<div class="flower"></div>
<div class="flower"></div>
<div class="flower"></div>
<div class="flower"></div>
</div>
<div class="balloons">
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>
</div>
</div>
<div class="wheel">
<div class="wheel-spinner"></div>
</div>
<div><pre>stay here and enjoy customer freshment!! otherwise its too hot out side
COPPS</pre></div>


<!--products-->
<section id="products">
<section
id="product1" class="section-p1">
<h1>LATEST PRODUCTS AVAILABLE</h1>
<p>choose the product you want to buy and click 'BUY' button to add the product to cart list.
</p>
<div class="pro-comtainer">

   
      
<div class="pro">
<img src="file:///storage/emulated/0/Pictures/facebook/1746466746755.jpg" alt="image unavailable">
<div class="des">
<span>
Android
</span>
<h5>Techno Spark 20 pro</h5>
<div class="star">
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<p>k14950.00</p>
<button onclick="addToCart('Techno Spark 20 pro', 14950.00)">
<i class="fa fa-cart-plus"></i>
BUY</button>
</div>
</div>
</div>



    <div class="pro">
    <img src=" file:///C:/Users/BLAQDRUM/Desktop/project defence/images/fridge.jpeg" alt="image unavailable">
    <div class="des">
        <span>
        sumsung
        </span>
        <h5>SUMSUNG REFRIGIRATOR</h5>
        <div class="star">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <p>k8950.00</p>
        <button onclick="addToCart('SUMSUNG REFRIGILATOR', 8950.00)">
        <i class="fa fa-cart-plus"></i>
        BUY</button>
        </div>
        </div>
        </div>
    
        <div class="pro">
            <img src="file:///C:/Users/BLAQDRUM/Desktop/project defence/images/tv.jpg " alt="image unavailable">
            <div class="des">
            <span>
            Hisense
            </span>
            <h5>HD SMART TV</h5>
            <div class="star">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <p>k4000.00</p>
            <button onclick="addToCart('HD SMART TV', 4000.00)">
            <i class="fa fa-cart-plus"></i>
            BUY</button>
            </div>
            </div>
            </div>
        
                      
</div>
</section>
</section>
<section id="burner">
    <h4>DO YOU WANT TO PURCHASE ONE BUT HAVE INSUFICIENT FUNDS?</h4>
    <h2>WITH COPPS <span> YOU CAN PAY 50% CASH</span> AND 50% WILL BE PAID IN MONTHLY INSTALMENTS  </h2>
    <h2><a href="">TERMS </a>& <a href="">CONDITIONS </a> APPLY</h2>
</section>
<section id="1">
   <style>

        #cart h2{
            color: blue;
            text-align: center;
            text-decoration: underline;
        }
        #cart p{
            color: deeppink;
            display: flex;
            margin-left: 50px;
            font-size: 30px;
        }
        h4{
            color: dodgerblue;
        }
    </style>
    
         
         
<section id="cartlist">
    <div id="cart">
  <h2 class="mt-4">ITEMS IN YOUR CART LIST WILL SHOW HERE:</h2>
  <ul id="cartList" class="list-group mb-3"></ul>
  
  
<ul id="cartList" class="list-group"></ul>
<div id="totalPrice" class="mt-2 fw-bold"></div>
</div>
  </section>
    
         </section>
        </section>
<!--stylesheet starts -->
<style>

#header{
display: flex;
align-items: center;
justify-content:
space-between;
padding: 20px 80px;
background: rgb(255,155,255);
box-shadow: 0 5px 10px rgb(0,0,0,0.9);
width: 900px;
position: fixed;
top: 0;
left: 0;
}
#navbar{
display: flex;
align-items: center;
justify-content: center;
}
#navbar li{
list-style: none;
padding: 0 20px;
position: relative;

}
#navbar li a{
text-decoration:none ;
font-size: 16px;
font-weight: 600;
color: #1a1a1a;
transition: 0.3s ease;
}
#navbar li a:hover,
#navbar li a.active{
color: #088178;
}
#navbar li a.active ::after,
#navbar li a:hover::after
{
content:"" ;
width: 60.7%;
height: 2px;
background: #088178;
position: absolute;
bottom: -4px;
left: 20px;
}
#search {
text-align:center;
}
#footer{
position: relative;
bottom: 0;
left:0;
width: 100%;
background-color:rgb(255,155,255);
color: #fff;
padding: 5px;
text-align: center;
z-index: 1000;
}
.menu-toggle {
cursor: pointer;
position: fixed;
top: 10px;
left: 10px;
z-index: 1000;
}
.menu-icon span {
display: block;
width: 20px;
height: 2px;
background-color: #333;
margin-bottom: 5px;
transition: all 0.3s ease;
}
.close-icon {
position: absolute;
top: 0;
left: 0;
}
.triangle {
width: 0;
height: 0;
border-style: solid;
border-width: 10px 10px 0 10px;
border-color: #333 transparent transparent transparent;
}
.ad-container {
width: 900px;
height: 600px;
overflow: hidden;
position: relative;
border: 1px solid #cbc;
top: 50px;
align-items: center;
margin: 20px auto;
border: 1px solid #ccc;
border-radius: 10px;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
font-size: 4vw;
word-wrap: break-word;
overflow-wrap: break-word;
text-overflow: ellipsis;
white-space: nowrap;
}
.ad-text {
position: absolute;
white-space: nowrap;

opacity: 0;
transition: opacity 1s;
}
.ad-text.active {
opacity: 1;
}
#ad {
color: rgb(200,90,200);
font-size:50px;
text-align: center;
text-shadow:
5px 2px 10px rgba(0, 0, 0, 0.2);
}
.ad-container h1{ text-align: center;
font-size: 50px;
color: rgb(00,00,200);
text-shadow: 10px 4px 10px rgba(0, 0, 0, 0.3);
}
.flowers {
position: absolute;
top: 300px;
left: 500px;
width: 100%;
height: 100%;
}

.flower {
position: absolute;
width: 50px;
height: 50px;
background-color: #ff69b4;
border-radius: 90%;
animation: flower-animation 5s infinite;
}
.balloons {
position: absolute;
top: 300px;
left: 200px;
width: 100%;
height: 100%;
align-items: center;
}
.balloon {
position: absolute;
width: 30px;
height: 60px;
background-color: #add8e6;
border-radius: 50%;
animation: balloon-animation 5s infinite;
}
@keyframes flower-animation {
0% {
transform: translate(0, 0);
}
25% {
transform: translate(50px, -50px);
}
50% {
transform: translate(100px, 0);
}
75% {
transform: translate(50px, 50px);
}
100% {
transform: translate(0, 0);
}
}
@keyframes balloon-animation {
0% {
transform: translate(0, 100%);
}
25% {
transform: translate(-50px, 50%);
}
50% {
transform: translate(0, 0);
}
75% {
transform: translate(50px, 50%);
}
100% {
transform: translate(0, 100%);
}
}
#product1{
text-align: center;
}
#product1  h1 {
    color: crimson;
    font-size: 30px;
    text-decoration: underline;
    text-decoration-color: #4285f4;
    
}
#product1  p{
    color: darkgreen;
}
#product1 .pro{
width: 23%;
min-width: 25px;
padding:10px 12px;
border: 1px solid #cce7d0 ;
border-radius: 25px;
cursor: pointer;
box-shadow: 20px 20px 30px rgba(0,0,0,0.2);
margin: 15px 0;
transition: 0.2s ease;
}

#product1 .pro:hover{
box-shadow: 20px 20px 30px rgba(0,0,0,0.6);
}
#product1 .pro img{
width: 100%;
border-radius: 20px;
}
#product1 .pro.des{
text-align: start;
padding:10px o ;
}
#product1 .pro .des span {
    color: #088178;
    font-size: 12px;
}
#product1 .pro .des h5 {
    padding-top: 7px;
    color: #4285f4;
    font-size: 14px;
}
#product1 .pro .des i {
    font-size: 12px;
    color: burlywood;
}
#product1 .pro .des p {
  padding-top: 7px; 
  font-size: 15px; 
  font-weight: 700;
  color: blue;
}
#product1 .pro .des button:hover {
    background-color: crimson;
}
#product1 .pro-comtainer {
    display: flex;
    justify-content: space-between;
    padding-inline: 20px;
    padding-top: 20px;
    flex-wrap: wrap;
}
#burner{
    background-color: #dcecea;
}
#burner h4{
    color: rgb(230, 11, 11);
    text-decoration: overline;
    font-size: 20px;
}
#burner span{
    color: #f0f;
}
.wheel {
position: relative;
width: 100px;
height: 200px;
border-radius: 50%;
background-color: rgb(0,255,255);
box-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
}
.wheel-spinner {
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
width: 50%;
height: 50%;
border-radius: 50%;
border: 10px solid #333;
border-top-color: #f0f;
animation: spin 0.1s linear infinite;
}
@keyframes spin {
0% {
transform: translate(-50%, -50%) rotate(0deg);
}
100% {
transform: translate(-50%, -50%) rotate(360deg);
}
}
.search-container {
margin-top: 15px;
}
.search-input {
padding: 10px;
width: 300px;
border: 1px solid #ccc;
border-radius: 5px;
font-size: 16px;
}
.search-button {
padding: 10px 20px;
background-color: #4285f4;
color: #fff;

border: none;
border-radius: 5px;
font-size: 16px;
cursor: pointer;
}
</style>
<!--stylesheet ends-->
<script>
const adTexts = document.querySelectorAll('.ad-text');
let currentIndex = 0;
function showAdvert(index) {
adTexts.forEach((adText, i) => {
if (i === index) {
adText.classList.add('active');
} else {
adText.classList.remove('active');
}
});
}
function changeAdvert() {
    
showAdvert(currentIndex);
currentIndex = (currentIndex + 1) % adTexts.length;
}
setInterval(changeAdvert, 6000);
</script>
<script>
const flowers = document.querySelectorAll('.flower');
const balloons = document.querySelectorAll('.balloon');
flowers.forEach((flower, index) => {
flower.style.top = `${index * 50}px`;
flower.style.left = `${Math.random() * 200}px`;
});
balloons.forEach((balloon, index) => {
balloon.style.top = `${index * 50}px`;
balloon.style.left = `${Math.random() * 200}px`;
});
</script>
<script>
const menuToggle = document.querySelector('.menu-toggle');
const menuIcon = document.querySelector('.menu-icon');
const closeIcon = document.querySelector('.close-icon');
const menu = document.querySelector('.menu');
menuToggle.addEventListener('click', () => {
if (menu.style.display === 'block') {
menu.style.display = 'none';
closeIcon.style.display = 'none';

menuIcon.style.display = 'block';
} else {
menu.style.display = 'block';
closeIcon.style.display = 'block';
menuIcon.style.display = 'none';
}
});
</script>
<script>
function searchGoogle() {
var searchTerm = document.getElementById('searchInput').value;
if (searchTerm) {
var searchUrl = 'https://www.google.com/search?q=' +
encodeURIComponent(searchTerm);
window.open(searchUrl, '_blank');
} else {
alert('Please type in the item you are searching for');
}
}


</csript>


<script>
  let cart = [];

  function signup() {
    const username = document.getElementById('signupUsername').value.trim();
    const password = document.getElementById('signupPassword').value.trim();

    if (username === '' || password === '') {
      alert('Please enter username and password.');
      return;
    }

    let users = JSON.parse(localStorage.getItem('users')) || [];

    if (users.some(user => user.username === username)) {
      alert('Username already exists.');
      return;
    }

    users.push({ username, password });
    localStorage.setItem('users', JSON.stringify(users));

    alert('Signup successful!');
    showLogin();
  }

  function login() {
    const username = document.getElementById('loginUsername').value.trim();
    const password = document.getElementById('loginPassword').value.trim();

    if (username === '' || password === '') {
      alert('Please enter username and password.');
      return;
    }

    const users = JSON.parse(localStorage.getItem('users')) || [];
    const user = users.find(u => u.username === username && u.password === password);

    if (!user) {
      alert('Incorrect username or password.');
      return;
    }

    localStorage.setItem('currentUser', username);
    document.getElementById('userDisplay').innerText = username;
    showShop();
  }

  function togglePassword(fieldId, btn) {
    const passwordField = document.getElementById(fieldId);

    if (passwordField.type === 'password') {
      passwordField.type = 'text';
      btn.textContent = '🙈';
    } else {
      passwordField.type = 'password';
      btn.textContent = '👁️';
    }
  }

  function showSignup() {
    document.getElementById('signupPage').style.display = 'block';
    document.getElementById('loginPage').style.display = 'none';
    document.getElementById('shopPage').style.display = 'none';
  }

  function showLogin() {
    document.getElementById('signupPage').style.display = 'none';
    document.getElementById('loginPage').style.display = 'block';
    document.getElementById('shopPage').style.display = 'none';
  }

  function showShop() {
    document.getElementById('signupPage').style.display = 'none';
    document.getElementById('loginPage').style.display = 'none';
    document.getElementById('shopPage').style.display = 'block';
  }

  function addToCart(productName, price) {
    cart.push({ productName, price });
    updateCartDisplay();
  }

  function updateCartDisplay() {
    const cartList = document.getElementById('cartList');
    cartList.innerHTML = '';
    cart.forEach((item) => {
      const li = document.createElement('li');
      li.className = 'list-group-item';
      li.textContent = `${item.productName} -k${item.price}`;
      cartList.appendChild(li);
    });
  }
  
li.textContent = `${item.productName} - K${item.price.replace('$', 'k')}`;

  function placeOrder(
