![heart-bg](https://github.com/user-attachments/assets/ace534ba-6b70-44c8-ba7f-75f22ffc3b87)
<img width="381" height="211" alt="no" src="https://github.com/user-attachments/assets/8f491b06-0cb3-4e14-888d-e2c0f689d737" /><img width="500" height="398" alt="envelope" src="https://github.com/user-attachments/assets/eef39c62-03fe-4083-a6a8-d0450a39ed66" />
![cat_heart](https://github.com/user-attachments/assets/62a1eb41-e253-4706-930e-6d796422d134)
![cat_dance](https://github.com/user-attachments/assets/878db894-50e8-47cc-a4f6-fe69057003ba)
<img width="380" height="211" alt="yes" src="https://github.com/user-attachments/assets/737be917-82d0-4a44-b84d-7802c3c7144e" />
<img width="5000" height="4563" alt="window" src="https://github.com/user-attachments/assets/7dd2528d-4a72-44f5-ac63-2806c9f6de5f" />
[style.css](https://github.com/user-attachments/files/25091098/style.css)
[settings.json](https://github.com/user-attachments/files/25091097/settings.json)
[script.js](https://github.com/user-attachments/files/25091096/script.js)
[index.html](https://github.com/user-attachments/files/25091111/index.html)
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="style.css" />
    <title>Valentine Letter</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Aldrich&family=Pixelify+Sans:wght@400..700&display=swap"
      rel="stylesheet"
    />
    <title>Document</title>
  </head>
  <body>
    <!-- Envelope Screen -->
    <div id="envelope-container">
      <img src="envelope.png" alt="Envelope" id="envelope" />
      <p>♡ Letter for You ♡</p>
    </div>

    <!-- Letter Screen -->
    <div id="letter-container">
      <div class="letter-window">
        <h1 id="letter-title">這是鉦凱喵的邀請，情人節一起過嗎?</h1>

        <img src="cat_heart.gif" class="cat" id="letter-cat" />

        <div class="buttons" id="letter-buttons">
          <img src="yes.png" class="btn yes-btn" alt="Yes" />

          <div class="no-wrapper">
            <img src="no.png" class="btn no-btn" alt="No" />
          </div>
        </div>

        <p id="final-text" class="final-text" style="display: none">
          <strong>Valentine Date:</strong> 我就知道，請找一天跟我一起喵喵約會!
        </p>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
