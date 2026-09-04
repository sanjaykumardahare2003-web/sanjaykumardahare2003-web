<div align="center">

# SANJAY KUMAR DAHARE

### Computer Science Student · Full-Stack Developer

Building practical web applications with modern technologies.

<br>

<a href="https://github.com/sanjaykumardahare2003-web">
  <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<a href="https://github.com/sanjaykumardahare2003-web?tab=repositories">
  <img src="https://img.shields.io/badge/Projects-Explore-0969DA?style=for-the-badge&logo=github&logoColor=white">
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1000&color=0969DA&center=true&vCenter=true&width=650&lines=Building+real-world+applications;React+%7C+TypeScript+%7C+Node.js;PostgreSQL+%7C+REST+APIs;Learn+%E2%86%92+Build+%E2%86%92+Ship" />

</div>

---

## About

I'm a Computer Science student interested in **full-stack development, backend systems, databases, and cloud deployment**.

I enjoy taking an idea from an initial concept to a working application — designing the interface, building the backend, connecting the database, testing the system, and deploying it.

My current focus is on becoming a stronger **full-stack developer** by building real-world projects and improving my understanding of software architecture.

---

# Tech Stack

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,tailwind,vite" />
</p>

### Backend & APIs

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express,php" />
</p>

### Databases

<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql" />
</p>

### Tools & Platforms

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,postman,vercel" />
</p>

---

# Featured Project

## Mehta Paints & Hardware

**A full-stack digital platform developed for a real-world paint and hardware business.**

The project combines customer-facing features with business management functionality.

### Highlights

- Product catalogue and product management
- Paint shade selection
- Admin dashboard
- Authentication and protected administration
- Order and enquiry management
- WhatsApp-based customer communication
- Business management features
- Responsive user interface
- Progressive Web App support
- Cloud deployment

### Architecture

```mermaid
flowchart LR

    Customer["Customer"]

    Frontend["React Frontend<br/>Vite + Tailwind"]

    API["REST API"]

    Backend["Node.js + Express"]

    Database[("PostgreSQL<br/>Drizzle ORM")]

    Admin["Admin Dashboard"]

    Customer --> Frontend
    Frontend --> API
    API --> Backend
    Backend --> Database
    Backend --> Admin
