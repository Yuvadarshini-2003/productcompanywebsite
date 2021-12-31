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

### Homepage

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Marvel Electronics</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/black.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Marvel Electronics</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/marvel.jpg" alt="Building" />
          <div class="contenttext">
            Marvel Electronics is committed to complying with local laws and regulations as well as applying a strict global code of conduct to all employees. It believes that ethical management is not only a tool for responding to the rapid changes in the global business environment, but also a vehicle for building trust with its various stakeholders including customers, shareholders, employees, business partners and local communities. With an aim to become one of the most ethical companies In the world, Marvel Electronics continues to train its employees and operate monitoring systems, while practicing fair and transparent corporate management.
            The real Avenger is here.
            <ul>
              <li>Best Quality</li>
              <li>Assured Guarantee and Warranty</li>
              <li>Plug into the dream of Electronics</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Marvel Electronics, Developed by Yuvadarshini.
      </div>
    </div>
  </body>
</html>
~~~


### People

~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Marvel Electronics</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/black.png" type="image/x-icon" />
    </head>
    <body>
        <div class="container">
            <div class="banner">Marvel Electronics</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitemselected"><a href='/static/people.html'>people</a></div>
                <div class="menuitem"><a href='/static/contact Us.html'>contact Us</a></div>
            </div>
            <div class="content">
                <div class="productcontent">
                    <h1>Our Crew Welcomes You All</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h1.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">Florence Pugh</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h2.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer</div>
                            <div class="itemprice">Rachel Weiss</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h3.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">William Hurt</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h4.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">Paul Rudd</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h5.jpg" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Kristen Steward</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="./img/h6.jpg" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">Josh Brolin</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 Marvel Electronics, Developed by Yuvadarshini. 
            </div>
        </div>
    </body>
</html>
~~~

### Products

~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Marvel Electronics</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/black.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Marvel Electronics.</div>
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
                  <img src="/static/img/P1.png" alt="product image">
                  </div>
                  <div class="itemname">Captain America Earbuds</div>
                  <div class="itemprice">Price: Rs.1500</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/P2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Black Widow Smart Watch</div>
                  <div class="itemprice">Price: Rs.3000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P3.jpg"  alt="product image">
                </div>
                <div class="itemname">Iron Man Earbuds</div>
                <div class="itemprice">Price: Rs.1600 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P4.jpg"  alt="product image">
                </div>
                <div class="itemname">Black Panther Earbuds</div>
                <div class="itemprice">Price: Rs.1450</div>
              </div><div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P5.jpg"  alt="product image">
                </div>
                <div class="itemname">Black Panther Headphones</div>
                <div class="itemprice">Price: Rs.2500</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P6.jpg"  alt="product image">
                </div>
                <div class="itemname">Deadpool Earphones</div>
                <div class="itemprice">Price: Rs.999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P7.jpg"  alt="product image">
                </div>
                <div class="itemname">Avengers Earphones</div>
                <div class="itemprice">Price: Rs.999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P8.jpg"  alt="product image">
                </div>
                <div class="itemname">Black Panther Wireless Speaker</div>
                <div class="itemprice">Price: Rs.3500 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P9.jpg"  alt="product image">
                </div>
                <div class="itemname">Iron man Wireless Speaker</div>
                <div class="itemprice">Price: Rs.2999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P10.jpg"  alt="product image">
                </div>
                <div class="itemname">Avengers Wall Charger</div>
                <div class="itemprice">Price: Rs.1399 </div>
              </div> 
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P11.jpg"  alt="product image">
                </div>
                <div class="itemname">Iron man Wireless Charger</div>
                <div class="itemprice">Price: Rs.899 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P12.jpg"  alt="product image">
                </div>
                <div class="itemname">Black Panther Watch</div>
                <div class="itemprice">Price: Rs.1899 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Marvel Electronics, Developed by Yuvadarshini.
      </div>
    </div>
  </body>
</html>
~~~

### Contact

~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Marvel Electronics</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/black.png" type="image/x-icon" />
    </head>

    <body>
        <div class="container">
            <div class="banner">Marvel Electronics</div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitem"><a href='/static/people.html'>people</a></div>
                <div class="menuitemselected"><a href='/static/contact Us.html'>contact Us</a></div>
            </div>
            <div class="content">
                <div class="Peoplecontent">
                    <h1>FEEL FREE TO CONTACT US</h1> 
                    <div class="Peopleitems">
                        <h2>For Enquiry</h2>
                        <h3>EMAIL : marvelelectronics08@gmail.com</h3>
                        <h3>NUMBER: +91 8778935693</h3>
                        <h3>ADDRESS: Shop No. 35,Richie Street,Broadway,Chennai-600001.</h3>
                    </div>
                </div>
            </div>
            <div class="footer">
            Copyright &#169; 2021 Marvel Electronics, Developed by Yuvadarshini.
            </div>
        </div>
    </body>
</html>
~~~
### Outpput:

![output](./images/contacts.jpg)
![output](./images/heads.jpg)
![output](./images/homee.jpg)
![output](./images/prod.jpg)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
