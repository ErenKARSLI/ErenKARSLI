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
import Grid1Background from 'https://cdn.jsdelivr.net/npm/threejs-components@0.0.16/build/backgrounds/grid1.cdn.min.js'

const bg = Grid1Background(document.getElementById('webgl-canvas'))

const button1 = document.getElementById('colors-btn')
button1.addEventListener('click', () => {
  bg.grid.setColors([0xffffff * Math.random(), 0xffffff * Math.random(), 0xffffff * Math.random()])
  bg.grid.light1.color.set(0xffffff * Math.random())
  bg.grid.light1.intensity = 500 + Math.random() * 1000
  bg.grid.light2.color.set(0xffffff * Math.random())
  bg.grid.light2.intensity = 250 + Math.random() * 250
})
------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&amp;display=swap">
    <link rel="stylesheet" href="style.css">
    <script defer type="module" src="main.js"></script>
    <title>Document</title>
</head>
<body>
    <div id="app">
        <canvas id="webgl-canvas"></canvas>
        <div class="hero">
          <h1>HTML</h1>
          <h2>CSS</h2>
        </div>
        <div class="buttons">
          <button type="button" id="colors-btn">
            Random colors
          </button>
        </div>
      </div>
      
</body>
</html>

-----

/* Copyright (c) 2024 by Kevin Levron (https://codepen.io/soju22/pen/MYgbRwg) */
body, html, #app {
    margin: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle, rgba(255,255,255,1) 0%, rgba(0,0,0,0.5) 200%);
  }
  
  #app {
    height: 100%;
    font-family: "Montserrat", serif;
  }
  
  .hero {
    position: relative;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  
  h1, h2 {
    margin: 0;
    padding: 0;
    color: white;
    text-transform: uppercase;
    text-shadow: 0 0 20px rgba(0, 0, 0, 1);
    line-height: 100%;
    user-select: none;
  }
  
  h1 {
    font-size: 80px;
    font-weight: 700;
  }
  
  h2 {
    font-size: 60px;
    font-weight: 500;
  }
  
  #webgl-canvas {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    overflow: hidden;
  }
  
  .buttons {
    position: fixed;
    width: 100%;
    bottom: 15px;
  
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
  }
  
  button {
    font-family: "Montserrat", serif;
    background-color: transparent;
    border-radius: 5px;
    border: transparent;
    padding: 4px 8px;
  }
