---
# **Project Name: Expense Tracker Web App**

The **Expense Tracker Web App** is a full-stack MERN application designed to help users track their expenses and manage budgets efficiently. The app provides a user-friendly interface for recording transactions, viewing expense reports, and analyzing spending patterns.

---

## **Mission and Objectives**

### **Mission**
To create an intuitive and efficient expense management platform that empowers users to monitor their financial habits and make informed budgeting decisions.

### **Objectives**
1. Enable users to securely register and log in.
2. Provide tools for recording, categorizing, and updating transactions.
3. Display visual insights through graphs and charts.
4. Ensure responsive design for seamless usage across devices.
5. Deploy the application for global accessibility.

---

## **Technology Stack**

### **Frontend**
1. **React.js**
   - **Why?** Simplifies UI development with reusable components.
   - **Use Case:** Building the user interface, including forms and charts.

2. **React Router**
   - **Why?** Enables seamless navigation between pages.
   - **Use Case:** Managing routes such as login, dashboard, and transaction history.

3. **Material-UI (MUI)**
   - **Why?** Provides pre-designed, customizable components.
   - **Use Case:** Styling buttons, forms, and charts.

4. **Chart.js**
   - **Why?** Offers powerful data visualization tools.
   - **Use Case:** Displaying spending patterns and budget breakdowns.

---

### **Backend**
1. **Node.js**
   - **Why?** Enables efficient backend logic.
   - **Use Case:** Handling API requests and business logic.

2. **Express.js**
   - **Why?** Lightweight framework for building APIs.
   - **Use Case:** Creating RESTful APIs for transactions and user authentication.

3. **JWT (JSON Web Tokens)**
   - **Why?** Ensures secure user authentication.
   - **Use Case:** Managing user sessions.

4. **Bcrypt.js**
   - **Why?** Encrypts passwords for secure storage.
   - **Use Case:** Protecting user credentials.

---

### **Database**
1. **MongoDB**
   - **Why?** Provides a flexible schema for managing transactions and users.
   - **Use Case:** Storing user profiles, categories, and expense data.

2. **Mongoose**
   - **Why?** Simplifies MongoDB interactions.
   - **Use Case:** Defining schemas and handling queries.

---

### **Deployment**
1. **Netlify/Vercel**
   - **Why?** Provides fast and reliable hosting for frontend applications.
   - **Use Case:** Hosting the React application.

2. **Render/AWS**
   - **Why?** Ensures scalable backend hosting.
   - **Use Case:** Deploying APIs and database connections.

---

## **System Architecture**
The app follows a traditional MERN architecture:
1. **Frontend:** React communicates with the backend through RESTful APIs.
2. **Backend:** Express handles requests, performs business logic, and interacts with MongoDB.
3. **Database:** MongoDB stores user data and transaction details.
4. **Authentication:** JWT manages user sessions and access control.

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

### **Week 1: Project Setup and Basic UI**
- **Goal:** Set up the project and design the initial interface.
- **Tasks:**
  1. Initialize React and Node.js projects.
     - **Reading:** [Setting Up MERN Stack](https://www.mongodb.com/mern-stack)
     - **Video:** [MERN Stack Crash Course](https://www.youtube.com/watch?v=fnpmR6Q5lEc)
  2. Create the project directory structure.
     - **Reading:** [React App Structure](https://reactjs.org/docs/getting-started.html)
     - **Video:** [React Basics](https://www.youtube.com/watch?v=SqcY0GlETPk)
  3. Set up Material-UI for styling.
     - **Reading:** [Material-UI Docs](https://mui.com/getting-started/usage/)
     - **Video:** [Material-UI Tutorial](https://www.youtube.com/watch?v=fzxEECHnsvU)

- **Deliverables:**
  - Functional frontend with basic navigation and placeholder components.

---

### **Week 2: Authentication System**
- **Goal:** Enable secure user registration and login.
- **Tasks:**
  1. Design user schema in MongoDB.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build authentication APIs with JWT.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Implementation Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)
  3. Implement login and signup pages in React.
     - **Reading:** [React Forms](https://react.dev/reference/react-dom/components/form)
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ)

- **Deliverables:**
  - Functional login and signup system.

---

### **Week 3: Expense Management**
- **Goal:** Allow users to add, edit, and view expenses.
- **Tasks:**
  1. Design expense schema in MongoDB.
     - **Reading:** [MongoDB Schema Guide](https://www.mongodb.com/docs/manual/data-modeling/)
     - **Video:** [Mongoose Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  2. Build APIs for CRUD operations on expenses.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  3. Create expense tracking UI.
     - **Reading:** [Material-UI Components](https://mui.com/getting-started/usage/)
     - **Video:** [Material UI](https://www.youtube.com/watch?v=CwAr9cUJA6A)

- **Deliverables:**
  - Expense management functionality.

---

### **Week 4: Visualization and Reports**
- **Goal:** Display expense insights through charts and graphs.
- **Tasks:**
  1. Integrate Chart.js for data visualization.
     - **Reading:** [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
     - **Video:** [React Chart.js Tutorial](https://www.youtube.com/watch?v=Ly-9VTXJlnA)
  2. Add monthly and category-wise expense summaries.
     - **Reading:** [React State Management](https://react.dev/learn/lifecycle-of-reactive-effects)
     - **Video:** [State Management in React](https://www.youtube.com/watch?v=35lXWvCuM8o)

- **Deliverables:**
  - Visual reports displaying spending patterns.

---

### **Week 5: Deployment and Testing**
- **Goal:** Deploy the application and ensure it works flawlessly.
- **Tasks:**
  1. Deploy the frontend on Netlify or Vercel.
     - **Reading:** [Netlify Deployment Guide](https://docs.netlify.com/)
     - **Video:** [Deploying React Apps](https://www.youtube.com/watch?v=eSeBVcKZx9Y)
  2. Deploy the backend on Render or AWS.
     - **Reading:** [Render Deployment Guide](https://render.com/docs)
     - **Video:** [Node.js Deployment Tutorial](https://www.youtube.com/watch?v=l134cBAJCuc)
  3. Test all features and fix bugs.
     - **Reading:** [Testing React Apps](https://reactjs.org/docs/testing.html)
     - **Video:** [React Testing Tutorial](https://www.youtube.com/watch?v=8Xwq35cPwYg)

- **Deliverables:**
  - Fully deployed and functional Expense Tracker app.

---

## Screenshots
![Screenshot (346)](https://github.com/user-attachments/assets/c0f71579-b72d-4a64-ae09-9e6c2a916dd7)
![Screenshot (347)](https://github.com/user-attachments/assets/e229e474-2e0f-4d5c-9b3c-5cec86ffb6e8)
![Screenshot (348)](https://github.com/user-attachments/assets/1cc8f96d-f1fc-481c-99f3-1f88a45ff123)
![Screenshot (350)](https://github.com/user-attachments/assets/d02692e9-d1fb-4ea2-8e34-1701275d1d1a)
![Screenshot (345)](https://github.com/user-attachments/assets/c836b520-bb99-4284-a5ac-c54a86faa66b)

---

## **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Material-UI Documentation](https://mui.com/)
4. [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
5. https://github.com/Maclinz/expense-tracker_fullstack
6. https://www.youtube.com/watch?v=i0JesTevAcA

