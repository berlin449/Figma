# Ex09 Event Registration Web Application
# Date:14/10/2025
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
```
page1

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bgn" src="img/bgn-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Login</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">DESIGNED BY S.Bhuavnesh(25015685)</div>
      <div class="text-wrapper-4">Aurora Night’25</div>
      <img class="logo" src="img/logo-1.png" />
      <img class="img" src="img/logo-2.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 942.47px;
  min-height: 1216.98px;
  position: relative;
}

.android-medium .bgn {
  position: absolute;
  top: -2px;
  left: -2px;
  width: 936px;
  height: 1217px;
  transform: rotate(0.22deg);
  aspect-ratio: 0.74;
  object-fit: cover;
}

.android-medium .rectangle {
  top: 775px;
  box-shadow: 0px 4px 4px #00000040;
  position: absolute;
  left: 314px;
  width: 248px;
  height: 76px;
  background-color: #f12595;
  transform: rotate(0.22deg);
}

.android-medium .text-wrapper {
  position: absolute;
  top: 781px;
  left: 395px;
  width: 85px;
  transform: rotate(0.22deg);
  font-family: "Prociono-Regular", Helvetica;
  font-weight: 400;
  color: #f4f8f7;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
}

.android-medium .div {
  top: 895px;
  position: absolute;
  left: 314px;
  width: 248px;
  height: 76px;
  background-color: #f12595;
  transform: rotate(0.22deg);
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 907px;
  left: 362px;
  transform: rotate(0.22deg);
  font-family: "Pridi-Regular", Helvetica;
  font-weight: 400;
  color: #f4fcfc;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1163px;
  left: 111px;
  transform: rotate(0.22deg);
  font-family: "Prata-Regular", Helvetica;
  font-weight: 400;
  color: #c72424;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 667px;
  left: 309px;
  transform: rotate(0.22deg);
  font-family: "Poller One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: 52px;
  white-space: nowrap;
}

.android-medium .logo {
  top: 4px;
  left: 17px;
  width: 925px;
  height: 186px;
  aspect-ratio: 4.97;
  position: absolute;
  transform: rotate(0.22deg);
  object-fit: cover;
}

.android-medium .img {
  top: 206px;
  left: 230px;
  width: 461px;
  height: 444px;
  aspect-ratio: 1.04;
  position: absolute;
  transform: rotate(0.22deg);
  object-fit: cover;
}

page2

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="sss" src="img/sss-1.png" />
      <div class="text-wrapper">Aurora Night’25 Events</div>
      <p class="cricket-volley-ball">
        → Cricket<br /><br />→ Volley Ball<br /><br />→ Badminton<br /><br />→ Foot Ball<br /><br />→ 100 MTS<br /><br />→
        200MTS<br /><br />→ 1000 MTS
      </p>
      <div class="div">DESIGNED BY S.Bhuavnesh(25025685)</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 872px;
  min-height: 1217px;
  position: relative;
}

.android-medium .sss {
  position: absolute;
  top: 0;
  left: 0;
  width: 872px;
  height: 1217px;
  aspect-ratio: 0.75;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 150px;
  left: 241px;
  font-family: "Potta One-Regular", Helvetica;
  font-weight: 400;
  color: #ff2828;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
  white-space: nowrap;
}

.android-medium .cricket-volley-ball {
  position: absolute;
  top: 256px;
  left: 152px;
  font-family: "Potta One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
}

.android-medium .div {
  position: absolute;
  top: 1121px;
  left: 165px;
  font-family: "Prociono-Regular", Helvetica;
  font-weight: 400;
  color: #e4f2e3;
  font-size: 35px;
  letter-spacing: 0;
  line-height: 52px;
  white-space: nowrap;
}

page3

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bgn" src="img/bgn-2.png" />
      <div class="text-wrapper">Event Registration Form</div>
      <div class="div">Fill the details</div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">Full Name</div>
      <div class="text-wrapper-4">Gender</div>
      <div class="text-wrapper-5">Age</div>
      <div class="text-wrapper-6">Mobile Number</div>
      <div class="text-wrapper-7">Email</div>
      <div class="text-wrapper-8">DESIGNED BY S.Bhuvanesh(25015685)</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 868px;
  min-height: 1164px;
  position: relative;
}

.android-medium .bgn {
  position: absolute;
  top: 0;
  left: 0;
  width: 868px;
  height: 1164px;
  aspect-ratio: 0.74;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 79px;
  left: 180px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #ce1a29;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 124px;
  left: 180px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle {
  position: absolute;
  top: 213px;
  left: 88px;
  width: 525px;
  height: 87px;
  background-color: #fcf6f6;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 335px;
  left: 88px;
  width: 400px;
  height: 87px;
  background-color: #fdf6f6;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 457px;
  left: 88px;
  width: 400px;
  height: 87px;
  background-color: #fdf6f6;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 579px;
  left: 88px;
  width: 525px;
  height: 87px;
  background-color: #fdf6f6;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 701px;
  left: 88px;
  width: 400px;
  height: 87px;
  background-color: #fdf6f6;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 853px;
  left: 204px;
  width: 394px;
  height: 102px;
  background-color: #ff1212;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 880px;
  left: 290px;
  font-family: "jsMath-cmr10-cmr10", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 228px;
  left: 127px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 350px;
  left: 127px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 465px;
  left: 127px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 594px;
  left: 114px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 709px;
  left: 111px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 1106px;
  left: 9px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}
```
# OUTPUT:
<img width="1036" height="429" alt="Screenshot 2025-10-14 175940" src="https://github.com/user-attachments/assets/ca69e4dd-6876-48ce-8e39-7865c6693c88" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
