
# Check that this is your GitHub profile repository
if (!(Test-Path ".git") -or !(Test-Path "README.md")) {
    Write-Host "ERROR: Open the SinchanaS18 profile repository folder first." -ForegroundColor Red
    exit
}

# Back up the current README
Copy-Item README.md README-backup.md -Force

# Create the updated README
@'
# 💫 About Me:
🔭 **Currently working on:** Building SafeRoute AI, an AI-powered women’s safety and emergency assistance system.

🤝 **Looking to collaborate on:** Java-based applications, Backend Development and Open-Source Projects.

🧠 **Exploring:** Data Structures & Algorithms, Problem Solving and Backend Engineering.

🌱 **Currently learning:** Java, Spring Boot, REST APIs, DBMS and SQL.

💬 **Ask me about:** Java, DSA, MySQL and Web Development.

⚡ **Fun fact:** I believe consistency beats perfection, and every problem solved makes me a better developer.

---

# 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sinchana-s-582a21397)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Sinchanaju18@gmail.com)

---

# 💻 Tech Stack:

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=ApacheMaven&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=tomcat&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-white?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-181717?style=for-the-badge&logo=gitlab&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=Canva&logoColor=white)
![Sketch](https://img.shields.io/badge/Sketch-F7B500?style=for-the-badge&logo=sketch&logoColor=black)

### Additional Technologies:
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![Wokwi](https://img.shields.io/badge/Wokwi-4A90E2?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![OSRM](https://img.shields.io/badge/OSRM-4B8BBE?style=for-the-badge)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=openstreetmap&logoColor=white)

---

# 📊 GitHub Stats:

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=SinchanaS18&show_icons=true&theme=dark&hide_border=false" height="180" alt="GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=SinchanaS18&layout=compact&theme=dark&hide_border=false" height="180" alt="Most Used Languages" />
</p>

<p align="center">
  <img src="./profile/streak.svg" alt="GitHub Streak" />
</p>

---

# 👀 Profile Views:

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SinchanaS18&label=PROFILE+VIEWS&color=0e75b6&style=flat" alt="Profile Views" />
</p>

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
'@ | Set-Content -Path README.md -Encoding utf8

# Create the GitHub Actions workflow folder
New-Item -ItemType Directory -Force ".github/workflows" | Out-Null
New-Item -ItemType Directory -Force "profile" | Out-Null

# Create the automatic streak image workflow
@'
name: Update GitHub Streak Stats

on:
  schedule:
    - cron: "0 3 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout repository
        uses: actions/checkout@v7

      - name: Generate streak stats
        uses: DenverCoder1/github-readme-streak-stats@v1
        with:
          options: user=${{ github.repository_owner }}&theme=dark&hide_border=true&disable_animations=true
          path: profile/streak.svg

      - name: Commit streak stats
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add profile/streak.svg
          git commit -m "Update GitHub streak stats" || exit 0
          git push
'@ | Set-Content -Path ".github/workflows/streak-stats.yml" -Encoding utf8

# Review and push
git status
git add README.md .github/workflows/streak-stats.yml
git commit -m "Update GitHub profile README and streak workflow"
git push origin main

Write-Host "Profile README and streak workflow pushed successfully!" -ForegroundColor Green
