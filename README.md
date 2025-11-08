# ✨ Who am I?

I'm **Prince Korankye**, a passionate **Web Developer** and soon-to-be **Computer Science student**.  
I love building creative and efficient web applications using modern tools and technologies.  
I’m currently deepening my **JavaScript** skills while creating projects that solve real-world problems.

---

## 🚀 What I Do

🔥 Frontend Web Development  
🧠 Learning Backend & Fullstack concepts  
💡 Building real-world projects  
⚙️ Exploring new frameworks and tools  

---

## 💻 Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🌐 Let's Connect


📫 **Email:** asamoahestella500@gmail.com
💬 **GitHub:** [PrinceKorankye](https://github.com/AKONNNO)  

name: Generate contribution snake

on:
  schedule:
    - cron: '0 0 */1 * *'   # runs daily (change as you like)
  workflow_dispatch:        # allows manual runs

permissions:
  contents: write           # important: allow the action to write files to the repo

jobs:
  build-snake:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: AKONNNO
          outputs: |
            output/github-contribution-grid-snake.svg?palette=github-dark&color_snake=%2300FF00


🌍 **Portfolio:** Coming soon!  

---

⭐ *“Learning never stops — every line of code counts.”*
