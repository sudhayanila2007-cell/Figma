# Ex09 Event Registration Web Application
## Date:30/12/2025

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
Home page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">celanza</div>
      <div class="div">saveetha engineering college</div>
      <p class="REGISTER-to"><span class="span">REGISTER </span> <span class="text-wrapper-2">to participate</span></p>
      <p class="VENUE-COLLEGE">VENUE:COLLEGE AUDITORIUM<br />DATE : 15TH MARCH 2026</p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 893px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 893px;
  aspect-ratio: 0.74;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 311px;
  left: 107px;
  width: 276px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 73px;
  left: 67px;
  width: 344px;
  font-family: "Inter-ExtraLight", Helvetica;
  font-weight: 200;
  color: #21e0ba;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .REGISTER-to {
  position: absolute;
  top: 612px;
  left: 98px;
  width: 275px;
  font-family: "Inter-ExtraLight", Helvetica;
  font-weight: 200;
  color: transparent;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .span {
  color: #f4d614;
}

.iphone-pro-max .text-wrapper-2 {
  color: #ffffff;
}

.iphone-pro-max .VENUE-COLLEGE {
  position: absolute;
  top: 744px;
  left: 47px;
  width: 375px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
page 2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-2.png" />
      <div class="text-wrapper">Fest schedule</div>
      <p class="element-TO-AM">
        <span class="span"
          >9.00 TO 9.30 AM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          INAUGURATION CEREMONY<br />9.30 TO 10.30 AM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          WELCOME DANCE &amp; MUSIC<br />10.30 TO 12.00 AM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SOLO
          SINGING<br />12.00 TO 1.00 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          GROUP DANCE<br /><br /><br /><br
        /></span>
        <span class="text-wrapper-2"
          >1.00 TO 2.00 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LUNCH
          BREAK<br
        /></span>
        <span class="span"
          ><br /><br /><br /><br />2.00 TO 3.00 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MIME/SKIT<br />3.00
          TO 5.00 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FASHION
          SHOW<br />5.00 TO 6.30 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PRIZE
          DISTRIBUTION<br />6.30 TO 9.30 PM<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BAND
          PERFORMANCE</span
        >
      </p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 893px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 893px;
  aspect-ratio: 0.66;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 23px;
  left: 17px;
  width: 399px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #fa090d;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .element-TO-AM {
  position: absolute;
  top: 124px;
  left: 24px;
  width: 384px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: transparent;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .span {
  color: #000000;
}

.iphone-pro-max .text-wrapper-2 {
  color: #a735e9;
}

page 3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-3.png" />
      <div class="text-wrapper">REGISTRATION FORM</div>
      <p class="STUDENT-NAME">
        STUDENT NAME:...........................<br /><br />REGISTER
        NO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:...........................<br /><br />DEPARTMENT&nbsp;&nbsp;&nbsp;&nbsp;
        :...........................<br /><br />YEAR OF STUDY:............................<br /><br />EMAIL
        ID&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:............................<br /><br />MOBILE
        NO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; :............................<br /><br /><br /><br /><br />NOTE:<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <br />&nbsp;&nbsp;&nbsp;&nbsp; *ID card is mandatory<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Report 30
        minutes early<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *Judge’s decision is final
      </p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 885px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 885px;
  aspect-ratio: 0.71;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 0;
  left: 27px;
  width: 402px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .STUDENT-NAME {
  position: absolute;
  top: 87px;
  left: 25px;
  width: 404px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

page 4

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-4.png" />
      <div class="text-wrapper">EVENTS...</div>
      <p class="solo-dance-group">
        Solo dance<br />Group dance<br />Solo singing<br />Group singing<br />mime<br />Quiz<br />Painting<br />Rangoli<br />Short
        film<br />Band performance<br />Debate<br />Photography
      </p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 885px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 885px;
  aspect-ratio: 0.5;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 46px;
  left: 89px;
  width: 265px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #28d931;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .solo-dance-group {
  position: absolute;
  top: 146px;
  left: 29px;
  width: 352px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-12-30 131318.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
