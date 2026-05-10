# Ex02 Commercial Website
## Date:10/05/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
# index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Tech Store</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#account">Account</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="section">
        <div class="content">
            <h2>Welcome to Tech Store</h2>
            <p>Your one-stop shop for gadgets and accessories.</p>
            <a href="#products">
    <button>Shop Now</button>
</a>
        </div>

        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c"
             alt="Tech Image">
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <h2>Our Products</h2>

        <div class="products-container">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9"
                     alt="Mobile">
                <h3>Smartphones</h3>
                <p>Latest Android and iPhone models.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853"
                 alt="Laptop">
                <h3>Laptops</h3>
                <p>High-performance laptops for work and gaming.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e"
                     alt="Headphones">
                <h3>Accessories</h3>
                <p>Headphones, chargers, and smart devices.</p>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>
            Tech Store provides high-quality electronic products
            with excellent customer service and affordable prices.
        </p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: techstore@gmail.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <!-- Account Section -->
    <section id="account" class="section">
        <h2>User Account</h2>

        <form>
            <input type="text" placeholder="Enter Username">
            <input type="password" placeholder="Enter Password">
            <button type="submit">Login</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow us on:</p>

        <div class="social-links">
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>

<a href="https://twitter.com" target="_blank">Twitter</a>
        </div>

        <p>© 2026 Tech Store. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
# style.css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
}

/* Header */
header{
    background:#222;
    color:white;
    padding:20px;

    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 10px;
    transition:0.3s;
}

nav a:hover{
    color:orange;
}

/* Sections */
.section{
    padding:40px;
}

/* Home Section */
#home{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
}

#home img{
    width:45%;
    border-radius:10px;
}

.content{
    width:50%;
}

.content button{
    margin-top:15px;
    padding:10px 20px;
    border:none;
    background:orange;
    color:white;
    cursor:pointer;
    transition:0.3s;
}

.content button:hover{
    background:darkorange;
}

/* Products */
.products-container{
    display:flex;
    justify-content:space-around;
    gap:20px;
    margin-top:20px;
}

.card{
    background:white;
    padding:20px;
    border-radius:10px;
    width:30%;
    text-align:center;
    box-shadow:0 2px 5px rgba(0,0,0,0.2);
    transition:0.3s;
}

.card:hover{
    transform:scale(1.05);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
    border-radius:10px;
}

/* About & Contact */
#about, #contact{
    background:white;
    margin:20px;
    border-radius:10px;
}

/* Account */
form{
    display:flex;
    flex-direction:column;
    width:300px;
    gap:15px;
}

form input{
    padding:10px;
}

form button{
    padding:10px;
    border:none;
    background:#222;
    color:white;
    cursor:pointer;
}

/* Footer */
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:20px;
}

.social-links a{
    color:orange;
    margin:0 10px;
    text-decoration:none;
}
```
## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/30aed33c-c58a-42de-9dc2-85ee4173bdd2" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/955f5ba5-52e5-4f99-8013-e7f84a3a0c43" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac8da480-6816-4c07-8d10-1d41cb8d1416" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
