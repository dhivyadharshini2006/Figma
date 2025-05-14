# Ex09 Event Registration Web Application
## Date:14/5/25
## Name :Dhivya Dharshini B
## Date :212223240031

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Christmas Event Registration</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
    }

    section {
      min-height: 100vh;
      padding: 40px 20px;
      text-align: center;
      background-size: cover;
      background-position: center;
      position: relative;
      color: #fff;
    }

    section::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      height: 100%; width: 100%;
      background: rgba(0, 0, 0, 0.5); /* Dark overlay for readability */
      z-index: 0;
    }

    section > * {
      position: relative;
      z-index: 1;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
      color: #ffeb3b;
      text-shadow: 3px 3px #b71c1c;
    }

    h2, p {
      font-size: 22px;
      color: #ffccbc;
      margin-bottom: 20px;
      text-shadow: 1px 1px #880e4f;
    }

    .button {
      display: inline-block;
      margin: 10px;
      padding: 12px 28px;
      background-color: #d50000;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      box-shadow: 3px 3px 8px #222;
    }

    .button:hover {
      background-color: #b71c1c;
    }

    .form input, .form select {
      display: block;
      margin: 10px auto;
      padding: 12px;
      width: 90%;
      max-width: 400px;
      border: 2px solid #ffeb3b;
      border-radius: 5px;
      font-size: 16px;
    }

    .form button {
      padding: 10px 25px;
      background-color: #43a047;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 18px;
      cursor: pointer;
      margin-top: 10px;
    }

    .form button:hover {
      background-color: #2e7d32;
    }

    ul {
      list-style-type: none;
      padding: 0;
      font-size: 22px;
      color: #ffe57f;
    }

    li::before {
      content: "🎄 ";
    }

    /* Section backgrounds */
    #home {
      background-image: url('https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=1400&q=80');
    }

    #events {
      background-image: url('https://images.unsplash.com/photo-1608888926646-76e3d6c7a3d8?auto=format&fit=crop&w=1400&q=80');
    }

    #register {
      background-image: url('https://images.unsplash.com/photo-1608889088852-77f9b51b4a6e?auto=format&fit=crop&w=1400&q=80');
    }

    #contact {
      background-image: url('https://images.unsplash.com/photo-1608888944336-b93ffab2905c?auto=format&fit=crop&w=1400&q=80');
    }

    .contact-info {
      background: rgba(0, 0, 0, 0.6);
      display: inline-block;
      padding: 20px;
      border-radius: 10px;
      color: #fff9c4;
      font-weight: bold;
    }
  </style>
</head>
<body>

<!-- HOME PAGE -->
<section id="home">
  <h1>🎅 CHRISTMAS CELEBRATION</h1>
  <img src="https://cdn-icons-png.flaticon.com/512/6714/6714978.png" alt="Christmas Icon" width="100">
  <h2>Joy, Music, Games & Lights!</h2>
  <a href="#events" class="button">View Events</a>
  <a href="#register" class="button">Register Now</a>
</section>

<!-- EVENTS PAGE -->
<section id="events">
  <h1>🎁 Christmas Events</h1>
  <ul>
    <li>Christmas Tree Decoration</li>
    <li>Santa Parade</li>
    <li>Carol Singing</li>
    <li>Secret Santa Gift Exchange</li>
    <li>Snowman Building Contest</li>
    <li>Gingerbread House Contest</li>
  </ul>
  <a href="#home" class="button">Back to Home</a>
</section>

<!-- REGISTRATION PAGE -->
<section id="register">
  <h1>Register to Participate 🎉</h1>
  <form class="form">
    <input type="text" placeholder="Full Name" required>
    <select required>
      <option disabled selected>Gender</option>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </select>
    <input type="number" placeholder="Age" required>
    <input type="text" placeholder="Class/Department" required>
    <input type="tel" placeholder="Mobile Number" required>
    <input type="email" placeholder="Email ID" required>
    <select required>
      <option disabled selected>Choose Event</option>
      <option>Christmas Tree Decoration</option>
      <option>Singing</option>
      <option>Gift Exchange</option>
    </select>
    <button type="submit">🎄 Submit</button>
  </form>
</section>

<!-- CONTACT PAGE -->
<section id="contact">
  <h1>🎅 Thank You!</h1>
  <h2>We’re excited for your participation!</h2>
  <div class="contact-info">
    <p><strong>Contact Us</strong></p>
    <p>Email: christmas@yourcollege.edu</p>
    <p>Phone: +91 9876543210</p>
    <p>Saveetha Engineering College</p>
  </div>
  <br>
  <a href="#home" class="button">Back to Home</a>
</section>

</body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d442e126-c46a-43ba-8aa2-fe37d9f0a40a)
![image](https://github.com/user-attachments/assets/0b3c7033-a6bf-4154-b9d4-cc889362c295)
![image](https://github.com/user-attachments/assets/ec13c612-a282-447b-b568-31b495194827)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
