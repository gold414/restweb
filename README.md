# Ex.07 Restaurant Website
## Date:05.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
<head>
    <title>My Restaurant</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <div class="head">
        <h1>WHITE TIGRIS INDIAN RESTAURANT</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="menu.html"> MENU|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <hr>
    <div class="center">
        <P class="type">RICH-EXQUISITE-DELIGHTFUL</P>
        <h1 class="quote">&QUOT;A taste of Indian tradion in every bite - Taste the tradion<br>of tamil culture.&QUOT;</h1>
        <p>You're invited to white tigris join us for unexpectable flavours,warm vibes, and a side of fortune. 
           From crispy spring rolls to sizzling stir-fries, Whhite Tigris Indian Restaurant serves up This
           kind of delious that makes hand optional(but recomanded)</p>
    </div>
    <div class="bottom">
        <img src="under.webp" alt="interior" width="400" height="200">
    </div><hr>
    <h3 class="foot">&copy;Thangapazham(25017581)</h3>
</body>
</html>

home.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background-image: url(restbg.jpg);
    height: 100%;
    width: 100%;
    background-size: cover;
    background-position: center;
}
.head,.list,ul,li{
    display: inline-block;
}
ul{
    margin-left: 80%;
    display: flex;
}
li{
    background-color: pink;
}
li:hover{
    background-color: grey;
    border-radius: 0px;
}
h1{
    color:red;
    margin: 20px;
}
.type{
    margin-right: 70%;
}
p{
    color: white;
    font-size: 20px;
    margin: 20px;
    text-align: center;
}
.quote{
    text-align: center;
}
.bottom{
    margin-left: 30%;
}
.foot{
    text-align: center;
    color: white;
}

menu.html

<html >
<head>
    <title>Menu Page</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <div class="head">
    <h1>Our Menu</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="menu.html"> MENU|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
        <h2>Foood Items</h2>
        <div class="food-item">
            <div class="food">
                <img src="idly.jpg" alt="Idly" width="200" height="150">
                <h3>Kovil Idly</h3>
            </div>
            <div class="food">
                <img src="dosa.webp" alt="Dosa" width="200" height="150">
                <h3>Kari Dosa</h3>
            </div>
            <div class="food">
                <img src="pongal.jpg" alt="Pongal" width="200" height="150">
                <h3>Ven Pongal</h3>
            </div>
            <div class="food">
                <img src="sambar vada.jpg" alt="Sambar Vada" width="200" height="150">
                <h3>Sambar Vada</h3>
            </div>
            <div class="food">
                <img src="eral thokku.jpg" alt="Eral Thokku" width="200" height="150">
                <h3>Eral Thokku</h3>
            </div>
            <div class="food">
                <img src="full meel.webp" alt="Full Meel" width="200" height="150">
                <h3>Full Meel</h3>
            </div>
            <div class="food">
                <img src="paniyaram.jpg" alt="Panniyaram" width="200" height="150">
                <h3>paniyaram</h3>
            </div>
            <div class="food">
                <img src="pongal sugar.jpg" alt="Sugar Pongal" width="200" height="150">
                <h3>Sugar Pongal</h3>
            </div>
            <div class="food">
                <img src="poori.jpg" alt="Poori" width="200" height="150">
                <h3>Poori</h3>
            </div>
            <div class="food">
                <img src="puliyadharai.webp" alt="Puliyadharai" width="200" height="150">
                <h3>Puliyadharai</h3>
            </div>
            <div class="food">
                <img src="snacks.png" alt="Comba Pack" width="200" height="150">
                <h3>Combo Pack</h3>
            </div>
            <div class="food">
                <img src="chilly parotta.webp" alt="Chilli Parotta" width="200" height="150">
                <h3>Chilli Parotta</h3>
            </div>
    </div>
    <h3 class="foot">&copy;Thangapazham(25017581)</h3>
</body>

menu.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-image: url(bg.webp);
    background-size: cover;
    background-attachment: fixed;
    text-align: center;
    line-height: 1.6;
}
h2{
    color: lime;
}
h3{
    color: limegreen;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
h1{
    color: red;
    background-color: yellow;
}

.food{
    border: 2px solid pink;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: darkgreen;
    display: inline-block;
}
.food:hover{
    background-color: lightgreen;
    transform: scale(1.1);
    transition: 0.3s;
}
.food-item h3{
    color: white;
}

admin.html

<html >
<head>
    <title>Admin page</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="head">
    <h1>Administration Team</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="menu.html"> MENU|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <h2>Meet our Team</h2>
    <div class="team">
        <div class="member">
            <img src="admin2.jpg" alt="Admin 1" width="200" height="200">
            <h3>Thalapathy</h3>
            <p>CEO</p>
        </div>
        <div class="member">
            <img src="admin1.jpg" alt="Admin 2" width="200" height="200">
            <h3>Bill Gates</h3>
            <p>Marketing Manager</p>
        </div>
        <div class="member">
            <img src="admin4.jpg" alt="Admin 3" width="200" height="200">
            <h3>Jack Sparrow</h3>
            <p>Operation manager</p>
        </div>
        <div class="member">
            <img src="profile.jpeg" alt="Admin 4" width="200" height="200">
            <h3>Thangapazham</h3>
            <p>HR manager</p>
        </div>
        <div class="member">
            <img src="admin5.jpg" alt="Admin 5" width="200" height="200">
            <h3>Steffi</h3>
            <p>Head Chef</p>
        </div>
        <div class="member">
            <img src="admin3.jpg" alt="Admin 6" width="200" height="200">
            <h3>Gojo Sataru</h3>
            <p>Customer Service Manager</p>
        </div>
    </div>
    <hr>
    <h3 class="foot">&copy;Thangapazham(25017581)</h3>
</body>
</html>

admin.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: yellow;
    color: red;
    line-height: 1.6;
    text-align: center;
}
.member{
    border: 2px solid pink;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: orange;
    display: inline-block;
}
.member:hover{
    background-color: lightblue;
    color: black;
    transform: scale(1.1);
    transition: 0.3s;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
.team{
    background-color: orangered;
}

contact.html

<html >
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="head">
    <h1>Contact Info</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="menu.html"> MENU|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <div class="content">
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to make a reservation,<br>please contact us using the information below:<br>
           Phone: (123) 456-7890<br>Email: royalindian@mail.com<br>
           Visit us at: 123 Main Street, TamilNadu, India<br></p>
    </div>
    <h3 class="foot">&copy;Thangapazham(25017581)</h3>
</body>

contact.css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body{
    background-image: url(contact.jpg);
    background-size: cover;
    background-position: center;
    text-align: center;
}
h1{
    text-align: center;
    padding: 20px;
    color: white;
    font-size: 40px;
}
h3{
    color: lime;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
.content{
    border: 2px solid pink;
    color: white;
    font-size: 20px;
    margin: 20px;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.788);
    border-radius: 10px;
}

```

## OUTPUT:
![alt text](<Screenshot (108).png>)
![alt text](<Screenshot (109).png>)
![alt text](<Screenshot (111).png>)
![alt text](<Screenshot (112).png>)
![alt text](<Screenshot (114).png>)
![alt text](<Screenshot (115).png>)
![alt text](<Screenshot (116).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
