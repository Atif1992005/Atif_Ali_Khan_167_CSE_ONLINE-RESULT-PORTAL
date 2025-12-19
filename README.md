<!-- ================= HERO ================= -->
<h1 align="center">🎓 ONLINE RESULT CHECKING SYSTEM</h1>

<p align="center">

<img src="https://img.shields.io/badge/PROJECT-DBMS%20LAB-%23ff0077?style=for-the-badge">
<img src="https://img.shields.io/badge/BUILT%20WITH-PHP%20%2B%20MYSQL-%230072ff?style=for-the-badge&logo=php">
<img src="https://img.shields.io/badge/STATUS-ACTIVE-%23a6ff00?style=for-the-badge">

</p>
<p align="center">
A simple and secure result checking system.<br>
Students can view results using Roll Number & DOB.
</p>

---

<!-- COOL STRIP -->
<p align="center">
🔥 Secure Login &nbsp; | &nbsp; ⚡ Fast &nbsp; | &nbsp; 🎯 Clean UI &nbsp; | &nbsp; 💾 Reliable DB
</p>



## 🌟 FEATURES
- 🔐 Secure login (Roll No + DOB)
- 🧑‍🎓 Personal student dashboard
- 📊 Detailed results with Percentile, AIR & Rank
- 📝 Syllabus + Instructions page
- ⚙️ 2 Tables + 1 SQL View
- 🧩 Clean database structure

---

---

## 🛠 TECH STACK

<p align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,php,mysql,github,vscode,bootstrap,apache,windows" />
</p>

| Layer | Technology |
|------|------------|
| 🎨 Frontend | HTML • CSS • JS |
| ⚙️ Backend | PHP |
| 🗄 Database | MySQL + phpMyAdmin |
| 🌍 Server | XAMPP (Apache + MySQL) |

---

## 📊 SYSTEM FLOW (GRAPH)

```mermaid
flowchart TD
A[Student Login] --> B[Dashboard]
B --> C[View Result]
C --> D[Database Fetch]
D --> E[Display Marks + Rank + Status]
```
🗂 DATABASE DESIGN ------------------------------------------------------------------------------------------------------------------------------
```mermaid
graph TD
A[student_basic] -->|1:1| B[student_result]
B --> C[(students VIEW)]
```

## ⚡ QUICK SETUP

1. Copy → `C:\xampp\htdocs\result_project`
2. Start **Apache + MySQL**
3. Create DB & Import  
   - student_basic  
   - student_result  
   - students (VIEW)
4. Open → `http://localhost/result_project/`

## 📁 PROJECT STRUCTURE
```
result_project/
 ├─ login.php
 ├─ dashboard.php
 ├─ view_result.php
 ├─ result_page.php
 ├─ instructions.html
 ├─ syllabus.html
 ├─ db_connect.php
 ├─ style.css
 └─ README.md
```

## 🎯 FUTURE UPDATES
- ⭐ Admin panel
- ⭐ PDF scorecard
- ⭐ Subject marks
- ⭐ Merit list
- ⭐ Better UI

<div align="center">
<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="250" style="margin: 0 10px;">
<img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="250" style="margin: 0 10px;">
<img src="https://media.giphy.com/media/Y4ak9Ki2GZCbJxAnJD/giphy.gif" width="250" style="margin: 0 10px;">
</div>

## 🔐 SECURITY
- ✔ Session authentication
- ✔ Structured queries
- ✔ Safe data access

<!-- FOOTER --> <p align="center"> ✨ Simple • Secure • Reliable ✨<br> Made for Students | Built with ❤️ </p>
