# Ex08 Event Registration Web Application
## Date:24/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
```
fram1.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="rectangle"></div>
      <img class="logo-sec" src="img/logo-sec-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <div class="div"></div>
      <img class="img" src="img/rectangle-3.svg" />
      <div class="rectangle-2"></div>
      <img class="talent" src="img/talent1-1.png" />
      <div class="text-wrapper">TALENT NIGHT EVENT</div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
    </div>
  </body>
</html>

styles1.css
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 301px;
  min-height: 567px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 301px;
  height: 567px;
  background-color: #ca84b2;
}

.frame .logo-sec {
  position: absolute;
  top: 0;
  left: 0;
  width: 301px;
  height: 61px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.frame .logo {
  position: absolute;
  top: 61px;
  left: 75px;
  width: 151px;
  height: 127px;
  aspect-ratio: 1.19;
}

.frame .div {
  position: absolute;
  top: 223px;
  left: 15px;
  width: 272px;
  height: 42px;
  background-color: #d85151;
}

.frame .img {
  position: absolute;
  top: 284px;
  left: 67px;
  width: 168px;
  height: 33px;
}

.frame .rectangle-2 {
  position: absolute;
  top: 336px;
  left: 67px;
  width: 168px;
  height: 34px;
  background-color: #afe95d;
}

.frame .talent {
  position: absolute;
  top: 389px;
  left: 67px;
  width: 166px;
  height: 165px;
  aspect-ratio: 1.01;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 231px;
  left: 41px;
  width: 232px;
  font-family: "Mplus 1p Bold-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 284px;
  left: 111px;
  width: 77px;
  font-family: "Mplus 1p Bold-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 341px;
  left: 96px;
  width: 109px;
  font-family: "Mplus 1p Bold-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

frame2.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="rectangle" src="img/rectangle-5.png" />
      <div class="div"></div>
      <img class="star" src="img/star-2.svg" />
      <img class="img" src="img/star-3.svg" />
      <img class="star-2" src="img/star-4.svg" />
      <img class="star-3" src="img/star-5.svg" />
      <img class="star-4" src="img/star-6.svg" />
      <img class="star-5" src="img/star-7.svg" />
      <img class="star-6" src="img/star-8.svg" />
      <img class="star-7" src="img/star-9.svg" />
      <div class="text-wrapper">SOLO SINGING</div>
      <div class="text-wrapper-2">GROUP SINGING</div>
      <div class="text-wrapper-3">SOLO DANCE</div>
      <div class="text-wrapper-4">GROUP DANCE</div>
      <div class="text-wrapper-5">INSTRUMENTAL PLAYING</div>
      <div class="text-wrapper-6">MIMICRY</div>
      <div class="text-wrapper-7">STAND-UP COMEDY</div>
      <div class="text-wrapper-8">BEATBOX</div>
    </div>
  </body>
</html>

style2.css

.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 301px;
  min-height: 567px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 301px;
  height: 567px;
  object-fit: cover;
}

.frame .div {
  position: absolute;
  top: 16px;
  left: 15px;
  width: 272px;
  height: 42px;
  background-color: #f7be02;
}

.frame .star {
  top: 79px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .img {
  top: 310px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-2 {
  top: 277px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-3 {
  top: 244px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-4 {
  top: 211px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-5 {
  top: 178px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-6 {
  top: 145px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .star-7 {
  top: 112px;
  position: absolute;
  left: 51px;
  width: 21px;
  height: 16px;
}

.frame .text-wrapper {
  top: 76px;
  width: 164px;
  position: absolute;
  left: 88px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-2 {
  top: 109px;
  position: absolute;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-3 {
  top: 142px;
  position: absolute;
  left: 88px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-4 {
  top: 175px;
  position: absolute;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 208px;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 241px;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 274px;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-8 {
  position: absolute;
  top: 307px;
  left: 86px;
  font-family: "Mouse Memoirs-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

frame3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="rectangle" src="img/rectangle-1.png" />
      <div class="div"></div>
      <div class="text-wrapper">SUBMIT</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">EMAIL</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-3">REGISTER NO</div>
      <div class="text-wrapper-4">GENDER</div>
      <div class="text-wrapper-5">PHONE NUMBER</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-6">NAME</div>
      <div class="EVENT-SELECTED">EVENT<br />&nbsp;&nbsp;&nbsp;&nbsp;SELECTED</div>
    </div>
  </body>
</html>

style3.css

.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 301px;
  min-height: 567px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 301px;
  height: 567px;
  object-fit: cover;
}

.frame .div {
  position: absolute;
  top: 506px;
  left: 59px;
  width: 183px;
  height: 44px;
  background-color: #f5cbcb;
}

.frame .text-wrapper {
  position: absolute;
  top: 514px;
  left: 103px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 264px;
  left: 59px;
  width: 159px;
  height: 29px;
  background-color: #a99d9d;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 264px;
  left: 107px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-3 {
  position: absolute;
  top: 307px;
  left: 59px;
  width: 158px;
  height: 49px;
  background-color: #a99d9d;
}

.frame .rectangle-4 {
  position: absolute;
  top: 221px;
  left: 59px;
  width: 159px;
  height: 29px;
  background-color: #a99d9d;
}

.frame .rectangle-5 {
  position: absolute;
  top: 178px;
  left: 59px;
  width: 159px;
  height: 29px;
  background-color: #a99d9d;
}

.frame .rectangle-6 {
  position: absolute;
  top: 135px;
  left: 59px;
  width: 159px;
  height: 29px;
  background-color: #a99d9d;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 135px;
  left: 75px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 178px;
  left: 98px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 221px;
  left: 62px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-7 {
  position: absolute;
  top: 92px;
  left: 59px;
  width: 159px;
  height: 29px;
  background-color: #a99d9d;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 92px;
  left: 108px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .EVENT-SELECTED {
  position: absolute;
  top: 303px;
  left: 82px;
  font-family: "Moul-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}
```
```

## OUTPUT:
![alt text](<Screenshot 2025-12-24 114223.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
