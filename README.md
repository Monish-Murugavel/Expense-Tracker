# 💰 Expense Tracker Desktop Application

## 📌 Overview

Expense Tracker is a modern desktop-based financial management application developed using **Electron.js**, **HTML5**, **CSS3**, and **JavaScript (ES6)**.  
The application is designed to help users efficiently record, manage, and analyze their financial transactions through an intuitive and interactive user interface.

The system enables users to:
- Track income and expenses
- Analyze spending patterns
- Visualize expense distribution
- Manage category-wise monthly budgets
- Monitor financial behavior using graphical analytics

The application combines real-time calculations, dynamic rendering, and data visualization to provide a seamless personal finance management experience.

---

# 🚀 Key Features

## 📌 Transaction Management Module

The transaction module allows users to record and manage financial activities efficiently.

### Features
- Add Income & Expense Transactions
- Category-Based Expense Classification
- Payment Method Tracking (Cash / UPI)
- Date-wise Transaction Management
- Dynamic Transaction Deletion
- Monthly Transaction Filtering
- Real-time Balance Calculation

### Supported Categories
- 🍜 Food
- 🚕 Transport
- 📓 Education
- 💄 Beauty
- 🛍️ Shopping
- 🎬 Entertainment
- 💊 Health
- 📦 Others

---

# 📊 Statistics & Analytics Module

The Statistics Dashboard provides graphical and analytical insights into user spending behavior.

### Features
- Interactive Pie Chart Visualization using Chart.js
- Total Monthly Expense Calculation
- Category-wise Expense Aggregation
- Percentage-based Expense Distribution
- Dynamic Legend Generation
- Real-time Statistical Rendering
- Automatic Sorting of Highest Spending Categories

### Mathematical Formula Used

\[
Percentage = \frac{Category\ Expense}{Total\ Expense} \times 100
\]

### Workflow
1. Filter monthly expense transactions
2. Calculate total expenses
3. Aggregate category-wise totals
4. Generate chart labels, values, and colors
5. Render pie chart dynamically
6. Display category-wise breakdown with percentages

---

# 💰 Budget Management Module

The Budget Management System helps users monitor and control monthly spending.

### Features
- Set Monthly Budgets for Each Category
- Visual Progress Indicators
- Real-time Budget Usage Tracking
- Budget Exceed Alerts
- Spending Warning Notifications
- Dynamic Progress Bars

### Alert Conditions
- ⚠️ Warning when spending exceeds 75%
- 🚨 Alert when budget limit is exceeded

---

# 🎨 User Interface & Experience

The application follows a modern dark-theme design with smooth transitions and responsive layouts.

### UI Features
- Dark Theme Interface
- Interactive Navigation System
- Responsive Desktop Layout
- Smooth Hover Effects
- Animated Transitions
- Dynamic Content Rendering
- Clean & Minimalistic Design

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure & Layout |
| CSS3 | Styling & Responsive Design |
| JavaScript (ES6) | Application Logic |
| Electron.js | Desktop Application Framework |
| Chart.js | Data Visualization |
| Local Storage | Data Persistence |

---

# 📂 Project Structure

```bash
Expense-Tracker/
│
├── index.html       # Main application structure
├── style.css        # Styling, layouts & animations
├── app.js           # Core business logic & rendering
├── main.js          # Electron desktop configuration
├── package.json     # Project dependencies & scripts
└── README.md
