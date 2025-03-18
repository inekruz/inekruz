[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Computer+science+student)](https://git.io/typing-svg)

Skip to content
DEV Community
Find related posts...
Работает на  Algolia
Войти
Создать учетную запись

3
Перейти к комментариям

2
Спасать

Поддержка

Ryoichi Homma
Ryoichi Homma
Posted on 30 июн. 2024 г. • Edited on 6 июл. 2024 г.


2
How to Customize GitHub Profile: Part 4
#
github
#
githubprofile
#
githubportfolio
#
developer
Welcome back to the fourth part of my series on customizing your GitHub profile! In this article, we'll delve into the fun and interactive contribution animation. This animation not only adds a unique flair to your profile but also visually represents your contributions in an engaging way.
Part 1 | Part 2 | Part 3 | Part 5

Example ImageExample Image2

Add Snake Contribution Animation and Why
The snake contribution animation is a creative way to showcase your GitHub activity. It adds a playful element to your profile while highlighting your commitment and consistency in contributing to open source projects.

Engagement: The animation captures the attention of visitors.
Interactivity: It provides a dynamic element to your otherwise static profile.
Visual Appeal: It makes your contribution graph more interesting and visually appealing.
Настройка анимации вклада змейки:
Чтобы добавить анимацию вклада змейки в профиль GitHub, можно использовать GitHub Actions и готовый скрипт, который создает анимацию. Вот как вы можете это настроить:

Шаг 1: Создание рабочего процесса GitHub Actions
Перейдите в репозиторий GitHub.
Перейдите на вкладку «Действия».
Нажмите «Новый рабочий процесс», затем настройте рабочий процесс самостоятельно.
Шаг 2: Добавьте код рабочего процесса
Чтобы добавить код рабочего процесса в файл рабочего процесса (например, github/workflows/snakeAnime.yml), обратитесь к репозиторию Platane.

Шаг 3: Добавьте анимацию в файл README.md
После того как рабочий процесс GitHub Actions настроен и успешно запущен, вы можете добавить созданный файл SVG в файл README.md. Вот как это сделать:

<!-- CONTRIBUTIONS -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Animation" src="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake.svg">
</picture>
Настройка анимации вклада змейки
Внешний вид анимации можно настроить, настроив цвета и расписание в файле рабочего процесса. Вот несколько вариантов настройки:

Расписание: Измените выражение cron, чтобы настроить частоту обновления анимации.
Знамя: Измените исходные URL-адреса, чтобы использовать другие цветовые схемы.
Заключение
В этой части мы рассмотрели, как добавить анимацию вклада змейки в ваш профиль GitHub. Этот забавный и интерактивный элемент не только подчеркивает ваш вклад, но и повышает визуальную привлекательность вашего профиля. Оставайтесь с нами, чтобы не пропустить последнюю часть, в которой мы расскажем о статистике GitHub и других полезных метриках.

Как всегда, не стесняйтесь задавать любые вопросы или делиться своими профилями на GitHub в комментариях ниже. Давайте объединяться и расти вместе🌱

Удачного программирования! 💻

Ссылка
Хранилище Платане

Другие детали
Часть 1 | Часть 2 | Часть 3 | Часть 5

profile
Прогресс
Способствовало

Image of Progress.com

Вебинар: 1 час конкурса по дизайн-системе
Learn how to to speed up design system creation using the KendoReact UI library and ThemeBuilder.

Save your seat

Top comments (3)
Subscribe
pic
Add to the discussion
 
 
alberto_fernandez_2dcd84a profile image
Alberto Fernandez
•
29 авг. 24 г.

wonderful


2
 likes
Like
Reply
 
 
ryoichihomma profile image
Ryoichi Homma 
•
17 окт. 24 г.

thank you Alberto!


Like
Reply
 
 
alberto_fernandez_2dcd84a profile image
Alberto Fernandez
•
4 дек. 24 г.

You are welcome.


1
 like
Like
Reply
Code of Conduct • Report abuse
profile
AWS
Promoted

AWS Q Developer image

Your AI Code Assistant
Automate your code reviews. Catch bugs before your coworkers. Fix security issues in your code. Built to handle large projects, Amazon Q Developer works alongside you from idea to production code.

Get started free in your IDE

Read next
mikeyoung44 profile image
New AI Model Breaks Records in Lip-Reading and Speech Recognition by Adapting to Signal Quality
Mike Young - Mar 12

mikeyoung44 profile image
Robot Assistant Masters 10 Common Household Tasks Using Whole-Body Coordination
Mike Young - Mar 12

mikeyoung44 profile image
AI Privacy Breakthrough: New Method Boosts Federated Learning Without Sharing Private Data
Mike Young - Mar 12

mikeyoung44 profile image
New Benchmark Shows Claude 3 Outperforms GPT-4 on Real-World AI Instructions
Mike Young - Mar 12


Ryoichi Homma
Follow
Aspiring Software Engineer/Web Developer, with experience in AI LLM evaluation | Seeking new roles in Canada | React, TypeScript, JavaScript, Tailwind CSS, Framer Motion | Expanding into MERN stack
Location
The Thompson Okanagan, British Columbia, Canada
Education
Thompson Rivers University
Pronouns
he/him/his
Work
AI (Language Model) Trainer at Outlier
Joined
24 мая 2024 г.
More from Ryoichi Homma
Git - Useful Commands
#git #versioncontrol #gitcommands #github
JS Basic - Modern vs. Traditional Ways
#javascript #linkedinlearning #jstips #developer
How to Customize GitHub Profile: Part 5
#github #githubprofile #githubportfolio #developer
profile
Прогресс
Способствовало

Image of Progress.com

Вебинар: 1 час конкурса по дизайн-системе
Узнайте, как ускорить создание дизайн-системы с помощью библиотеки KendoReact UI и ThemeBuilder.

Сохраните свое место

<!-- CONTRIBUTIONS -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inekruz/inekruz/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/inekruz/inekruz/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Animation" src="https://raw.githubusercontent.com/inekruz/inekruz/output/github-contribution-grid-snake.svg">
</picture>

## 🌐 Socials:
[![TELEGRAM](https://i.imgur.com/rgGu9u1.png)](https://t.me/inekruz) 

# 💻 Tech Stack:
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=plastic&logo=vercel&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=plastic&logo=amazon-aws&logoColor=white) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=plastic&logo=gnu-bash&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=plastic&logo=PyTorch&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=plastic&logo=flask&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=plastic&logo=apache&logoColor=white) ![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=plastic&logo=Amazon%20DynamoDB&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=plastic&logo=mysql&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=plastic&logo=TensorFlow&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=plastic&logo=django&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=plastic&logo=Raspberry-Pi) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=plastic&logo=docker&logoColor=white) ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=plastic&logo=cisco&logoColor=black) ![Pi-Hole](https://img.shields.io/badge/pihole-%2396060C.svg?style=plastic&logo=pi-hole&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=plastic&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=plastic&logo=nginx&logoColor=white) ![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=plastic&logo=yarn&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=plastic&logo=npm&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=plastic&logo=next.js&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=plastic&logo=javascript&logoColor=%23F7DF1E) ![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=plastic&logo=graphql&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=plastic&logo=microsoft%20sql%20server&logoColor=white)![GDB](https://img.shields.io/badge/GDB-%23004D7A?style=flat)![Langchain](https://img.shields.io/badge/Langchain-%23FFD700?style=flat)![OSINT](https://img.shields.io/badge/OSINT-%23FF4500?style=flat)![Impacket](https://img.shields.io/badge/Impacket-%23008B8B?style=flat)![Active Directory](https://img.shields.io/badge/Active%20Directory-%23007396?style=flat&logo=active-directory&logoColor=white)![Red Teaming](https://img.shields.io/badge/Red%20Teaming-%23FF0000?style=flat)![Blue Teaming](https://img.shields.io/badge/Blue%20Teaming-%230000FF?style=flat)![Snort](https://img.shields.io/badge/Snort-%23FF4500?style=flat)![IOS Cisco](https://img.shields.io/badge/IOS%20Cisco-%230049FD?style=flat&logo=cisco&logoColor=white)![Malware](https://img.shields.io/badge/Malware-%23FF0000?style=flat)![Nmap](https://img.shields.io/badge/Nmap-%23000000?style=flat&logo=nmap&logoColor=white)![Metasploit](https://img.shields.io/badge/Metasploit-%23FF0000?style=flat)![ExploitDB](https://img.shields.io/badge/ExploitDB-%23FFFFFF?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-%23FFA500?style=flat)
![Amplify](https://img.shields.io/badge/Amplify-%23FF00FF?style=flat)
![Nuclei](https://img.shields.io/badge/Nuclei-%23FFFF00?style=flat)
![Katana](https://img.shields.io/badge/Katana-%23000000?style=flat)
![LLMs](https://img.shields.io/badge/LLMs-%23FFD700?style=flat)
![Finetunning](https://img.shields.io/badge/Finetunning-%23FF8C00?style=flat)
# 📊 GitHub Stats:
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=inekruz&theme=solarized_dark)

![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=inekruz&theme=solarized_dark) ![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=inekruz&theme=solarized_dark)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=inekruz&theme=radical&no-frame=false&no-bg=true&margin-w=4)

---
[![](https://visitcount.itsvg.in/api?id=inekruz&icon=0&color=0)](https://visitcount.itsvg.in)
