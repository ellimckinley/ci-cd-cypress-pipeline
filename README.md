# Tech Quiz

Test your technical knowledge with this interactive, full-stack Tech Quiz application! This MERN-based app delivers a fast-paced quiz experience while incorporating modern CI/CD workflows and comprehensive testing.

This project demonstrates:

- Component and E2E testing using Cypress
- Continuous Integration (CI) with GitHub Actions
- Continuous Deployment (CD) via Render
- Full-stack development with MongoDB, Express, React (Vite), and Node.js

---

## 📚 Table of Contents

- [🚀 Deployed Application](#-deployed-application)
- [🛠 Technologies Used](#-technologies-used)
- [📦 Installation Instructions](#-installation-instructions)
- [🧪 Testing Instructions](#-testing-instructions)
- [🔁 Deployment Pipeline](#-deployment-pipeline)
- [📸 Screenshot](#-screenshot)
- [👩‍💻 Author](#-author)
- [📄 License](#-license)

---

## 🚀 Deployed Application

🌐 [View Live App on Render](https://ci-cd-cypress-pipeline.onrender.com/)  
📂 [GitHub Repository](https://github.com/ellimckinley/ci-cd-cypress-pipeline)

---

## 🛠 Technologies Used

- **MongoDB Atlas**
- **Express.js**
- **React (Vite)**
- **Node.js**
- **TypeScript**
- **Cypress (Component & E2E testing)**
- **GitHub Actions (CI/CD)**
- **Render (Web Service deployment)**

---

## 📦 Installation Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/ellimckinley/ci-cd-cypress-pipeline.git
   cd ci-cd-cypress-pipeline

   ```

2. Install dependencies:

   ```bash
   npm run install

   ```

3. Build the frontend:

   ```bash
    npm run build

   ```

4. Start the application:

   ```bash
   npm start
   ```

---

## 🧪 Testing Instructions

Run Cypress component and E2E tests locally:

```bash
 npx cypress open
```

```bash
 npx cypress run --component
 npx cypress run --e2e
```

---

## 🔁 Deployment Pipeline

Pull Requests to develop trigger Cypress tests via GitHub Actions

Merges from develop → main trigger auto-deploy to Render via a Deploy Hook

Environment variables (like MONGODB_URI) are securely managed through Render

---

## Technologies Used

- MongoDB

- Express.js

- React

- Node.js

- Cypress

- TypeScript

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👩‍💻 Author

**Elli McKinley**
Business Systems Specialist | Developer-in-Training | River Rat 🛶
[GitHub](https://github.com/ellimckinley) | [LinkedIn](https://linkedin.com/in/ellimckinley)

---

```

```
