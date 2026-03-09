# Product Card Design with Hover Effect using CSS
## Date:09.03.2026

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
~~~
product.html

<html>
    <head>
        <title>Product Card</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="card">
            <img src="andras-vas-Bd7gNnWJBkU-unsplash.jpg" class="product-img">
            <h2>Laptop</h2>
            <p class="para">Processor

14th Generation Intel® Core™ i7-14700HX Processor (E-cores up to 3.90 GHz P-cores up to 5.50 GHz)
Operating System

Windows 11 Home Single Language 64
Graphic Card

NVIDIA® GeForce RTX™ 5050 Laptop GPU 8GB GDDR7
Memory

16 GB DDR5-5600MT/s (SODIMM)
Storage

1 TB SSD M.2 2242 PCIe Gen4 QLC
Display

39.62cms (15.6) FHD (1920 x 1080), IPS, Anti-Glare, Non-Touch, 100%sRGB, 300 nits, 144 Hz
AC Adapter / Power Supply
245W
Pointing Device
ClickPad
Keyboard
24zone RGB Backlit, Eclipse Black - English (US)
WIFI
Wi-Fi 6 2x2 AX & Bluetooth® 5.3
Warranty
1 Year On-site
Color
Luna Grey
Brand
Lenovo LOQ
Screen Resolution
1920 x 1080</p>
              <h3 class="price">Rs.150000</h3>
            <button class="submit">Add to cart</button>
        </div>
        <footer>
            <p>SATHIYA PRIYAN G(25018768)</p>
        </footer>
    </body>
</html>

style.css

body
{
    background:greenyellow;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
}
.card
{
    width:400px;
    background-color:gold;
    text-align:center;
    padding:20px;
    box-shadow:0 5px 15px white(49, 12, 13);
    transition:0.3s;
}
.product-img
{
    width: 300px;
    height: 350x;
    border-radius:10px;
}
.card h2
{
    color:violet(4, 4, 100);
}
.para
{
    color:orangered;
}
.price
{
    color:orchid;
}
.card:hover
{
    transform:scale(1.1);
    box-shadow:0 15px 25px cornflowerblue;
}

.card:hover .product-img
{
    transform:scale(1.1);
}

.card:hover .submit
{
    background:chartreuse;
}

footer
{
    width:100%;
    text-align:center;
    background:coral;
    color:lawngreen;
    padding:10px;
    margin-top:30px;
}
~~~
## OUTPUT:
![alt text](<Screenshot (27).png>)
## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
