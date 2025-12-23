# Ex.06 Restaurant Website
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CAFE QUINNN</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#f8f4ef;       
      color:#3b2f2f;            
    }

    header{
      background:#caa19d;      
      padding:20px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    header h1{
      letter-spacing:2px;
    }

    nav a{
      color:#f5e6d3;
      text-decoration:none;
      margin:0 12px;
      font-weight:bold;
    }

    nav a:hover{
      color:#d9a066;           
    }

    .hero{
      height:70vh;
      background:url('PIC8.jpg') center/cover no-repeat;
      display:flex;
      justify-content:center;
      align-items:center;
    }

    .hero h2{
      background:rgba(75,46,43,0.85);
      color:white;
      padding:18px 30px;
      border-radius:8px;
      font-size:28px;
    }

    section{
      padding:55px 40px;
    }

    h2{
      text-align:center;
      margin-bottom:30px;
      color:#4b2e2b;
      font-size:32px;
    }

    
    .about{
      display:flex;
      gap:30px;
      align-items:center;
      justify-content:center;
    }

    .about p{
      max-width:500px;
      font-size:30px;
      line-height:1.6;
    }

    .about img{
      width:100%;
      max-width:420px;
      border-radius:12px;
    }

    
    .menu{
      display:flex;
      gap:25px;
      flex-wrap:wrap;
      justify-content:center;
    }

    .menu-card{
      background:#fffaf5;
      width:260px;
      border-radius:12px;
      overflow:hidden;
      box-shadow:0 6px 15px rgba(0,0,0,0.12);
    }

    .menu-card img{
      width:100%;
      height:180px;
      object-fit:cover;
    }

    .menu-card div{
      padding:15px;
      text-align:center;
    }

    .menu-card h3{
      color:#4b2e2b;
      margin-bottom:8px;
    }

    .menu-card p{
      color:#a47148;
      font-weight:bold;
      font-size:18px;
    }

    
    .gallery{
      display:flex;
      gap:20px;
      flex-wrap:wrap;
      justify-content:center;
    }

    .gallery img{
      width:260px;
      border-radius:10px;
      box-shadow:0 5px 12px rgba(0,0,0,0.15);
    }

   
    .contact{
      background:#4b2e2b;
      color:#f5e6d3;
      text-align:center;
      padding:50px 20px;
    }

    .contact p{
      margin:8px 0;
      font-size:16px;
    }

    footer{
      background:#2e1c1a;
      color:#d2b48c;
      text-align:center;
      padding:12px;
    }

    
    @media(max-width:768px){
      .about{
        flex-direction:column;
        text-align:center;
      }

      header{
        flex-direction:column;
        gap:10px;
      }

      .hero h2{
        font-size:22px;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>THE COFFEE SPOT</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero" id="home">
  <h2>Brewed fresh • Served with love</h2>
</div>

<section id="about">
  <h2>About Us</h2>
  <div class="about">
    <p>
      Experience rich flavors, perfect aromas, and carefully crafted coffee.
      The Coffee Spot is your everyday escape for comfort, calm, and great taste.
    </p>
    <img src="abt_us.jpg">
  </div>
</section>

<section id="menu">
  <h2>Our Menu</h2>
  <div class="menu">

    <div class="menu-card">
      <img src="cuppacino.jpg">
      <div>
        <h3>Classic Cappuccino</h3>
        <p>₹280</p>
      </div>
    </div>

    <div class="menu-card">
      <img src="coffee3.jpg">
      <div>
        <h3>Cold Coffee</h3>
        <p>₹180</p>
      </div>
    </div>

    <div class="menu-card">
      <img src="hotchoco.jpg">
      <div>
        <h3>Signature Hot Chocolate</h3>
        <p>₹320</p>
      </div>
    </div>

  </div>
</section>

<section id="gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="PIC5.jpg">
    <img src="PIC6.jpg">
    <img src="PIC7.jpg">
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>📍 Chennai, India</p>
  <p>📞 +91 9840311956</p>
  <p>✉ cafequinnn@email.com</p>
  <p>Rubika M</p>
  <p>25008774</p>
</section>

<footer>
  <p>© 2025 CAFE QUINNN</p>
</footer>

</body>
</html>
```

## OUTPUT:
![p1](https://github.com/user-attachments/assets/8e108eda-e28d-4727-b579-c44aff37081f)

![p2](https://github.com/user-attachments/assets/2afc2623-0740-4e0f-81a2-42d9338ab6e6)

![p3](https://github.com/user-attachments/assets/d5893773-9dba-44e2-ace2-b4324f55fed0)


![p4](https://github.com/user-attachments/assets/c5b5c56c-6c4a-4327-be76-29eb128dc4dc)

![p5](https://github.com/user-attachments/assets/d6c8376f-a280-41f3-8591-3ca4fc796921)

## RESULT:

The program for designing software company website using HTML and CSS is completed successfully.
