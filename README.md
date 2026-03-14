# Ex.06 Restaurant Website
## Date:14.03.2026

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
Publish the website in Localhost.

## PROGRAM:
```
Home.html
<html>
<head>
     <title>Home</title>
     <link rel="stylesheet" href="style.css">
</head>
<body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">Naidu Restaurant</h1>
        <h2 class="subtitle">Taste of indian spicy</h2>
        <p style="margin-left:80px;">
            Indian food is characterized by a complex, aromatic,and layered blend of spices, ranging from mild and creamy to fiery hot.
        </p>
        <div class="image-container">
            <img src="hotel1.jpg">
            <img src="hotel2.jpg">
            <img src="hotel3.jpg">
        </div>
        <footer>Ramesh Jaisurya | x | 25005800 </footer>
</body>
</html>


Admin.html
<html>
<head>
        <title>Admin</title>
        <link rel="stylesheet" href="style.css">
</head>
<body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">ADMINISTRATION TEAM</h1>
        <div class="team-container">
            <div class="team-card">
                <img src="surya.jpeg">
                <h3>Jaisurya</h3>
                <p>General Manager</p>
            </div>
            <div class="team-card">
                <img src="dwijesh.jpeg">
                <h3>Dwijesh</h3>
                <p>Marketing Manager</p>

            </div>

            <div class="team-card">
                <img src="shawn.jpeg">
                <h3>Shawn</h3>
                <p>chef</p>
            </div>

            <div class="team-card">
                <img src="Iniyaa.jpeg">
                <h3>Iniya</h3>
                <p>assistant Chef</p>
            </div>
            <div class="team-card">
                <img src="jeeva.jpeg">
                <h3>Jeeva</h3>
                <p> customer service manager</p>
            </div>
        </div>
        <footer>Ramesh Jaisurya | x | 25005800</footer>
</body>
</html>

Contact.html

<html>
<head>
      <title>Contact</title>
      <link rel="stylesheet" href="style.css">
</head>
<body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">CONTACT</h1>
        <div class="contact-box">
            <h2>Visit us At:</h2>
            <p>
                Naidu Restaurant
                <br>
                bengaluru brodway
                <br>
                church Street,pin-code:560001
                <br>
                India
            </p>
            <br>
            <h2>Phone:</h2>
            <p>+91 9966789177</p>
            <br>
            <h2>Email ID:</h2>
            <p>Jaisurya3308@gmail.com</p>
        </div>
        <footer>Ramesh Jaisurya | x | 25005800</footer>
</body>
</html>

style.css


body{
    background-image:url(https://png.pngtree.com/thumb_back/fh260/background/20240425/pngtree-top-desk-with-blur-restaurant-background-wooden-table-image_15665383.jpg);
    background-size:cover;
    background-position:center;
    color:rgb(255, 103, 2);
    padding:fixed;
    margin:0;
    bottom:0;
    box-sizing:border-box;
    font-family:Arial;
}

nav{
    position:absolute;
    top:20px;
    right:80px;
    background:linear-gradient(45deg,rgb(184, 6, 6),black,rgba(255, 64, 0, 0.945));
    padding:12px 40px;
}

nav b{
    margin:0 20px;
    text-decoration:none;
    color:rgb(178, 74, 74);
    font-weight:bold;
}

.main-title{
    font-size:90px;
    color:rgb(156, 26, 24);
    margin-left:80px;
    margin-top:120px;
}

.subtitle{
    font-size:30px;
    margin-left:80px;
}

.image-container{
    display:flex;
    justify-content:center;
    gap:80px;
    margin-top:40px;
}

.image-container img{
    width: 500px;
    border: radius 25px;
}

.menu-container{
    display:flex;
    justify-content:center;
    gap:25px;
    margin-top:400px;
}

.card{
     background:linear-gradient(45deg,rgb(184, 6, 6),black,rgba(255, 64, 0, 0.945));
    width: 180px;
    height: 260px;
    border-radius: 15px;
    overflow: hidden;  
    position: relative;
    padding:15px;
    text-align:center;
    color:white;
}

.card img{
    border-radius: 10px;
    width: 100%;
    height: 150px;
    object-fit: cover;
    display: block;
}

.card h3{
    margin-top:10px;
}

.card p{
    margin-top:5px;
}

.team-container{
    display:flex;
    justify-content:center;
    gap:30px;
    margin-top:350px;
}

.team-card{
    background:linear-gradient(45deg,rgb(184, 6, 6),black,rgba(255, 64, 0, 0.945));
    width:180px;
    padding:20px;
    border-radius:15px;
    text-align:center;
    color:rgb(10, 101, 174);
}

.team-card img{
    width:120px;
    height:120px;
    border-radius:40%;
}

.team-card h3{
    margin-top:10px;
}

.contact-box{
    margin-left:90px;
    margin-top:40px;
    line-height:35px;
    color: rgb(249, 164, 164);
    
}

footer{
    text-align:center;
    padding:10px;
    background:linear-gradient(90deg,rgb(184, 6, 6),black,rgba(255, 64, 0, 0.945));
    color:whitesmoke;
    position:fixed;
    bottom:0;
    width:100%;
}



```


## OUTPUT:
![alt text](<Screenshot (105).png>)
![alt text](<Screenshot (106).png>)
![alt text](<Screenshot (107).png>)
![alt text](<Screenshot (108).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
