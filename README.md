# Ex.07 Software Product Company Website
## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
```html
<!DOCTYPE html>
<html>
<head>
  <title>Software Product Development Company</title>
  <style>
    /* Global Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Header Styles */
    header {
      background-color: #345995;
      color: #fff;
      padding: 40px;
      text-align: center;
    }

    h1 {
      font-size: 48px;
      margin: 0;
      font-family: 'Open Sans', Arial, sans-serif;
    }

    /* Main Content Styles */
    main {
      padding: 40px;
    }

    h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #345995;
      font-family: 'Raleway', Arial, sans-serif;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 20px;
      margin-bottom: 40px;
    }

    .product {
      border: 1px solid #ccc;
      padding: 20px;
      text-align: center;
      background-color: #f7f7f7;
    }

    .product img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
    }

    .product h3 {
      font-size: 24px;
      margin: 0;
      color: #333;
      font-family: 'Raleway', Arial, sans-serif;
    }

    .product p {
      color: #666;
      font-family: 'Open Sans', Arial, sans-serif;
    }

    .people {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .person {
      width: 250px;
      margin: 20px;
      text-align: center;
    }

    .person img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    .person h3 {
      font-size: 24px;
      margin: 0;
      color: #333;
      font-family: 'Raleway', Arial, sans-serif;
    }

    .person p {
      color: #666;
      font-family: 'Open Sans', Arial, sans-serif;
    }

    .contact-info {
      text-align: center;
      margin-bottom: 40px;
    }

    .contact-info p {
      color: #666;
      font-family: 'Open Sans', Arial, sans-serif;
    }

    /* Footer Styles */
    footer {
      background-color: #345995;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to HackMaster Innovations </h1>
  </header>

  <main>
    <h2>Products Available</h2>

    
      <div class="Products Available">
        <img src="/static/images/omgcable.jpg" alt="Product 1">
        <h3>THE O.MG ELITE CABLE</h3>
        <a href="https://shop.hak5.org/products/omg-cable">https://shop.hak5.org/products/omg-cable</a>
        <p>Is that phone charger doing more than you think it is?</p>

       
        
            
      </div>

      
      <div class="Products Available">
        <img src="/static/images/flipper.jpg" alt="Product 2">
        <h3>THE FLIPPER ZERO IS A SWISS ARMY KNIFE </h3>
        <a href="https://www.etsy.com/in-en/market/flipper_zero_device">https://www.etsy.com/in-en/market/flipper_zero_device</a>
        <p>An all-purpose tool for making wireless mischief</p>
        
      </div>

      <div class="Products Available">
        <img src="/static/images/huntercat.jpg" alt="Product 2">
        <h3>THE HUNTER CAT IS THE BODYGUARD FOR YOUR CREDIT CARD</h3>
        <a href="https://hackerwarehouse.com/product/hunter-cat/">https://hackerwarehouse.com/product/hunter-cat/</a>
        <p>A single-purpose gadget to find out if a credit card reader is stealing your data</p>
        
      </div>

      

      

    </div>

   
    <h2>THE JAYA GROUPS OF COMPANY </h2>
     <h2>People behind the company</h2>


    <div class="peoples">
      <div class="person">
          <div class="mypic"></div>
        <img src="/static/images/beach.jpg" alt="Person 1">
        <h3>Jayavarthan</h3>
        <p>CEO</p>
      </div>

    <div class="peoples">
      <div class="person people behind the company">
          <div class="mypic"></div>
        <img src="/static/images/krish.jpg" alt="Person 2">
        <h3>Jayakrishnan</h3>
        <p>ETHICAL HACKER</p>
      </div>

      <div class="peoples">
      <div class="person people behind the company">
          <div class="mypic"></div>
        <img src="/static/images/mani.jpg" alt="Person 2">
        <h3>Jayamani</h3>
        <p>SOFTWARE DEVELOPER</p>
      </div>

    
      
    </div>

    <h2>Contact Us</h2>

    <div class="contact-info">
      <p>5/13 KRISHNAN KOVIL 1ST Street, THANJAVUR-613001,TAMILNADU,INDIA</p>
      <p>Phone:9344524024</p>
      <p>Email: jayavarthanp@gmail.com</p>
    </div>
  </main>

  <footer>
    <p>Designed and developed by JAYAVARTHAN P</p>
  </footer>
</body>
</html>

```

## OUTPUT:
![Screenshot (15)](https://github.com/Jayamani25/softweb/assets/85949888/aa55a122-ab2d-4df1-bb9d-9fbff1c38063)
![Screenshot (17)](https://github.com/Jayamani25/softweb/assets/85949888/5310a53b-4160-4bbd-87f1-707c2775a7ef)
![Screenshot (18)](https://github.com/Jayamani25/softweb/assets/85949888/cb558ef2-ad84-43c7-8ed1-be255c5adbf6)
![Screenshot (20)](https://github.com/Jayamani25/softweb/assets/85949888/52c4c9f5-3d6c-4a97-9c7b-95fda65d1527)

## HTML VALIDATOR:
![Screenshot (14)](https://github.com/Jayamani25/softweb/assets/85949888/83468ee5-50f4-4cf8-ada8-b1a54ec4da35)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
