<!--
  ╔═══════════════════════════════════════════════════════════════════════════╗
  ║                                                                           ║
  ║   ████████╗██╗  ██╗███████╗    ███████╗███╗   ██╗ ██████╗ ██╗███╗   ██╗███████╗   ║
  ║   ╚══██╔══╝██║  ██║██╔════╝   ██╔════╝████╗  ██║██╔════╝ ██║████╗  ██║██╔════╝   ║
  ║      ██║   ███████║█████╗      █████╗  ██╔██╗ ██║██║  ███╗██║██╔██╗ ██║█████╗     ║
  ║      ██║   ██╔══██║██╔══╝      ██╔══╝  ██║╚██╗██║██║   ██║██║██║╚██╗██║██╔══╝     ║
  ║      ██║   ██║  ██║███████╗    ███████╗██║ ╚████║╚██████╔╝██║██║ ╚████║███████╗   ║
  ║      ╚═╝   ╚═╝  ╚═╝╚══════╝    ╚══════╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝╚═╝  ╚═══╝╚══════╝   ║
  ║                                                                           ║
  ║              T E T R I S   D E V E L O P E R   P R O F I L E              ║
  ║                                                                           ║
  ╚═══════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    TETRIS GAME ZONE HEADER                        -->
<!-- ═══════════════════════════════════════════════════════════════ -->

```
╔══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                                                                                                                  ║
║    ███╗   ███╗██╗██████╗ ██╗  ██╗████████╗    ██╗   ██╗ ██████╗ ██╗   ██╗██╗██╗   ██╗ ██████╗ ██████╗ ██╗   ██╗     ║
║    ████╗ ████║██║██╔══██╗██║  ██║╚══██╔══╝    ╚██╗ ██╔╝██╔═══██╗██║   ██║██║██║   ██║██╔═══██╗██╔══██╗╚██╗ ██╔╝     ║
║    ██╔████╔██║██║██████╔╝███████║   ██║        ╚████╔╝ ██║   ██║██║   ██║██║██║   ██║██║   ██║██████╔╝ ╚████╔╝      ║
║    ██║╚██╔╝██║██║██╔═══╝ ██╔══██║   ██║         ╚██╔╝  ██║   ██║██║   ██║██║╚██╗ ██╔╝██║   ██║██╔══██╗  ╚██╔╝       ║
║    ██║ ╚═╝ ██║██║██║     ██║  ██║   ██║          ██║   ╚██████╔╝╚██████╔╝██║ ╚████╔╝ ╚██████╔╝██║  ██║   ██║        ║
║    ╚═╝     ╚═╝╚═╝╚═╝     ╚═╝  ╚═╝   ╚═╝          ╚═╝    ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝   ╚═════╝ ╚═╝  ╚═╝   ╚═╝        ║
║                                                                                                                                  ║
║                                    ███╗   ███╗ █████╗ ███╗   ██╗ ██████╗                                                    ║
║                                    ████╗ ████║██╔══██╗████╗  ██║██╔════╝                                                    ║
║                                    ██╔████╔██║███████║██╔██╗ ██║██║  ███╗                                                   ║
║                                    ██║╚██╔╝██║██╔══██║██║╚██╗██║██║   ██║                                                   ║
║                                    ██║ ╚═╝ ██║██║  ██║██║ ╚████║╚██████╔╝                                                   ║
║                                    ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝                                                    ║
║                                                                                                                                  ║
║                          ██████╗ ██╗   ██╗███╗   ██╗ ██████╗ ███████╗ ██████╗ ███╗   ██╗                                     ║
║                          ██╔══██╗██║   ██║████╗  ██║██╔════╝ ██╔════╝██╔═══██╗████╗  ██║                                     ║
║                          ██║  ██║██║   ██║██╔██╗ ██║██║  ███╗█████╗  ██║   ██║██╔██╗ ██║                                     ║
║                          ██║  ██║██║   ██║██║╚██╗██║██║   ██║██╔══╝  ██║   ██║██║╚██╗██║                                     ║
║                          ██████╔╝╚██████╔╝██║ ╚████║╚██████╔╝███████╗╚██████╔╝██║ ╚████║                                     ║
║                          ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝ ╚═════╝ ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝                                     ║
║                                                                                                                                  ║
║    ███████╗██████╗  █████╗ ██╗   ██╗███████╗    ███████╗ ██████╗ ██╗   ██╗███╗   ██╗ ██████╗ ███████╗██████╗ ██╗           ║
║    ██╔════╝██╔══██╗██╔══██╗██║   ██║██╔════╝    ██╔════╝██╔═══██╗██║   ██║████╗  ██║██╔════╝ ██╔════╝██╔══██╗██║           ║
║    ███████╗██████╔╝███████║██║   ██║█████╗      ███████╗██║   ██║██║   ██║██╔██╗ ██║██║  ███╗█████╗  ██████╔╝██║           ║
║    ╚════██║██╔═══╝ ██╔══██║╚██╗ ██╔╝██╔══╝      ╚════██║██║   ██║██║   ██║██║╚██╗██║██║   ██║██╔══╝  ██╔══██╗╚═╝           ║
║    ███████║██║     ██║  ██║ ╚████╔╝ ███████╗    ███████║╚██████╔╝╚██████╔╝██║ ╚████║╚██████╔╝███████╗██║  ██║██╗           ║
║    ╚══════╝╚═╝     ╚═╝  ╚═╝  ╚═══╝  ╚══════╝    ╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝           ║
║                                                                                                                                  ║
╚══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
```

<!-- Tetris Blocks Animation -->
<p align="center">
  <img src="https://readme-jokes.vercel.app/api?bg=0d1117&border=00FFF0&title_color=00FFF0&text_color=FFFFFF&code_color=FF006E&theme=cyber" />
</p>

<!-- Status Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Da%20Nang%20City-Vietnam-00FFF0?style=for-the-badge&logo=location&logoColor=00FFF0"/>
  <img src="https://img.shields.io/badge/UTC%2B7-22:53-00FF88?style=for-the-badge&logo=clock&logoColor=00FF88"/>
  <img src="https://img.shields.io/badge/Contributions-260%2Byear-FF006E?style=for-the-badge&logo=fire&logoColor=FF006E"/>
  <img src="https://img.shields.io/badge/Status-Online-00FFF0?style=for-the-badge&logo=pulse&logoColor=00FFF0"/>
</p>

---

## ⚡ About Me

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=2000&pause=1000&color=00FFF0&background=0D111700&center=true&vCenter=true&width=600&lines=Welcome+to+my+GitHub+profile!;Software+Developer+%7C+AI+%7C+Computer+Vision+%7C+Python;Building+innovative+solutions+in+Da+Nang" alt="Typing Effect" />
</p>

```python
class Developer:
    def __init__(self):
        self.name     = "Nguyễn Văn Nguyên"
        self.username = "zannguyen"
        self.location = "Da Nang City, Vietnam"
        self.timezone = "UTC +07:00"
        self.email    = "nguyen2406gl@gmail.com"
        self.facebook = "iamzannguyen"
        self.website  = "iamzannguyen.com"
        self.status   = "🟢 Online"

    def get_interests(self):
        return [
            "Computer Vision",
            "YOLO Object Detection",
            "AI & Machine Learning",
            "Traffic Flow Systems",
            "Software Defect Prediction",
            "Mobile App Development",
        ]

    def get_languages(self):
        return ["Python", "JavaScript", "HTML", "Kotlin", "Java"]

    def get_achievements(self):
        return ["Pull Shark x2", "YOLO", "260+ contributions/year"]

    def build_future(self):
        return "Always coding, always learning..."
```

---

## 📊 GitHub Statistics

<p align="center">
  <img height="165px" src="https://github-readme-stats.vercel.app/api?username=zannguyen&show_icons=true&show=reviews&theme=react&hide_border=true&bg_color=0D1117&icon_color=00FFF0&title_color=FF006E&text_color=FFFFFF&count_private=true&include_all_commits=true" />
</p>

<p align="center">
  <img height="165px" src="https://github-readme-streak-stats.herokuapp.com/?user=zannguyen&theme=react-dark&background=0D1117&border=7B2FFF&stroke=00FFF0&ring=FF006E&fire=00FFF0&currStreakLabel=00FFF0&sideNums=00FFF0&currStreakNum=FF006E&sideLabels=00FF88&dates=FFFFFF&type=stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zannguyen&layout=compact&langs_count=8&theme=react&hide_border=true&bg_color=0D1117&title_color=00FFF0&text_color=FFFFFF&ring_color=FF006E&border_color=7B2FFF" />
</p>

---

## 🛠️ Tech Stack & Skills

### 🔤 Programming Languages

<p align="center">
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=FFD43B" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=FFFFFF" />
</p>

### 🤖 AI / Computer Vision

<p align="center">
  <img src="https://img.shields.io/badge/YOLOv11-FF6B35?style=for-the-badge&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=FFFFFF" />
</p>

### 🧰 Tools & Platforms

<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=FFFFFF" />
</p>

### 📊 Skills Proficiency

```
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│  ████████████████████████████████░░░░░░░░░░░░░░  Python      85%   │
│  ████████████████████████████████████░░░░░░░░░  AI/CV       80%   │
│  ██████████████████████░░░░░░░░░░░░░░░░░░░░░░  JavaScript  65%   │
│  ██████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░  Android     60%   │
│  ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░  Kotlin      55%   │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 📦 Pinned Repositories

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=YOLOv11&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=AI-Tool-for-Software-Defect-Prediction&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=LACA_Platform_Version_2.0&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=BaberShop-App&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=AI_trafficFlow_system&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=zannguyen&repo=ExamListDTU&theme=react&bg_color=0D1117&title_color=00FFF0&icon_color=FF006E&border_color=7B2FFF&description_color=FFFFFF&show_owner=false" />
</p>

---

## 🔥 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=zannguyen&theme=react-dark&bg_color=0D1117&color=00FFF0&line=00FFF0&point=FF006E&area=true&curvature=0.5&hide_border=false&font=Fira+Code" />
</p>

---

## 🎯 Skills Distribution

```
╭─────────────────────────────────────────────────────────────────╮
│                                                                 │
│    ⚡ Contribution Type Distribution                            │
│                                                                 │
│        Commits ████████████████████████████████░░░░░░░  80%   │
│        PRs    █████████████░░░░░░░░░░░░░░░░░░░░░░░░░  19%   │
│        Review ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   1%   │
│        Issues ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   0%   │
│                                                                 │
╰─────────────────────────────────────────────────────────────────╯
```

---

## 💬 Contact & Connect

<p align="center">
  <a href="https://github.com/zannguyen" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=FFFFFF&style=flat-square" />
  </a>
  <a href="https://facebook.com/iamzannguyen" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=FFFFFF&style=flat-square" />
  </a>
  <a href="mailto:nguyen2406gl@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=FFFFFF&style=flat-square" />
  </a>
  <a href="https://iamzannguyen.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-00FFF0?style=for-the-badge&logo=world&logoColor=0D1117&style=flat-square" />
  </a>
</p>

---

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║              ⚡  KẾT NỐI VỚI TÔI  ⚡                            ║
║                                                                   ║
║   📧  Email     →   nguyen2406gl@gmail.com                        ║
║   💻  GitHub    →   github.com/zannguyen                          ║
║   💬  Facebook  →   facebook.com/iamzannguyen                     ║
║   🌐  Website   →   iamzannguyen.com                              ║
║   📍  Location  →   Da Nang City, Vietnam 🏝️                    ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## 🔮 Visitor Count

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zannguyen&color=00FFF0&style=for-the-badge&logo=eye" />
</p>

---

<p align="center">

```
 ██████╗ ██████╗ ███╗   ██╗ ██████╗ ██████╗  ██████╗ ██╗     ██╗████████╗██╗   ██╗
██╔════╝██╔═══██╗████╗  ██║██╔════╝ ██╔══██╗██╔═══██╗██║     ██║╚══██╔══╝╚██╗ ██╔╝
██║     ██║   ██║██╔██╗ ██║██║  ███╗██████╔╝██║   ██║██║     ██║   ██║    ╚████╔╝
██║     ██║   ██║██║╚██╗██║██║   ██║██╔══██╗██║   ██║██║     ██║   ██║     ╚██╔╝
╚██████╗╚██████╔╝██║ ╚████║╚██████╔╝██║  ██║╚██████╔╝███████╗██║   ██║      ██║
 ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝   ╚═╝      ╚═╝
```

**Made with ❤️ in Da Nang City, Vietnam**

**© 2023 - 2026 · All systems normal** ⚡

</p>
</div>

<!--
  ╔═══════════════════════════════════════════════════════════════════════════╗
  ║  PROFILE GENERATED: March 2026                                           ║
  ║  THEME: Cyberpunk Tetris Developer Profile                               ║
  ║  CONTRIBUTIONS: 260+ in the last year                                    ║
  ║  PRIMARY LANGUAGE: Python                                                ║
  ╚═══════════════════════════════════════════════════════════════════════════╝
-->
