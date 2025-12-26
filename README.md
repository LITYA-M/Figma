# Ex09 Event Registration Web Application
## Date:26/12/2025

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
HOME PAGE
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-25-204317-1.png" />
      <img class="image" src="img/image-1.png" />
      <img class="img" src="img/screenshot-2025-12-25-204317-2.png" />
      <img class="screenshot-2" src="img/screenshot-2025-12-26-124954-1.png" />
      <div class="text-wrapper">MUSIC EVENTS</div>
      <img class="rectangle" src="img/rectangle-2.svg" />
      <div class="div">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">REGISTER</div>
    </div>
  </body>
</html>

STYLE.CSS
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 399px;
  min-height: 766px;
  position: relative;
}

.iphone-pro .screenshot {
  top: 33px;
  left: 25px;
  width: 349px;
  height: 55px;
  position: absolute;
  aspect-ratio: 6.34;
  object-fit: cover;
}

.iphone-pro .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 399px;
  height: 766px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro .img {
  top: 30px;
  left: 20px;
  width: 369px;
  height: 58px;
  position: absolute;
  aspect-ratio: 6.34;
  object-fit: cover;
}

.iphone-pro .screenshot-2 {
  position: absolute;
  top: 485px;
  left: 44px;
  width: 330px;
  height: 223px;
  aspect-ratio: 1.48;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 135px;
  left: 76px;
  width: 252px;
  -webkit-text-stroke: 4px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #d73839;
  font-size: 32px;
  text-align: right;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 324px;
  left: 129px;
  width: 151px;
  height: 59px;
}

.iphone-pro .div {
  position: absolute;
  top: 333px;
  left: 84px;
  width: 229px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ed1313;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 411px;
  left: 103px;
  width: 212px;
  height: 51px;
  background-color: #bf31e6;
  border: 1px solid;
  border-color: #f53051;
  box-shadow: 0px 4px 4px #14131340;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 414px;
  left: 116px;
  width: 195px;
  -webkit-text-stroke: 3px #000000;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #f52a2a;
  font-size: 36px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}
PAGE 2
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="img" src="img/image-2.png" /></div>
  </body>
</html>
STYLE.CSS
.image {
  width: 431px;
  height: 766px;
}

.image .img {
  position: fixed;
  top: 0;
  left: 10px;
  width: 399px;
  height: 766px;
  aspect-ratio: 0.56;
  object-fit: cover;
}
PAGE 3
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="image" src="img/image-2.png" />
      <div class="rectangle"></div>
      <img class="screenshot" src="img/screenshot-2025-12-26-122456-1.png" />
      <img class="EVENT-REGISTRATION" src="img/EVENT-REGISTRATION-FORM.png" />
      <div class="text-wrapper">FULL NAME</div>
      <div class="div"></div>
      <div class="text-wrapper-2">GENDER</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">AGE</div>
      <img class="img" src="img/rectangle.png" />
      <div class="text-wrapper-4">MOBILE NUMBER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-5">EMAIL ID</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-6">EVENTS TO REGISTER</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-7">REGISTER</div>
    </div>
  </body>
</html>
STYLE.CSS
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 399px;
  min-height: 766px;
  position: relative;
}

.iphone-pro .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 399px;
  height: 766px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 146px;
  left: 12px;
  width: 326px;
  height: 33px;
  background-color: #d9d9d9;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 445px;
  left: 287px;
  width: 92px;
  height: 275px;
  aspect-ratio: 0.34;
  object-fit: cover;
}

.iphone-pro .EVENT-REGISTRATION {
  position: absolute;
  top: 95px;
  right: 3px;
  width: 339px;
  height: 28px;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 158px;
  left: 21px;
  width: 232px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .div {
  position: absolute;
  top: 205px;
  left: 12px;
  width: 241px;
  height: 34px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 215px;
  left: 20px;
  width: 125px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 263px;
  left: 12px;
  width: 249px;
  height: 32px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 270px;
  left: 21px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .img {
  position: absolute;
  top: 317px;
  left: 12px;
  width: 241px;
  height: 32px;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 326px;
  left: 19px;
  width: 133px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 376px;
  left: 12px;
  width: 318px;
  height: 42px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 379px;
  left: 27px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 444px;
  left: 12px;
  width: 263px;
  height: 43px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 457px;
  left: 25px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-5 {
  position: absolute;
  top: 548px;
  left: 65px;
  width: 182px;
  height: 40px;
  background-color: #d31818;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .text-wrapper-7 {
  position: absolute;
  top: 547px;
  left: 77px;
  -webkit-text-stroke: 2px #211515;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
PAGE 4
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="image" src="img/image-3.png" />
      <p class="we-are-all-eagerly">we are all eagerly waiting for your <br />participaton in music event.</p>
      <div class="text-wrapper">THANK YOU</div>
    </div>
  </body>
</html>
STYLE.CSS
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 399px;
  min-height: 766px;
  position: relative;
}

.iphone-pro .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 399px;
  height: 766px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro .we-are-all-eagerly {
  position: absolute;
  top: 205px;
  left: 51px;
  width: 270px;
  -webkit-text-stroke: 5px #000000;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #f53051;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 114px;
  left: 89px;
  -webkit-text-stroke: 2px #000000;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffde0a;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-12-26 182321.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
