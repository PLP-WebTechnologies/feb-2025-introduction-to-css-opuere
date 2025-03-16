# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

/* Class Selector */

.Green {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* ID Selector */

#Welcome {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

/* Tag Selector */

h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

/* Image Styling */

img {
  max-width: 100%;
  height: auto;
  margin: 20px 0;
  padding: 10px;
  border: 1px solid #ccc;
}

/* Margin, Padding, and Borders */

.button {
  background-color: #4CAF50;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.button:hover {
  background-color: #3e8e41;
}



<!DOCTYPE html>
<html lang="en">
<head>                          
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title><Medicar></title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div class="Green">
    <h1 id="Welcome">Welcome to Medichar</h1>
    <h3>Our Mission</h3>
    <p>"At Medichar, our mission is to provide immediate medical assistance and support to victims in emergency situations, ensuring they receive timely and compassionate care. We strive to bridge the gap between emergency response and family support, alleviating the financial burden of medical expenses for those in need."</p>
    <h3>Our Vision</h3>
    <p>"Our vision is to create a world where every individual has access to prompt and quality medical care, regardless of their financial situation. We envision Medichar as a beacon of hope, providing a safety net for those affected by unexpected medical emergencies, and empowering families to focus on recovery and healing."
</p>
    <h3>Core Values:</h3>
<ol type="I">
      <li><strong>Compassion</strong>: We provide empathetic and caring support to those in need.</li>
      <li><strong>Urgency</strong>: We respond promptly to emergency situations, ensuring timely medical intervention.</li>
      <li><strong>Integrity</strong>: We operate with transparency, accountability, and honesty in all our endeavors.</li>
      <li><strong>Collaboration</strong>: We foster partnerships with medical institutions, emergency services, and community organizations to amplify our impact.</li>
      <li><strong>Respect</strong>: We treat every individual with dignity and respect, regardless of their background or circumstances.
      </li>
    </ol>
    <h3>Objectives:</h3>
    <ol>
      <li> Provide immediate medical assistance to victims in emergency situations..</li>
      <li> Offer financial support for medical expenses, including hospital bills and treatment costs.</li>
      <li>Facilitate communication and coordination between emergency services, medical institutions, and family members. </li>
      <li>Raise awareness about the importance of timely medical intervention and the need for community support.</li>
      <li> Establish partnerships with medical institutions, corporations, and community organizations to sustain and expand our services.</li>
    </ol>
    <img src="Grace.png" alt="image">
    <button class="button">Submit</button>
  </div>
</body>
</html>



