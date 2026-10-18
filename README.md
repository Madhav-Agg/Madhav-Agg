<div align="center">

<a href="https://github.com/Madhav-Agg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1200&color=58A6FF&center=true&vCenter=true&width=760&height=60&lines=Madhav+Aggarwal;Java+%26+Backend+Development;Spring+Boot+%C2%B7+REST+APIs+%C2%B7+SQL" alt="Madhav Aggarwal - Java and Backend Development" />
</a>

**B.Tech student building backend projects with Java and Spring Boot, practicing DSA, and looking for an SDE / backend internship.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhav-aggarwal-a90805374/)
[![LeetCode](https://img.shields.io/badge/LeetCode-1F2937?style=for-the-badge&logo=leetcode&logoColor=FFA116)](https://leetcode.com/u/Madhav_Aggarwal/)
[![Portfolio](https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=githubpages&logoColor=58A6FF)](https://madhav-agg.github.io/MY-PORTFOLIO/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aggarwalmadhav44@gmail.com)

</div>

---

## About

I'm a B.Tech student at Chandigarh Engineering College, CGC Landran (graduating 2028). I started with front-end web projects and have moved toward backend development: building REST APIs with Spring Boot, working with relational databases, and getting comfortable with the fundamentals behind them.

I practice data structures and algorithms in Java on LeetCode and build small, complete projects to learn how the pieces of a backend fit together.

```java
public class Madhav {
    String education   = "B.Tech, Chandigarh Engineering College, CGC Landran (2028)";
    String[] focus     = {"Java", "Spring Boot", "REST APIs", "SQL"};
    String practice    = "DSA in Java on LeetCode";
    String lookingFor  = "SDE / Backend Engineering internship";
}
```

---

## Tech Stack

**Languages** &nbsp;
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend** &nbsp;
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-0D1117?style=flat-square&logoColor=58A6FF)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

**Databases** &nbsp;
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![H2](https://img.shields.io/badge/H2-0D1117?style=flat-square&logoColor=58A6FF)
<!-- PostgreSQL: uncomment once it appears in one of your projects
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
-->

**Tools** &nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<sub>Earlier web projects also used HTML, CSS, JavaScript, Firebase and Supabase.</sub>

---

## Featured Projects

### Complaint Tracker
A complaint-management web app where users raise tickets and admins assign them and move them through **Open → In Progress → Resolved**.

- Role-based access (Admin / User) with Spring Security and BCrypt password hashing
- Status transitions enforced in the service layer: no skipping steps, no going backwards
- Dashboard with ticket counts, plus filtering by status and category
- REST endpoints alongside the Thymeleaf pages; H2 for local development, MySQL for production profile
- Includes a Dockerfile

**Stack:** Java · Spring Boot 3 · Spring Security · Spring MVC · Spring Data JPA · Hibernate · Thymeleaf · H2 / MySQL · Maven · Docker

[Repository](https://github.com/Madhav-Agg/Complaint-Tracker) &nbsp;·&nbsp; [Live demo](https://complaint-tracker-5d85.onrender.com)

---

### Inventory Management API
A REST API for managing products and stock levels.

- CRUD for products, with search by name and filtering by category
- Stock increase/decrease endpoint that rejects updates that would make stock negative
- Low-stock endpoint with a configurable threshold
- Request validation, duplicate-SKU detection (`409 Conflict`) and structured JSON error responses
- Layered structure (controller → service → repository) and a Postman collection included in the repo

**Stack:** Java 17 · Spring Boot 3 · Spring Data JPA · Hibernate · MySQL · Bean Validation · Maven · Postman

[Repository](https://github.com/Madhav-Agg/Inventory-Management-API)

---

### NabhaCare Connect
A telemedicine web app with separate doctor and patient panels, built with a JavaScript/TypeScript stack.

- Phone number + one-time-code sign-in, JWT sessions, and authorization enforced on the server for each role
- Appointment booking, health records, and WebRTC video consultation
- Interface available in English, Hindi and Punjabi
- Optional integrations (SMS, AI symptom checker) fail with clear errors when not configured

**Stack:** React · TypeScript · Vite · Node.js · Express · Socket.IO · SQLite

[Repository](https://github.com/Madhav-Agg/NabhaCareConnect)

---

### Also: ThisIsMagma 3D Clone
A front-end clone of the ThisIsMagma website, built to practice web animation and interactive visuals. &nbsp; [Live demo](https://madhav-agg.github.io/This-Is-Magma-Clone-3d/) &nbsp;·&nbsp; [Repository](https://github.com/Madhav-Agg/This-Is-Magma-Clone-3d)

---

## Achievements

- **First place**, National Science Day Competition at CEC
- **Smart India Hackathon**, internal round finalist (twice)
- **100+ problems solved** on [LeetCode](https://leetcode.com/u/Madhav_Aggarwal/), mostly in Java
- **Web Development and Community Engagement Intern**, Tensorik (June to September 2025)

---

## Current Focus

<!-- Edit this list as your focus changes -->
- Improving Java and DSA skills
- Building backend applications with Spring Boot
- Designing REST APIs and working with relational databases
- Building practical projects to strengthen software engineering fundamentals

---

## GitHub & Practice

<div align="center">

<img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Madhav-Agg&show_icons=true&theme=github_dark&hide_border=true&count_private=false" />
<img height="165" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Madhav-Agg&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />

<img height="165" alt="LeetCode stats" src="https://leetcard.jacoblin.cool/Madhav_Aggarwal?theme=dark&font=Fira%20Code&ext=heatmap" />

<sub>Language usage is a rough indicator based on repository contents, not a measure of skill.</sub>

</div>

---

<div align="center">

[LinkedIn](https://www.linkedin.com/in/madhav-aggarwal-a90805374/) &nbsp;·&nbsp; [GitHub](https://github.com/Madhav-Agg) &nbsp;·&nbsp; [LeetCode](https://leetcode.com/u/Madhav_Aggarwal/) &nbsp;·&nbsp; [Portfolio](https://madhav-agg.github.io/MY-PORTFOLIO/) &nbsp;·&nbsp; [aggarwalmadhav44@gmail.com](mailto:aggarwalmadhav44@gmail.com)

</div>
