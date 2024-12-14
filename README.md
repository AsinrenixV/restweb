# Ex.07 Restaurant Website
## Date:14-12-2024

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
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Welcome to Rovarsinn restaurant</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            margin: 0;
            padding: 0;
            background-color:aliceblue;
			;

        }
        header {
            background-image:url('rest.png');
		    font-style:italic;
			color:beige;
            text-align: center;
            padding: 200px 0px;
			background-repeat: no-repeat;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #130505;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #a9a5ab;
        }
        .section {
            padding: 20px;
            text-align: center;
        }
		.designer {
			position: absolute;
			bottom:40px;
			right:35px;
			width:80px;

		}
        
		.administration.item {
			display: inline-block;
            width: 10%;
            padding: 10px;
            margin: 10px;
            background-color: antiquewhite;
            border-radius: 3px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		.administration.item img {
			width: 50%;
            border-radius: 3px;
		}
		.menu-item {
            display: inline-block;
            width: 30%;
            padding: 10px;
            margin: 10px;
            background-color: antiquewhite;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
	
        }
        .menu-item img {
            width: 100%;
            border-radius: 8px;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .reservation-form input, .reservation-form textarea {
            width: 80%;
            padding: 10px;
            margin: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        .reservation-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .reservation-form button:hover {
            background-color: #d72b2b;
        }
		
    </style>
</head>
<body>

    <header>
        <h1>Rovarsinn Restaurant</h1>
        <p>Where every meal is a delight!</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
		<a href="#administration">Administration</a>
		<a href="#reservation">reservation</a>
	
    </nav>
	

    <section id="home" class="section">
        <h2>WELCOME TO ROVARSINN RESTAURANT!!!</h2>
        <p>Discover the finest dining experience with exquisite flavors,exceptional service,and a warm atmosphere that will leave you wanting more</p>
    </section>

    <section id="menu" class="section">
        <h2>Our Delicious Food Menu</h2>
        <div class="menu-item">
            <img src="cheeseburger.jpeg" alt="Dish 1">
            <h1>Cheese Burger</h1>
            <p>Melted cheese and caramelized onions on a toasted bun..</p>
            <p>$15.99</p>
        </div>
		<div class="menu-item">
			<img src="butterchickenrice.jpeg" alt="Dish 2">
			<h2>Butter Chicken Rice</h2>
			<p>Treat yourself to a fragrant and irresistible Butter Chicken Rice experience,discover the ultimate comfort food with our creamy and savory Butter Chicken Rice...</p>
			<p>$16</p>
		</div>
		<div class="menu-item">
			<img src="italianpasta.jpeg" alt="Dish 3">
			<h3>Italian Pasta</h3>
			<p>Try it which was topped with spicy and hot spices that gives you crunchy taste...</p>
			<p>$32</p>
		</div>
		<div class="menu-item">
			<img src="pastasweetycherry.jpeg" alt="Dish 4">
			<h4>Pasta Sweety Cherry</h4>
			<p>Explore the Delicious Sweety pasta dish that gives you such a sweet taste....take it eat it..</p>
			<p>$22</p>
		</div>
		<div class="menu-item">
			<img src="applejuice.jpeg" alt="Dish 5">
			<h5>Apple Juice</h5>
			<p>FFresh juice made from fresh apples...</p>
			<p>$13</p>
		</div>
		<div class="menu-item">
            <img src="spicychicken.jpg" alt="Dish 6">
            <h6>Spicy Chicken</h6>
            <p>Feel the heat with our blazing hot chicken scorching hot and full of flavor fiery spices and savory flavors come together in our spicy chicken...</p>
            <p>$20.99</p>
        </div>
        <div class="menu-item">
            <img src="nuggets.jpg" alt="Dish 7">
            <h1>Nuggets</h1>
            <p>Tender and flavorful nuggets, cooked to perfection spicy and savory nuggets that will leave you wanting more golden and crunchy nuggets, perfect for snacking...</p>
            <p>$12.99</p>
        </div>
		<div class="menu-item">
			<img src="cocktails.jpeg" alt="Dish 8">
			<h2>Cocktails</h2>
			<p>Treat yourself to a sophisticated and elegant cocktail experience..</p>
			<p>$19</p>
		</div>
		<div class="menu-item">
			<img src="lugerburger.jpeg" alt="Dish 9">
			<h3>Luger Burger</h3>
			<p>Treat yourself to a decadent and satisfying Luger Burger experience discover the ultimate comfort food with our hearty Luger Burger...</p>
			<p>$12</p>
		</div>
		<div class="menu-item">
			<img src="mochafrosting.jpeg" alt="Dish 10">
			<h4>Mocha Frosting</h4>
			<p>Decadent and creamy, our mocha frosting is the perfect treat experience the velvety smoothness of our mocha frosting...</p>
			<p>$13</p>
		</div>
		<div class="menu-item">
			<img src="dosa.jpeg" alt="Dish 11">
			<h5>Dosa</h5>
			<p>Don't forget to taste the crunchy dosa with such spicy chatniii...</p>
			<p>$10</p>
		</div>
		<div class="menu-item">
			<img src="lazyburgerpizza.jpeg" alt="Dish 12">
			<h6>Lazy burger pizza</h6>
			<p>Get ready for a flavor explosion with our hot and melty Lazy Baker Pizza..</p>
			<p>$13</p>
		</div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Rovarsinn restaurant is an establishment that prepares and serves food and drinks to customers.Meals are generally served and eaten on the premises, but many restaurants also offer take-out and food delivery services. Restaurants vary greatly in appearance and offerings, including a wide variety of cuisines and service models ranging from inexpensive fast-food restaurants and cafeterias to mid-priced family restaurants, to high-priced luxury establishments.</p>

    <section id="contact" class="section">
        <h2>Contact us for Delicious food</h2>
        <p>Email: Rovarsinnrest@gmail.com</p>
        <p>Phone: 7390034679</p>
        <p>Address: NEW YORK CITY</p>
		
    </section>
	<section id="administration" class="section">
		<h2>Administration</h2>
		<div class="administration-item">
			<img src="chef01.jpeg" alt="best chef1">
			<h1>CHEF.RAMAN</h1>
		</div>
		<div class="administration-item">
			<img src="chef02.jpeg" alt="best chef2">
			<h2>CHEF.HARINI</h2>
		</div>
		<div class="administration-item">
			<img src="chef03.jpeg" alt="best chef3">
			<h3>CHEF.VARSHINI</h3>
		</div>
	</section>
	<section id="reservation" class="section reservation-form">
        <h2>Make your Order</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required><br>
            <input type="email" name="email" placeholder="Your Email" required><br>
            <input type="number" name="phone" placeholder="Your Phone Number" required><br>
            <textarea name="message" placeholder="Special Requests" rows="4"></textarea><br>
            <button type="submit">Order Now</button>
        </form>
    </section>
</body>
</html>
```

## OUTPUT:
![alt text](<renix/restapp/static/Screenshot (67).png>)
![alt text](<renix/restapp/static/Screenshot (55).png>)
![alt text](<renix/restapp/static/Screenshot (56).png>)
![alt text](<renix/restapp/static/Screenshot (57).png>)
![alt text](<renix/restapp/static/Screenshot (58).png>)
![alt text](<renix/restapp/static/Screenshot (59).png>)
![alt text](<renix/restapp/static/Screenshot (60).png>)
![alt text](<renix/restapp/static/Screenshot (61).png>)
![alt text](<renix/restapp/static/Screenshot (62).png>)
![alt text](<renix/restapp/static/Screenshot (63).png>)
![alt text](<renix/restapp/static/Screenshot (64).png>)
![alt text](<renix/restapp/static/Screenshot (65).png>)
![alt text](<renix/restapp/static/Screenshot (66).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
