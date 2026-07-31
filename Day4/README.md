# 🏋️ Day 4 – Lightning Web Components (LWC)
## Salesforce Internship – Gym Management System

### 📅 Date
31-07-2026

---

# 📌 Objective

The objective of Day 4 was to learn the fundamentals of **Lightning Web Components (LWC)** and build the first user interface for the **Gym Management System**. During this session, I created my first Lightning Web Component, deployed it to Salesforce, displayed data using JavaScript variables, and handled user interactions using events. LWC is Salesforce's modern framework for building fast, reusable UI components using HTML, JavaScript, and XML. :contentReference[oaicite:0]{index=0}

---

# 🚀 Topics Covered

- Introduction to Lightning Web Components (LWC)
- LWC Folder Structure
- HTML Template
- JavaScript Controller
- XML Configuration File
- Deploying LWC using Salesforce CLI
- Lightning App Builder
- Data Binding
- Event Handling
- User Input using `lightning-input`

---

# 📂 Component Created

```
gymHome
```

### Folder Structure

```
force-app
└── main
    └── default
        └── lwc
            └── gymHome
                ├── gymHome.html
                ├── gymHome.js
                └── gymHome.js-meta.xml
```

---

# 🛠️ Activities Performed

### ✅ Activity 1
Created the first Lightning Web Component (`gymHome`) using VS Code.

### ✅ Activity 2
Configured the component using:

- HTML
- JavaScript
- Meta XML

### ✅ Activity 3
Deployed the component to the Salesforce Org using:

```bash
sf project deploy start --source-dir force-app/main/default/lwc/gymHome
```

### ✅ Activity 4
Added the component to the **Gym Dashboard** using Lightning App Builder.

### ✅ Activity 5
Displayed Gym information using JavaScript variables.

Example:

- Member Name
- Trainer Name
- Membership Type

### ✅ Activity 6
Implemented Data Binding using:

```html
{memberName}
```

### ✅ Activity 7
Implemented Event Handling using a **Show Welcome** button.

### ✅ Activity 8
Accepted user input using `lightning-input` and updated the UI dynamically.

---

# 🖥️ Dashboard Output

```
🏋️ FitLife Gym Management

Welcome to FitLife Gym

Member Name : Kushal Konchada

Trainer Name : Rahul Sharma

Membership : Gold Membership

[ Show Welcome ]
```

---

# 💻 Technologies Used

- Salesforce Platform
- Lightning Web Components (LWC)
- HTML
- JavaScript
- XML
- Salesforce CLI
- VS Code

---

# 📖 Key Concepts Learned

### Lightning Web Components

LWC is Salesforce's modern UI framework for creating reusable and high-performance components using standard web technologies. :contentReference[oaicite:1]{index=1}

### Data Binding

Data binding connects JavaScript properties with HTML using curly braces (`{}`), allowing the UI to update automatically when the data changes. :contentReference[oaicite:2]{index=2}

### Event Handling

Handled button click events using the `onclick` attribute and JavaScript methods.

Example:

```html
<lightning-button
    label="Show Welcome"
    onclick={showWelcome}>
</lightning-button>
```

### User Input

Collected user input using the `lightning-input` base component and `onchange` event. Lightning base components provide reusable UI elements that follow Salesforce Lightning Design System (SLDS). :contentReference[oaicite:3]{index=3}

---

# 🎯 Learning Outcome

By the end of Day 4, I was able to:

- Create Lightning Web Components
- Deploy components to Salesforce
- Add components to Lightning App Builder
- Display data using JavaScript variables
- Implement data binding
- Handle button click events
- Accept user input
- Understand the basic architecture of LWC

---

# 📌 Next Goal

Build a complete **Gym Management Dashboard** by integrating:

- Apex
- SOQL
- Salesforce Database
- CRUD Operations
- Dynamic Member Management

---

## 📚 References

- Salesforce Trailhead – Lightning Web Components Basics
- Salesforce Developer Documentation
- Lightning Base Components Documentation :contentReference[oaicite:4]{index=4}
