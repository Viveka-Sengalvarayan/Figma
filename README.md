# Ex09 Event Registration Web Application
## Date:06.10.2025

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hostel Fest - Saveetha Engineering College</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <!-- Screen 1: Welcome -->
  <section class="screen welcome">
    <h1>Saveetha Engineering College</h1>
    <h2>HOSTEL FEST</h2>
    <div class="buttons">
      <button>LOGIN</button>
      <button>REGISTER</button>
    </div>
  </section>

  <!-- Screen 2: Events -->
  <section class="screen events">
    <h2>EVENTS</h2>
    <ul>
      <li>MEHANDI</li>
      <li>CHESS</li>
      <li>BADMINTON</li>
      <li>DIGITAL ART</li>
      <li>COOKING WITHOUT FIRE</li>
      <li>DRAWING</li>
      <li>CARROM</li>
      <li>ATHLETICS</li>
    </ul>
  </section>

  <!-- Screen 3: Registration Form -->
  <section class="screen registration">
    <h2>EVENT REGISTRATION FORM</h2>
    <form>
      <input type="text" placeholder="Full Name" required />
      <select required>
        <option value="">Gender</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
      </select>
      <input type="number" placeholder="Age" required />
      <input type="email" placeholder="Mail ID" required />
      <select required>
        <option value="">Event to Register</option>
        <option value="mehandi">Mehandi</option>
        <option value="chess">Chess</option>
        <!-- Add other events here -->
      </select>
      <button type="submit">REGISTER</button>
    </form>
  </section>

  <!-- Screen 4: Thank You -->
  <section class="screen thankyou">
    <h1>THANK YOU</h1>
    <p>We are eagerly waiting for your participation,<br>let's enjoy together!!!</p>
    <h3>CONTACT US</h3>
    <p>saveethahostel@gmail.com<br>25849679136<br>7594961235</p>
  </section>
</body>
</html>
```
```
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

.screen {
  padding: 2rem;
  text-align: center;
  border-bottom: 2px solid #ddd;
}

.welcome h1 {
  font-size: 1.8rem;
  color: #444;
}

.welcome h2 {
  font-size: 2.5rem;
  color: #e91e63;
  margin: 1rem 0;
}

.buttons button {
  margin: 0.5rem;
  padding: 0.8rem 1.5rem;
  font-size: 1rem;
  background-color: #e91e63;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.events ul {
  list-style-type: none;
  padding: 0;
}

.events li {
  font-size: 1.2rem;
  margin: 0.5rem 0;
}

.registration form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 400px;
  margin: auto;
}

.registration input,
.registration select {
  padding: 0.8rem;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.registration button {
  background-color: #4caf50;
  color: white;
  padding: 0.8rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.thankyou h1 {
  font-size: 2rem;
  color: #4caf50;
}

.thankyou p {
  font-size: 1.2rem;
  margin: 1rem 0;
}

.thankyou h3 {
  margin-top: 2rem;
  font-size: 1.5rem;
  color: #333;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-06 163033.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
