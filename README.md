# Ex09 Event Registration Web Application
## Date:

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
  <meta charset="UTF-8">
  <title>Sports Day Events</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }
    .page {
      width: 100vw;
      height: 100vh;
      padding: 20px;
      display: none;
      text-align: center;
    }
    .active {
      display: block;
    }
    .btn {
      padding: 10px 20px;
      margin: 10px;
      background-color: plum;
      border: none;
      border-radius: 20px;
      cursor: pointer;
    }
    input {
      display: block;
      margin: 10px auto;
      padding: 10px;
      width: 80%;
    }
    .event-list {
      margin-top: 30px;
      font-size: 20px;
    }
    .event-list li {
      list-style: none;
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <!-- Page 1: Welcome -->
  <div class="page active" id="page1">
    <h2>Saveetha Engineering College</h2>
    <p><strong>Sports Day Events</strong></p>
    <button class="btn" onclick="showPage('page2')">Login</button>
    <button class="btn" onclick="showPage('page2')">Register</button>
  </div>

  <!-- Page 2: Events List -->
  <div class="page" id="page2">
    <h2>Sports Day Events</h2>
    <ul class="event-list">
      <li>★ Cricket</li>
      <li>★ Badminton</li>
      <li>★ Volleyball</li>
      <li>★ 100 mts</li>
      <li>★ Kho Kho</li>
    </ul>
    <button class="btn" onclick="showPage('page3')">Proceed to Register</button>
  </div>

  <!-- Page 3: Registration Form -->
  <div class="page" id="page3">
    <h2>Events Registration Form</h2>
    <input type="text" placeholder="Name">
    <input type="text" placeholder="Gender">
    <input type="number" placeholder="Age">
    <input type="text" placeholder="Reg No">
    <input type="text" placeholder="Department">
    <input type="tel" placeholder="Mobile No">
    <input type="email" placeholder="Email">
    <input type="text" placeholder="Events to register">
    <button class="btn" onclick="showPage('page4')">Register</button>
  </div>

  <!-- Page 4: Thank You -->
  <div class="page" id="page4">
    <h2>Thank You</h2>
    <p>We are all eagerly waiting for your participation in the events.</p>
  </div>

  <script>
    function showPage(id) {
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>

</body>
</html>

```


## OUTPUT:

![Screenshot 2025-05-12 222327](https://github.com/user-attachments/assets/6f088ea8-414d-449e-99a1-1343e8e4ed88)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
