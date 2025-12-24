# Ex.06 Book Front Cover Page Design
## Date:24.12.2025
## Register number:25006451

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
cover.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="cover">
    <div class="inner-box">
      <h3 class="top">SEC Insights</h3>
      <h1 class="title">FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
      <p class="subtitle">Deep Dive in HTML, CSS & JS Basics<br>Top seller of 2025</p>

      <div class="bottom">
        <p class="special">SPECIAL EDITION</p>
        <div class="line"></div>
        <div class="bottom-row">
          <p class="author">S.VISHVABALA</p>
          <img class="photo">
          <p class="sec">SEC</p>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
~~~
style.css:
~~~
body {
  margin: 0;
  padding: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #6a11cb, #2575fc);
  font-family: "Segoe UI", Arial, sans-serif;
}

/* MAIN FORM CARD */
.cover {
  width: 420px;
  padding: 25px;
  background: rgba(255, 255, 255, 0.18);
  border-radius: 18px;
  backdrop-filter: blur(12px);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.35);
}

/* INNER CONTENT */
.inner-box {
  padding: 25px;
  border-radius: 15px;
  border: 2px solid rgba(255, 255, 255, 0.4);
}

/* FORM TITLE */
.top {
  color: #ffffff;
  text-align: center;
  font-size: 22px;
  letter-spacing: 1px;
  margin-bottom: 20px;
}

/* PHOTO */
.photo {
  width: 90px;
  height: 120px;
  border-radius: 12px;
  border: 2px solid #ffffff;
  background: url("my photo.jpeg") no-repeat center;
  background-size: cover;
  display: block;
  margin: 15px auto 25px auto;
}

/* INPUT LABELS */
label {
  color: #f5f5ff;
  font-size: 15px;
  font-weight: 500;
}

/* INPUT FIELDS */
input[type="text"],
input[type="number"],
input[type="email"] {
  width: 100%;
  padding: 12px;
  margin-top: 6px;
  margin-bottom: 16px;
  border-radius: 10px;
  border: none;
  outline: none;
  font-size: 15px;
  background: rgba(255, 255, 255, 0.9);
  color: #3b2a6f;
}

/* PLACEHOLDER */
input::placeholder {
  color: #9a8bc9;
}

/* BUTTON */
button,
input[type="submit"] {
  width: 100%;
  padding: 12px;
  border-radius: 12px;
  border: none;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  background: linear-gradient(135deg, #ff6ec4, #7873f5);
  color: #ffffff;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

/* BUTTON HOVER */
button:hover,
input[type="submit"]:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 25px rgba(120, 115, 245, 0.6);
}

/* RESULT / OUTPUT TEXT */
.result {
  margin-top: 18px;
  text-align: center;
  color: #ffebff;
  font-weight: 600;
}
~~~


## OUTPUT:
<img width="908" height="706" alt="image" src="https://github.com/user-attachments/assets/7203b443-c97d-4d30-ba39-ed58b592ac8f" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
