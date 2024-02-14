# Blackbucks_web_and_react

Part 1: Web Development Basics
1. "Overview of Web Development"

Write a brief paragraph explaining what web development is and why it is important.
Answer:
Web development refers to the process of creating and maintaining websites or web applications for the internet. 
It encompasses a range of tasks, including web design, coding, scripting, and content management. Web development
plays a crucial role in the digital age as it enables individuals, businesses, and organizations to establish an 
online presence and interact with a global audience. A well-designed and functional website not only serves as a 
virtual storefront but also facilitates communication, collaboration, and the delivery of information or services.
In today's interconnected world, where online presence is often the first point of contact for potential customers 
or users, effective web development is vital for establishing credibility, enhancing user experience, and achieving 
success in the digital realm.

2. HTML Basics"
- Create an HTML file ('index.html') that includes a basic structure with '<html>', '<head>', and <body>' tags.
Add a title to the webpage.
Include a paragraph ('<p>") with some text.
Answer:
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>
    <p>This is a simple paragraph with some text. You can replace this text with your own content.</p>
</body>
</html>

3. CSS Basics
- Create a CSS file ('styles.css) and link it to your HTML file.
- Style the paragraph text to be blue and centered using CSS.
Answer:
body {
    font-family: Arial, sans-serif; 
}

p {
    color: blue; /* Set the text color to blue */
    text-align: center; /* Center-align the text */
}
adding a line to existing index.html file i.e
<link rel="stylesheet" href="styles.css">

4. JavaScript Basics
Create a JavaScript file ('script.js') and link it to your HTML file.
- Write a JavaScript function that changes the text color of the paragraph to red when a button is clicked.
Answer:
function changeTextColor() {
    var paragraph = document.getElementById("myParagraph");
    paragraph.style.color = "red";
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <p id="myParagraph">This is a simple paragraph with some text. You can replace this text with your own content.</p>
    <button onclick="changeTextColor()">Change Text Color to Red</button>
</body>
</html>




