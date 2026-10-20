# ITUE301: Advance Web Development Framework (AWDF) - Lab Practicals

## Student Information
- **Name:** Hitansh Parikh
- **Student ID:** 23CS054
- **Email:** [23cs054@charusat.edu.in](mailto:23cs054@charusat.edu.in)
- **Semester:** 5th Semester
- **Program:** B.Tech - Computer Science & Engineering
- **Department:** Computer Science and Engineering, CSPIT
- **University:** Charotar University of Science and Technology (CHARUSAT)
- **Academic Year:** 2026–2027

---

## Practicals Overview

| Practical | Title & Focus Area | Tech Stack | Code Link | Report (.docx) |
| :---: | :--- | :--- | :---: | :---: |
| **01** | Setup React environment with Vite & Student Portfolio | React / Node.js / Express / MongoDB / Docker | [practical-01](./practical-01) | [Practical 1 Report](./docs/23CS054_Practical_1.docx) |
| **02** | Modular UI components, Navbar styling & theme toggle | React / Node.js / Express / MongoDB / Docker | [practical-02](./practical-02) | [Practical 2 Report](./docs/23CS054_Practical_2.docx) |
| **03** | GitHub API integration & live repository explorer | React / Node.js / Express / MongoDB / Docker | [practical-03](./practical-03) | [Practical 3 Report](./docs/23CS054_Practical_3.docx) |
| **04** | RESTful Task Manager backend with Express.js | React / Node.js / Express / MongoDB / Docker | [practical-04](./practical-04) | [Practical 4 Report](./docs/23CS054_Practical_4.docx) |
| **05** | Task Manager API with MongoDB & Mongoose ORM | React / Node.js / Express / MongoDB / Docker | [practical-05](./practical-05) | [Practical 5 Report](./docs/23CS054_Practical_5.docx) |
| **06** | Full-Stack Task Manager integration (React + Express) | React / Node.js / Express / MongoDB / Docker | [practical-06](./practical-06) | [Practical 6 Report](./docs/23CS054_Practical_6.docx) |
| **07** | User Authentication & JWT authorization middleware | React / Node.js / Express / MongoDB / Docker | [practical-07](./practical-07) | [Practical 7 Report](./docs/23CS054_Practical_7.docx) |
| **08** | State management with React Context & Redux Toolkit | React / Node.js / Express / MongoDB / Docker | [practical-08](./practical-08) | [Practical 8 Report](./docs/23CS054_Practical_8.docx) |
| **09** | Advanced filtering, sorting & pagination in Task Manager | React / Node.js / Express / MongoDB / Docker | [practical-09](./practical-09) | [Practical 9 Report](./docs/23CS054_Practical_9.docx) |
| **10** | Real-time updates with Server-Sent Events (SSE) | React / Node.js / Express / MongoDB / Docker | [practical-10](./practical-10) | [Practical 10 Report](./docs/23CS054_Practical_10.docx) |
| **11** | Containerization with Docker & Docker Compose orchestration | React / Node.js / Express / MongoDB / Docker | [practical-11](./practical-11) | [Practical 11 Report](./docs/23CS054_Practical_11.docx) |
| **12** | Automated testing & GitHub Actions CI/CD Pipeline | React / Node.js / Express / MongoDB / Docker | [practical-12](./practical-12) | [Practical 12 Report](./docs/23CS054_Practical_12.docx) |
| **13** | Production deployment, health monitoring & AI service integration | React / Node.js / Express / MongoDB / Docker | [practical-13](./practical-13) | [Practical 13 Report](./docs/23CS054_Practical_13.docx) |

---

## Project Structure
```
23CS054_AWDF/
├── docs/                               # Lab Report Word documents for all 13 practicals
│   ├── 23CS054_Practical_1.docx
│   ├── ...
│   └── 23CS054_Practical_13.docx
├── practical-01/                       # Practical 01: Setup React environment & Portfolio
├── practical-02/                       # Practical 02: Modular UI components & theme toggle
├── practical-03/                       # Practical 03: GitHub API integration & repo explorer
├── practical-04/                       # Practical 04: RESTful Task Manager backend (Express)
├── practical-05/                       # Practical 05: Task Manager API with MongoDB & Mongoose
├── practical-06/                       # Practical 06: Full-Stack React + Express + MongoDB
├── practical-07/                       # Practical 07: Authentication & JWT middleware
├── practical-08/                       # Practical 08: React Context & Redux Toolkit
├── practical-09/                       # Practical 09: Filtering, sorting & pagination
├── practical-10/                       # Practical 10: Real-time updates with SSE
├── practical-11/                       # Practical 11: Docker & Docker Compose orchestration
├── practical-12/                       # Practical 12: Automated testing & CI/CD pipeline
├── practical-13/                       # Practical 13: Deployment, monitoring & AI service
└── README.md                           # Master Lab Manual and documentation
```

---

## Instructions to Run Any Practical Locally

### For Frontend Practicals (Practicals 1–3):
```bash
cd practical-XX
npm install
npm run dev
```

### For Backend Practicals (Practicals 4–5):
```bash
cd practical-XX
npm install
npm run dev # or npm start
```

### For Full-Stack Practicals (Practicals 6–10, 13):
1. **Start the Express API Server:**
   ```bash
   cd practical-XX/server
   npm install
   npm run dev
   ```
2. **Start the React Client:**
   ```bash
   cd practical-XX/client
   npm install
   npm run dev
   ```

### For Dockerized Practicals (Practicals 11–13):
```bash
cd practical-XX
docker-compose up --build
```

---
*Created by Hitansh Parikh (23CS054) for AWDF Laboratory (ITUE301).*
