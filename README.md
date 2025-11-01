<!-- 🌍 Animated Header -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3000&pause=800&color=FF69B4&center=true&vCenter=true&width=800&lines=🌐+F1+Internships+Website;Helping+International+Students+with+Internship+Search;Built+with+React%2C+Node.js%2C+and+MySQL+💻✨" alt="Typing Animation" />
</p>

---

# 🌐 F1 Internships Website

**F1 Internships Website** is a full-stack web application built to help **international (F1 visa) students** quickly find internships and jobs that offer **visa sponsorship (CPT/OPT)**.
It bridges the gap between global talent and U.S. employers through a searchable, accessible, and scalable platform.

Built using **React + Vite** for the frontend and **Node.js + Express + MySQL** for the backend, this project combines clean UI design, dynamic database queries, and RESTful APIs for seamless interaction between data and user experience.

https://github.com/user-attachments/assets/92e51a15-9393-46ee-be7e-c8435933d61a

---

## 💡 Motivation

As international students ourselves, we noticed that internship search platforms rarely indicate whether a company **sponsors visas** — forcing students to waste hours applying to positions they aren’t eligible for.

This project solves that problem by centralizing and displaying **CPT/OPT-friendly internship listings**, helping students find legitimate opportunities **faster and smarter**.
Our tagline: *“Finding internships faster than your visa expires.”* 🕒

---

## 🌟 Features

* 🔍 **Search Internships** – Filter by title, company, or keyword
* 📨 **Direct Apply Links** – Instant access to external application portals
* 📊 **Dynamic Data Retrieval** – Internships fetched in real time from a MySQL database
* 📱 **Responsive Design** – Fully optimized for both desktop and mobile users
* 🧭 **Routing System** – Built using React Router for smooth page transitions
* ⚙️ **Scalable Backend** – RESTful Express.js API serving filtered internship data

<p align="center">
  <img width="900" alt="F1 Internships Website" src="https://github.com/user-attachments/assets/acf2d842-fa50-4808-aeb8-9de98815eac8" />
</p>

---

## ⚙️ Architecture Overview

| Layer                   | Technologies                                       | Description                                                     |
| ----------------------- | -------------------------------------------------- | --------------------------------------------------------------- |
| 🎨 **Frontend**         | React, Vite, HTML5, CSS3, JavaScript, React Router | Renders internship listings, search filters, and responsive UI  |
| ⚙️ **Backend**          | Node.js, Express.js                                | Provides RESTful endpoints for internship queries and filtering |
| 💾 **Database**         | MySQL                                              | Stores internship data (company, role, eligibility, location)   |
| 🌍 **Hosting (future)** | Render / AWS                                       | Scalable deployment and CI/CD pipeline integration planned      |

---

## 🧠 Technical Highlights

* Built a **normalized MySQL schema** to handle up to 10,000 internship listings efficiently
* Implemented **server-side filtering** for optimized search queries
* Integrated **REST API endpoints** for CRUD operations (Create, Read, Update, Delete)
* Applied **frontend modularization** with reusable React components (Cards, SearchBar, Filters)
* Designed with **accessibility standards** in mind (WCAG-friendly colors and structure)
* Developed and tested under **Agile-style sprints** with a clear backlog and milestones

---

## 🧩 Project Structure

### **Frontend**

Located in the `Frontend/` directory
Built using React (Vite).

Key files:

* `src/pages/Home.jsx` – Displays internship cards
* `src/pages/Cards.jsx` – Renders individual internship listings
* `src/pages/Data.jsx` – Contains sample internship data for testing
* `vite.config.js` – Vite configuration

### **Backend**

Located in the `Backend/` directory
Built using Express.js and MySQL.

Key files:

* `server.js` – Express server connecting to the MySQL database
* `.env` – Contains database credentials and configuration variables

---

## 🚀 Installation & Setup

### Prerequisites

* Node.js (v16 or later)
* MySQL

### Steps

```bash
# Clone the repository
git clone <repository-url>
cd F1_Internships_Website

# Install backend dependencies
cd Backend
npm install

# Install frontend dependencies
cd ../Frontend
npm install
```

### Configure Environment Variables

Create a `.env` file inside `Backend/` with the following:

```
HOST=<your-database-host>
USER=<your-database-username>
PASSWORD=<your-database-password>
DATABASE=<your-database-name>
```

Ensure your MySQL database contains a table named `internships_opt_cpt` with appropriate columns for:
`id`, `company`, `title`, `location`, `visa_eligibility`, `apply_link`

---

## 🧭 Running the Application

```bash
# Start backend server
cd Backend
node server.js

# Start frontend server
cd ../Frontend
npm run dev
```

Access the website at 👉 [http://localhost:5173](http://localhost:5173)

---

## 🧰 Scripts

| Command          | Description                     |
| ---------------- | ------------------------------- |
| `npm run dev`    | Run frontend development server |
| `node server.js` | Start Express backend server    |

---

## 🧱 Technologies Used

**Frontend:** React, Vite, React Router, CSS, HTML, JavaScript
**Backend:** Express.js, Node.js, MySQL, dotenv

---

## 📈 For Recruiters

**Technical Focus:**

* Built REST APIs and implemented CRUD operations for scalable backend interaction
* Designed relational database schemas for optimal performance under load
* Applied clean architecture principles to separate UI logic from business logic

**Program Management Focus:**

* Led 3-person team through **end-to-end development lifecycle**
* Created sprint goals, managed GitHub issues, and tracked progress using Agile methodology
* Defined **project milestones, feature prioritization**, and version control workflows
* Coordinated cross-functional collaboration between frontend and backend contributors

---

## 💡 Future Improvements

* 🌎 Add **authentication system** (user accounts + saved internships)
* 📬 Enable **email notifications** for new relevant postings
* 📊 Integrate **admin dashboard** for adding/editing database listings
* 🤖 Explore **AI-based internship recommendations** using student profile data

---

## 👩🏻‍💻 Author

**Mahnoor Iftikhar**
📍 Pacific Lutheran University — *CS & Economics Double Major, Data Science Minor*
Passionate about **tech accessibility**, **product building**, and **empowering international students through technology.**

📫 [LinkedIn](https://www.linkedin.com/in/mahnooriftikharrr)
📧 [iftikhm@plu.edu](mailto:iftikhm@plu.edu) | [mahnooriftikharr@gmail.com](mailto:mahnooriftikharr@gmail.com)

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="260" alt="Coding girl animation"/>
</p>
