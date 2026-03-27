<h1 align="center">FinanceFlow - Angular Financial Tracker Application</h1>

<p align="center">
A frontend-only Financial Tracker web application developed using Angular, demonstrating core framework concepts, clean architecture, and practical implementation of a syllabus-driven project.
</p>

<hr>

<h2>1. Project Overview</h2>

<p>
FinanceFlow is a single-page application built entirely with Angular, designed to manage personal finances by tracking income and expenses. 
The project focuses on applying fundamental and advanced Angular concepts in a structured and practical manner without relying on a backend.
</p>

<ul>
  <li>Frontend-only application using Angular</li>
  <li>Data persistence using browser localStorage</li>
  <li>Structured according to Angular best practices</li>
  <li>Designed for academic learning and interview demonstration</li>
</ul>

<hr>

<h2>2. Features</h2>

<ul>
  <li><b>Authentication</b>
    <ul>
      <li>Login and Signup functionality</li>
      <li>Simulated JWT authentication using localStorage</li>
      <li>Route protection using Auth Guards</li>
    </ul>
  </li>

  <li><b>Dashboard</b>
    <ul>
      <li>Displays total income</li>
      <li>Displays total expenses</li>
      <li>Shows remaining balance</li>
    </ul>
  </li>

  <li><b>Transaction Management</b>
    <ul>
      <li>Add transactions using Reactive Forms</li>
      <li>Form validation (required, minimum values)</li>
      <li>Edit and delete transactions</li>
    </ul>
  </li>

  <li><b>Transaction Listing</b>
    <ul>
      <li>Display transactions using *ngFor</li>
      <li>Filter by category and date</li>
    </ul>
  </li>

  <li><b>Data Visualization</b>
    <ul>
      <li>Category-wise expense chart</li>
      <li>Monthly summary using Chart.js</li>
    </ul>
  </li>
</ul>

<hr>

<h2>3. Angular Concepts Covered</h2>

<ul>
  <li>Components and modular architecture</li>
  <li>Templates and styling</li>
  <li>Data binding (property, event, two-way)</li>
  <li>Directives (*ngIf, *ngFor)</li>
  <li>Pipes (currency, date)</li>
  <li>Reactive Forms with validation</li>
  <li>Services and Dependency Injection</li>
  <li>Routing and navigation</li>
  <li>Route Guards (CanActivate)</li>
  <li>Observables and async handling (simulated HTTP)</li>
</ul>

<hr>

<h2>4. Project Structure</h2>

<pre>
src/
 └── app/
     ├── components/
     │   ├── login/
     │   ├── signup/
     │   ├── dashboard/
     │   ├── add-transaction/
     │   ├── transaction-list/
     │   └── navbar/
     │
     ├── services/
     │   ├── auth.service.ts
     │   └── transaction.service.ts
     │
     ├── guards/
     │   └── auth.guard.ts
</pre>

<hr>

<h2>5. Technologies Used</h2>

<ul>
  <li>Angular</li>
  <li>TypeScript</li>
  <li>Tailwind CSS</li>
  <li>Chart.js</li>
  <li>LocalStorage</li>
</ul>

<hr>

<h2>6. Installation and Setup</h2>

<pre>
git clone https://github.com/Lakshpri/FinanceFlow.git
cd FinanceFlow
npm install
ng serve
</pre>

<p>Access the application at: <b>http://localhost:4200</b></p>

<hr>

<h2>7. Demo Credentials</h2>

<pre>
Email: demo@example.com
Password: 123456
</pre>

<hr>

<h2>8. Key Highlights</h2>

<ul>
  <li>Clean and maintainable Angular architecture</li>
  <li>Separation of concerns using services</li>
  <li>Reusable and scalable component design</li>
  <li>Real-world simulation of authentication and data handling</li>
  <li>Fully deployable frontend application</li>
</ul>

<hr>

<h2>9. Future Enhancements</h2>

<ul>
  <li>Integration with Spring Boot backend</li>
  <li>JWT-based authentication</li>
  <li>Database integration (PostgreSQL)</li>
  <li>Advanced analytics and reporting</li>
</ul>

<hr>

<h2 align="center">Developed as part of structured Angular learning and practical implementation</h2>
