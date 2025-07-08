# Styled_Profile_Card
## Date: 08-07-2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sabitha Paulraj - Profile</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <section>
    <h1>Sabitha Paulraj</h1>
    <h2>Web Developer | Designer | Tech Enthusiast</h2>
    <img src="profile.jpg" alt="Sabitha Paulraj's Profile Photo" width="200" height="200">
    <article>
      <h3>About Me</h3>
      <p>
        Hi! I'm Sabitha Paulraj. I'm a 3rd yr CS undergrad obsessed with ML and GenAI. You'll usually find me working with LLMs or deep-diving into NLP just for fun. If it's AI and it's cool — I dive into it.
        Lately, I've been getting into system design — learning how to architect large-scale systems, from LLDs to HLDs that actually scale.<br><br>
        Connect with me on <a href="https://www.linkedin.com/in/sabithapaulraj/" target="_blank">LinkedIn</a> or visit my <a href="https://sabithapaulraj.netlify.app/" target="_blank">personal website</a>.
      </p>
    </article>
  </section>
</body>
</html> 
```
## CSS Code
```
body{
    background-color: lightgrey;
    font-family: Arial, Helvetica, sans-serif;
}
h1{
    
    text-align: center;
    color: slateblue;
}
h2{
    text-align: center;
    color: chocolate;
    
}
h3{
    text-align: center;
    color: teal;
    
}
img{
    display: block;
    margin: auto;
    width:15%;
    height: 30%;
    border-radius: 50%;
}
p{
    padding: 3rem;
    line-height: normal;
    border: 1px solid;
    background-color: whitesmoke;
}
section{
    margin: auto;
    padding: 2rem;
    background-color: white;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
div{
    text-align: center;
    padding: 1rem;
    margin: 1rem;
    background-color: lightcyan;
}
article{
    max-width: 50%;
    margin: auto;
    text-align: center;
    padding: 1rem;
    background-color: lightyellow;
}
```
## Output:
![image](https://github.com/user-attachments/assets/0afa7ee8-73f5-459b-9041-96d1a9e68469)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
