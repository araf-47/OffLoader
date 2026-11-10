<div align="center">

![OffLoader Logo](assets/Logo/offloader-icon.png#gh-light-mode-only)
![OffLoader Logo](assets/Logo/offloader-icon-dark.png#gh-dark-mode-only)

<br/>

# OffLoader 📝

[![Status: In Development](https://img.shields.io/badge/Status-In%20Development-FFB300?style=for-the-badge&logo=git&logoColor=white)](#-core-features-in-development)
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

<br/>

**OffLoader** is a full-stack note-taking and task-tracking web application. It is designed to help users offload mental clutter by capturing freeform thoughts, structured checklists, and daily tasks in one seamless workspace.

</div>

---

## 🚀 Tech Stack

### Frontend
- **Framework:** Angular &nbsp; [![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)](https://angular.dev/)
- **Styling:** CSS / SCSS &nbsp; [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white)](https://sass-lang.com/)
- **State & HTTP:** Angular Services & HttpClient &nbsp; [![HttpClient](https://img.shields.io/badge/HttpClient-DD0031?style=flat-square&logo=angular&logoColor=white)](https://angular.dev/guide/http)

### Backend
- **Language:** Java &nbsp; [![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com/)
- **Framework:** Spring Boot &nbsp; [![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
- **API Architecture:** RESTful APIs &nbsp; [![RESTful APIs](https://img.shields.io/badge/RESTful-APIs-009688?style=flat-square&logo=postman&logoColor=white)](https://restfulapi.net/)
- **ORM:** Spring Data JPA (Hibernate) &nbsp; [![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)](https://hibernate.org/)

### Database
- **Database Management System:** PostgreSQL &nbsp; [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

---

## 🏗 System Architecture

OffLoader follows a standard three-tier architecture:

```mermaid
flowchart TD
    A["[ Angular Frontend ]"] -->|"HTTP / REST API JSON"| B["[ Spring Boot Backend Service ]"]
    B -->|"Spring Data JPA / SQL"| C["[ PostgreSQL Database ]"]
```

---

## 📌 Core Features (In Development)

- [ ] **Dual-Type Notes:** Support for both rich text notes and interactive checklist items.
- [ ] **Dynamic Checklist Management:** Real-time checking, unchecking, and ordering of todo items.
- [ ] **Labeling & Tagging:** Organize notes using custom labels and many-to-many tag relationships.
- [ ] **Color Coding & Organization:** Customize note card colors and pin priority notes to the top.
- [ ] **Archive & Trash Management:** Archive completed tasks or move items to trash with soft-delete capabilities.

---

## 🎯 Future Goals

- [ ] **User Authentication & Accounts:** Implement secure multi-user sign-up, login, and JWT-based session management.
- [ ] **Cloud Synchronization:** Sync notes and checklists seamlessly to PostgreSQL, accessible from any browser.
- [ ] **Dedicated Android App:** Build a mobile companion app with full web feature parity plus smartphone-specific capabilities (e.g., widgets, offline sync, push notifications).
