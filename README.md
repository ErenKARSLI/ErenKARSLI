#Eren Turgut KARSLI

Hello! I'm Eren, I'm a Developer. Welcome to my GitHub profile!

## Hakkımda

- 💼 currently freelance
- 🎓 TechProEducation Java Devoloper
- 💬 You can ask me questions about Java, JS and React.
- 📫 Reach me: Karslieren61@gmail.com

## 🔧 Languages ​​and Tools

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

---

![HTML_CSS](http://127.0.0.1:5500/index.html)

![HTML](<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="offer">
        <h2 class="offer__header">Special Offer</h2>
        <p class="offer__desc">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
        <button class="offer__btn">Claim offer</button>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>)

![CSS](* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  background-color: #111;
  font-family: sans-serif;
}

.container {
  position: relative;
  width: 100%;
  height: 100vh;
}

.offer {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #fff;
  padding: 2rem;
  border-radius: 1rem;
}

.offer__header {
  margin-bottom: 1rem;
}

.offer__desc {
  margin-bottom: 1rem;
}
)
![JavaScript](const button = document.querySelector(".offer__btn");
const header = document.querySelector(".offer__header");
const desc = document.querySelector(".offer__desc");

const texts = [
  "Limited Time Deal!",
  "Hurry up! Only today!",
  "Don't miss out!",
];

button.addEventListener("click", () => {
  const randomIndex = Math.floor(Math.random() * texts.length);
  header.textContent = texts[randomIndex];
});
)

