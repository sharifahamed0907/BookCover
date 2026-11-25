Ex.05 Book Cover Page Design
Date: 19.11.2026
AIM:
To design a book back cover page using HTML and CSS.

DESIGN STEPS:
Step 1:
Create a Django Admin project.

Step 2:
Create an app in the Django interface.

Step 3:
Create a folder named 'static' in the app folder.

Step 4:
Create a new HTML file in the static folder.

Step 5:
Write the HTML code with relevant CSS properties.

Step 6:
Choose the appropriate style and color scheme.

Step 7:
Insert the images in their appropriate places.

Step 8:
Publish the website in the LocalHost.

PROGRAM:
'''
<!DOCTYPE html>
<html>
<head>
  <title>Book Cover Page</title>
  <style>
    body {
      background: linear-gradient(to right, #2c1a5c, #c2398a);
      font-family: Georgia, serif;
    }

    /* holds both covers side by side */
    .book {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }

    /* style shared by front and back */
    .front, .back {
      width: 320px;
      height: 500px;
      padding: 20px;
      text-align: center;
      color: white;
      border: 4px solid gold;
      border-radius: 12px;
      box-shadow: 0 8px 20px black;
    }

    .front {
      background: linear-gradient(#5b2a9a, #e0457b, #ff9f43);
    }

    .back {
      background: linear-gradient(#ff9f43, #e0457b, #5b2a9a);
    }

    h1 {
      color: gold;
      font-size: 32px;
    }

    h2 {
      color: gold;
    }

    .cover-img {
      width: 230px;
      height: 230px;
      margin: 0 auto;
      border-radius: 50%;
      border: 4px solid white;
      overflow: hidden;       /* clips the drawing into a circle */
    }

    .author {
      font-size: 20px;
      letter-spacing: 2px;
      margin-top: 15px;
    }

    .review {
      background-color: rgba(255, 255, 255, 0.2);
      padding: 8px;
      border-radius: 8px;
      font-style: italic;
      font-size: 14px;
    }

    .price {
      font-weight: bold;
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <div class="book">

    <!-- BACK COVER -->
    <div class="back">
      <h2>About the Book</h2>
      <p>
        Meera leaves her city for a quiet month by the sea. There she finds
        an old lighthouse, a silent keeper and a letter meant for her.
      </p>
      <p class="review">"A warm and exciting read." - Daily Reader</p>
      <p>Anita Raman lives in Tamil Nadu and writes about home and memory.</p>
      <p class="price">Price: Rs. 399</p>
    </div>

    <!-- FRONT COVER -->
    <div class="front">
      <h1>The Lighthouse</h1>
      <p>A Novel</p>
      <div class="cover-img">
        <svg viewBox="0 0 200 200">
          <rect width="200" height="200" fill="#c2398a"/>
          <rect y="90" width="200" height="50" fill="#ff9f43"/>
          <circle cx="100" cy="130" r="34" fill="#ffd36b"/>
          <polygon points="100,62 200,30 200,86" fill="#fff6b0" opacity="0.4"/>
          <polygon points="100,62 0,30 0,86" fill="#fff6b0" opacity="0.4"/>
          <rect y="130" width="200" height="70" fill="#1d4e89"/>
          <path d="M60 150 Q100 118 140 150 L150 170 H50Z" fill="#3b2f4a"/>
          <polygon points="88,142 112,142 107,76 93,76" fill="white"/>
          <polygon points="90,126 110,126 109,114 91,114" fill="#e63946"/>
          <polygon points="93,100 107,100 106,90 94,90" fill="#e63946"/>
          <rect x="91" y="64" width="18" height="12" fill="#ffd60a"/>
          <polygon points="89,64 111,64 100,52" fill="#e63946"/>
        </svg>
      </div>
      <p class="author">ANITA RAMAN</p>
    </div>

  </div>
</body>
</html>
'''
OUTPUT:

![alt text](<Screenshot 2026-11-19 220230.png>)

RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
