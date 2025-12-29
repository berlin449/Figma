# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE: 
EVENT DAY
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Event Days - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #111;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 24px;
    }
    .logo {
      margin-bottom: 24px;
      width: 220px;
      height: 60px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 16px;
      font-weight: bold;
      color: #0a3871;
    }
    .events {
      color: #0f0;
      font-family: Arial, sans-serif;
      font-size: 20px;
      text-align: center;
      margin-bottom: 12px;
    }
    .at-sec {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 28px;
    }
    .event-list {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 17px;
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .event-list li {
      margin-bottom: 18px;
      letter-spacing: 1px;
    }
    .event-list li::before {
      content: "★ ";
      color: #fff;
      margin-right: 7px;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="events">
      "EVENT DAYS"
    </div>
    <div class="at-sec">
      AT SEC
    </div>
    <ul class="event-list">
      <li>ICEMS '25</li>
      <li>HACKATHON</li>
      <li>FLASH MOB</li>
      <li>CELENZA</li>
    </ul>
  </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hackathon Event - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #19a73c;
      border-radius: 38px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 22px;
      padding-bottom: 22px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 60px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 16px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 18px;
    }
    .event-title {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 24px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 10px;
    }
    .description {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 24px;
    }
    .details {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 20px;
      text-align: center;
      margin-bottom: 18px;
    }
    .register-btn {
      display: block;
      margin: 0 auto 16px auto;
      padding: 7px 32px;
      background: #fff;
      color: #19a73c;
      font-family: Arial, sans-serif;
      font-size: 18px;
      font-weight: bold;
      border: 2px solid #fff;
      border-radius: 6px;
      cursor: pointer;
      text-align: center;
    }
    .cash-message {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 18px;
      position: absolute;
      left: 50%;
      bottom: 32px;
      transform: translateX(-50%);
      width: 90%;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "HACKATHON"
    </div>
    <div class="description">
      The word "hackathon"<br>
      is a combination of the word "hack" and<br>
      "marathon".
    </div>
    <div class="details">
      DATE:03/01/2026<br>
      PRIZE:1,00,000/-
    </div>
    <button class="register-btn">REGISTER</button>
    <div class="cash-message">
      Participate and win<br>
      the cash money
    </div>
  </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flash Mob Event - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #f71010;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 24px 16px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 54px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 15px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 10px;
      margin-top: 2px;
    }
    .event-title {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 10px;
    }
    .description {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 26px;
    }
    .details {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 22px;
      text-align: center;
      margin-bottom: 12px;
    }
    .register-btn {
      display: block;
      margin: 0 auto 18px auto;
      padding: 8px 30px;
      background: #fff;
      color: #f71010;
      font-family: Arial, sans-serif;
      font-size: 18px;
      font-weight: bold;
      border: 2px solid #f71010;
      border-radius: 6px;
      cursor: pointer;
      text-align: center;
      box-shadow: 1px 1px 2px #bbb;
    }
    .cash-message {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 18px;
      background: rgba(0,0,0,0.11);
      border-radius: 8px;
      padding: 10px;
      position: absolute;
      left: 50%;
      bottom: 24px;
      transform: translateX(-50%);
      width: 88%;
      text-align: center;
    }
    .details .date,
    .details .prize {
      display: block;
      margin-bottom: 6px;
    }
    .details .date {
      color: #fc8989;
      font-size: 22px;
      font-weight: bold;
    }
    .details .prize {
      color: #870000;
      font-size: 22px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "FLASH MOB"
    </div>
    <div class="description">
      A celebration of joy,<br>
      energy, and rhythm,<br>
      where students dance<br>
      to the beats of a<br>
      live DJ.
    </div>
    <div class="details">
      <span class="date">DATE:05/01/2026</span>
      <span class="prize">PRIZE:50,000/-</span>
    </div>
    <button class="register-btn">REGISTER</button>
    <div class="cash-message">
      Participate and win<br>
      the prize money
    </div>
  </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=320, initial-scale=1.0">
  <title>CELENZA - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #ef90e6;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 24px 16px 0 16px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 54px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 15px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 12px;
      margin-top: 2px;
    }
    .event-title {
      color: #2a043f;
      font-family: Arial, sans-serif;
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 14px;
    }
    .description {
      color: #121212;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: left;
      margin-bottom: 28px;
      line-height: 1.3;
    }
    .details {
      color: #e90038;
      font-family: Arial, sans-serif;
      font-size: 21px;
      font-weight: bold;
      text-align: left;
      margin-bottom: 22px;
    }
    .call-participate {
      color: #121212;
      font-family: Arial, sans-serif;
      font-size: 21px;
      font-weight: bold;
      text-align: left;
      margin-bottom: 32px;
      line-height: 1.2;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "CELENZA"
    </div>
    <div class="description">
      Cultural events and<br>
      activities that showcase<br>
      students talent,<br>
      innovation and<br>
      competitive spirit
    </div>
    <div class="details">
      DATE:10/01/2026
    </div>
    <div class="call-participate">
      COME AND<br>
      PARTICIPATE<br>
      AND ENJOY<br>
      THE EVENTS
    </div>
  </div>
</body>
</html>
# OUTPUT:
![banner](https://github.com/user-attachments/assets/08974879-e4bd-4326-9a02-05e956b71b9a)
![event days](https://github.com/user-attachments/assets/c60eb794-babe-4883-99ea-e87520ab4239)
![icems](https://github.com/user-attachments/assets/a5ea147b-f0e1-474c-b030-6c47021e6ed5)
![hackathon](https://github.com/user-attachments/assets/02d74246-0c53-4731-ab6e-a6dc4031a45c)
![flash mob](https://github.com/user-attachments/assets/12454de1-6e8c-447f-9e71-f577b42bc718)
![celenza](https://github.com/user-attachments/assets/044ab417-0cc8-4ffa-bc3d-be8366604580)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
