# Zorvyn – Financial Analytics Dashboard

A responsive financial management dashboard developed with **React** and **Material UI**, focused on data visualization, transaction monitoring, and structured UI architecture. The project demonstrates frontend engineering practices such as component modularization, state management, and responsive layout systems.

---

## Live Application

**Project Demo:**
Live Demo - https://financial-dashboard-ivory-psi.vercel.app/

---

## Project Description

Zorvyn is a frontend financial dashboard prototype built to simulate how modern fintech admin panels manage financial insights and transaction data. The application emphasizes usability, structured design patterns, and scalable component organization.

The main development goals included:

* Building a structured React component architecture
* Creating reusable UI components
* Implementing responsive layouts
* Managing global state efficiently
* Designing clear financial data visualizations

---

## Core Capabilities

### User Interface

* Minimal and professional interface design
* Dark and light theme support
* Card-based analytics layout
* Consistent spacing and typography

### Responsive Behaviour

* Mobile-first responsive structure
* Adaptive sidebar navigation
* Optimized layouts for:

  * Mobile devices
  * Tablets
  * Desktop screens

### Role Based Interface Control

Two interface roles were simulated:

**Administrator**

* Can create transactions
* Full dashboard interaction

**Viewer**

* Read-only access
* Restricted interaction controls

This demonstrates basic RBAC (Role Based Access Control) concepts at UI level.

### Financial Data Visualization

Dashboard includes:

**Analytics Section**

* Account balance overview
* Income tracking
* Expense tracking
* Transaction count metrics

**Charts**

* Revenue trend visualization
* Expense distribution chart
* Key financial insights panel

### Transaction Management

Transaction module includes:

* Search functionality
* Category filtering
* Paginated table
* Status indicators:

  * Completed
  * Pending

### Theme System

Theme switching implemented using Material UI theme provider:

* Dark theme support
* Light theme support
* Dynamic component styling adaptation

---

## State Management Approach

Global state handled using **React Context API**.

Managed data includes:

* Current user role
* Transaction records
* Active filters
* Filtered datasets

### Reason for choosing Context API

* No external dependency required
* Suitable for medium scale applications
* Clean global state structure
* Easy integration with component tree

---

## Folder Organization

Project follows a modular structure:

```
src/

Dashboard/
TopBar.jsx
SideBar.jsx
Header.jsx
SummaryCards.jsx
Charts.jsx
Insights.jsx
Transactions.jsx

Data/
mockData.js

context/
AppContext.jsx

Theme.js
App.js
index.js
```

---

## Technology Stack

Frontend:

* React.js
* Material UI

Data Visualization:

* Recharts
* Nivo Charts

State Management:

* React Context API

Development Tools:

* JavaScript (ES6+)
* CSS Flexbox/Grid
* Responsive design techniques

---

## Local Development Setup

### Clone Repository

```
git clone https://github.com/AswinM7-byte/financial-dashboard.git
cd financial-dashboard
```

### Install Packages

```
npm install
```

### Start Development Server

```
npm start
```

---

## Implementation Highlights

Key frontend improvements implemented:

* Fixed readability issues in light theme
* Improved chart hover interaction
* Responsive sidebar behavior
* Role based button visibility
* Consistent layout spacing
* CSV export support
* UI alignment refinements

---

## Possible Enhancements

Planned improvements include:

* Backend API integration
* Authentication system (JWT/Firebase/Auth0)
* Advanced filtering options
* Animation integration
* Performance optimization
* Real database integration

---

## Learning Outcomes

This project helped strengthen understanding of:

* React component architecture
* UI scalability practices
* State management strategies
* Data visualization integration
* Responsive UI engineering
* Role based UI patterns

---

## Author

**Aswin M**
Frontend Developer | Full Stack Learner

GitHub:
https://github.com/AswinM7-byte
