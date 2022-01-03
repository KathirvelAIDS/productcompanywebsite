# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
home page
```

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Ktm Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Ktm Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/products.html">People</a></div>
        <div class="menuitem"><a href="/static/products.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            KTM bikes is the first name that comes to mind when it comes to off-road bikes.
            KTM AG, formerly known as KTM Sportmotorcycle AG, is renowned for manufacturing
            the enduro, motocross and supermoto bikes. KTM AG is an Austrian company
            manufacturing off-road bikes and sports cars. This company has an Indian 
            connection with Bajaj Auto having a substantial share in the ownership.
            These bikes are extremely popular among the younger generation as they
            classify as adventure bikes in many ways.
            <br />
            The illustrated vehicles may vary in selected details from the production
            models and some illustrations feature optional equipment available at
            additional cost. All information concerning the scope of supply, appearance,
            services, dimensions and weights is non-binding and specified with the 
            proviso that errors, for instance in printing, setting and/or typing, 
            may occur; such information is subject to change without notice. 
            Please note that model specifications may vary from country to country.
            In the case of coated surfaces, there may be color differences due to
            the usual process fluctuations. The consumption values stated refer 
            to the roadworthy series condition of the vehicles at the time of
            factory delivery.
            <ul>
              <li>Get Ready to Race.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ktm Private Limited, Developed by kathirvel.
      </div>
    </div>
  </body>
</html>
```
product page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Ktm Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Ktm Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_gold.png" alt="product image">
                </div>
                <div class="itemname">Tally Gold</div>
                <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>


          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ktm Private Limited, Developed by kathirvel.
      </div>
    </div>
  </body>
</html>
```                                
contact us page
```
<!DOCTYPE html>
<html lang="en">
<head>
<title></title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/ail.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="contactus">
<div class="homecontent">
<h1>Contact Us:</h1>
<h1>Address:<br>
<br> Cary,
<br>North Carolina,
<br>United States.</h1>
<div class="contenttext1">
</div><br>
<h1>Phone:
<div class="contenttext">

</div>
<h1>E-Mail:
<br> help@gamesover.com </h1><br>
<div class="contenttext">
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Game Over Private Limited, Developed by kathirvel.
</div>
</div>
</body>
</html>
```

## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
