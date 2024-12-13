# Ex.07 Restaurant Website
# Date: 8/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <title>Tempting kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d80e0e;
        }

        header {
            background-color: #5f0808;
            color: rgb(182, 217, 41);
            padding: 15px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #051345;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: rgb(208, 232, 26);
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav ul li a:hover {
            background-color: #e31212;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #434040;
            color: white;
            text-align: center;
            padding:1px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            color: #e1d7d7;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .menu-item {
            background-color: #e70f0f;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 10px rgba(6, 3, 3, 0.1);
        }

        .menu-item h3,h4{
            margin: 0 0 10px 0;
        }

        .menu-item p {
            color: #080808;
        }
    </style>
</head>
<body>

<header>
    <h1>TEMPTING KITCHEN</h1>
    <p>SATISFY YOUR SENSES</p>
    <img src="c:\Users\monis\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\7BFA32686D200C64CB46DE03AC2EAC0D\WhatsApp Image 2024-12-07 at 10.20.36_df746a11.jpg"width="15%">
 </header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#administration">Administration</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home">
    <h2>Welcome to TEMPTING KITCHEN</h2>
    <p>Where every bite is a celebration of flavor! Our menu is a culinary adventure, crafted with fresh, locally sourced ingredients that tantalize your taste buds. Whether you're here for a cozy dinner or a special celebration, our warm atmosphere and dedicated staff ensure a memorable dining experience. Indulge in our signature dishes and discover why we’re a beloved destination for food lovers. Come savor the magic at Tempting Kitchen!</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <h3>Parotta</h3>
            <img src="c:\Users\monis\Downloads\pexels-prabal-9609857.jpg"width="100%">
            <p><strong>RS.30</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken biriyani</h3>
            <img src="c:\Users\monis\Downloads\pexels-mumtahina-tanni-1080117-6260921.jpg"width="100%">
            <p><strong>RS.200</strong></p>
        
    </div>
        <div class="menu-item">
            <h3>Chicken full grill</h3>
            <img src="c:\Users\monis\Downloads\pexels-mouktik-joshi-98936055-9646843.jpg"width="50%">
            <p><strong>RS.300</strong></p>
        </div>
        <div class="menu-item">
            <h3>Hot chicken gravy</h3>
            <img src="c:\Users\monis\Downloads\pexels-sahersuthriwala-6599106.jpg"width="100%">
            <p><strong>RS.190</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken fried rice</h3>
            <img src="c:\Users\monis\Downloads\pexels-nadim-shaikh-2923533-7758253.jpg"width="100%">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken noodles</h3>
            <img src="c:\Users\monis\Downloads\Sichuan-Chilli-Chicken-Noodles-04.jpg"width="80%">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Malai chicken</h3>
            <img src="c:\Users\monis\Downloads\pexels-harry-dona-2338407.jpg"width="100%">
            <p><strong>RS.250</strong></p>
        </div>
        <div class="menu-item">
            <h3>Fried Chicken</h3>
            <img src="c:\Users\monis\Downloads\Instant-Pot-Fried-Chicken.jpg"width="100%">
            <p><strong>RS.210</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken burger</h3>
            <img src="c:\Users\monis\Downloads\pexels-k-patel-1100389468-20722066.jpg"width="80%">
            <p><strong>RS.210</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken shawerma</h3>
            <img src="c:\Users\monis\Downloads\pexels-rajdeepcraft-17119248-6416559.jpg"width="80%">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Mint mojito</h3>
            <img src="c:\Users\monis\Downloads\pexels-anilsharma65-10927828.jpg"width="100%">
            <p><strong>RS.160</strong></p>
        </div>
        <div class="menu-item">
            <h3>Black current Ice Cream</h3>
            <img src="c:\Users\monis\Downloads\pexels-alisha-mishra-579430-1343504.jpg"width="100%">
            <p><strong>RS.150</strong></p>
        </div>
    </div>
</section>
<section id="administration">
    <h2>Administration</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="c:\Users\monis\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\31839B036F63806CBA3F47B93AF8CCB5\WhatsApp Image 2024-11-23 at 11.45.19_932b052c.jpg"width="60%">
            <h3>FOUNDER</h3>
        </div>
        <div class="menu-item">
            <img src="c:\Users\monis\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\3B5DCA501EE1E6D8CD7B905F4E1BF723\WhatsApp Image 2024-11-23 at 11.45.51_c8e2881c.jpg"width="52%">
            <h3>MANAGER</h3>
        </div>
        <div class="menu-item">
            <img src="c:\Users\monis\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\E2A2DCC36A08A345332C751B2F2E476C\WhatsApp Image 2024-11-23 at 11.46.17_10b82e73.jpg"width="50%">
            <h3>BRAND AMBASSADOR</h3>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Tempting Kitchen is a popular restaurant known for its diverse menu and inviting atmosphere. It typically features a mix of cuisines, emphasizing fresh ingredients and bold flavors. Many locations focus on creating a warm, welcoming environment, making it a great spot for casual dining or special occasions.

        If you’re looking for specifics about its offerings, ambiance, or any signature dishes, let me know!
        We are in this field since 2006. Served 25000+ customers</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Anna nagar, Chennai- 600001</p>
    <p>Phone: 9876543213</p>
    <p>Email: temptingkitchen@gmail.com</p>
</section>
<footer>
    <p>@Owned by MONISH.S</p>
</footer>

</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-13 100818](https://github.com/user-attachments/assets/ae5ff3c9-443a-48f8-83b8-a64958d81680)
![Screenshot 2024-12-13 100844](https://github.com/user-attachments/assets/6345c81b-05cf-40b0-9944-99c4b06f0452)
![Screenshot 2024-12-13 100859](https://github.com/user-attachments/assets/9f1f5c31-52d8-4406-807f-ff55dc8e64d1)
![Screenshot 2024-12-13 100918](https://github.com/user-attachments/assets/71df2840-0ed7-4361-a500-30a6a163c725)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
