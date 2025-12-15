# Ex.05 Book Cover Page Design
## Date: 15.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
cover.html

<html>
    <head>
        <title>Cover</title>
        <link rel="stylesheet" href="styles.css">
    </head>
<body>
<div class="container">
    <h2>About the Book</h2>
    <hr>
    <p>
        This book, <mark>"Foundations of Modern Software Engineering"</mark> offers a clear and practical introduction to building reliable, scalable, and efficient software systems. It bridges the gap between theory and real-world application, guiding readers through the core concepts that shape today’s software development practices.
        The book explores fundamental programming principles, software design patterns, version control, testing strategies, and collaborative development workflows. Emphasis is placed on writing clean, maintainable code and understanding how software systems evolve from simple ideas into robust digital solutions. Whether you are a student, beginner, or aspiring professional, this book provides a strong foundation for success in the software industry.
    </p>
    <div class="quote">
        "Great software is not just written - it is designed, tested, and continuously improved.""
    </div>
    <div class="authbox">
        <img src="kho1.jpeg" alt="Author Image">
        <div>
            <h3>Khovarthan V</h3>
            <p>
                Khovarthan V is a passionate learner and emerging professional in the field of software and technology. With a strong interest in modern development practices and problem-solving, Khovarthan V focuses on building a solid understanding of core computing concepts and their practical applications. Through this book, the author aims to simplify complex ideas and inspire readers to approach software development with clarity, confidence, and creativity.
            </p>
        </div>
    </div>
    <div class="footer">
        <span><b>SEC Publishers</b><br>Printed in India</span>
        <span class="price">Price: Rs.899</span>
    </div>
</div>
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background: linear-gradient(gold,black) 
}
.container {
    background: white;
    width: 46%;
    margin: auto;
    padding: 25px;
    border-radius: 10px;
    border: 2px solid red
}
h2{
    color: red;
}
hr {
    border: none;
    height: 2px;
    background: red;
    margin: 10px 0 20px 0;
}
p {
    line-height: 2;
    color: black;
}
.quote {
    border: 1px solid red;
    background: lightyellow;
    border-left: 5px solid red;
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
    color: black;
    border-radius: 5px;
}
.authbox {
    display: flex;
    background: lightyellow;
    padding: 15px;
    border-radius: 10px;
    border: 1px solid red;
    margin-top: 25px;
    gap: 15px;
}
.authbox img {
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
    border: 2px solid red;
}
.authbox h3 {
    margin: 0 0 5px 0;
    color: red;
}
.footer {
    margin-top: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: lightcoral;
    color: darkblue;
    padding: 12px 20px;
    border-radius: 10px;
}
.price {
    font-weight: bold;
    font-size: 18px;
}
```

## OUTPUT:

![alt text](<Screenshot (51).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
