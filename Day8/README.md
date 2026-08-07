# 🏋️ Gym Management System - Salesforce CRM

## 📌 Project Overview

The Gym Management System is a Salesforce CRM application developed using Apex, Lightning Web Components (LWC), SOQL, and Salesforce automation. It streamlines gym operations by managing members, memberships, trainers, workout plans, payments, and dashboard analytics within a single platform.

The application automates the complete member onboarding process, assigns trainers based on workout specialization, generates memberships and workout plans automatically, tracks payments, and provides an interactive dashboard with real-time business insights.

---

## 🚀 Features

### 👤 Member Management

* Register new gym members
* Automatic End Date calculation
* Membership validation
* Automatic Membership creation
* Automatic Workout Plan creation
* Automatic Trainer Assignment
* Relationship-based data management

### 💳 Membership Management

* Monthly Membership
* Quarterly Membership
* Half-Yearly Membership
* Yearly Membership
* Automatic membership fee assignment
* Automatic discount calculation
* Membership duration calculation
* Membership status tracking (Active / Expired)

### 💰 Payment Management

* Payment record generation
* Revenue tracking
* Membership-wise payment records
* Currency formatting
* Relationship with Membership object

### 🏋️ Trainer Management

* Trainer profiles
* Workout specialization
* Automatic trainer assignment
* Member-to-Trainer relationship

### 📋 Workout Plans

* Automatic workout plan generation
* Start Date
* End Date
* Active/Inactive status
* Member relationship

---

# ⚙️ Automation

The system uses Salesforce Apex Triggers and Trigger Handlers.

### Member Trigger

* Before Insert
* Before Update
* After Insert

Automations include:

* End Date calculation
* Date validation
* Membership creation
* Workout Plan creation
* Trainer assignment

---

# 📊 Dashboard (Lightning Web Components)

The custom dashboard displays live Salesforce data.

### KPI Cards

* Total Members
* Total Trainers
* Total Memberships
* Total Revenue

### Recent Members

* Search
* Sorting
* Pagination
* Clickable Member Record Links

### Recent Payments

* Latest payment records
* Member details
* Payment amount
* Payment date

### Charts

* Membership Distribution
* Revenue Analysis (In Progress)

---

# 🛠️ Technologies Used

* Salesforce CRM
* Apex
* SOQL
* Lightning Web Components (LWC)
* JavaScript
* HTML
* CSS
* SLDS (Salesforce Lightning Design System)
* Chart.js
* Git & GitHub

---

# 📂 Salesforce Objects

* Member__c
* Membership__c
* Trainer__c
* Workout_Plan__c
* Payment__c

---

# Relationships

Member
→ Membership

Membership
→ Payment

Member
→ Workout Plan

Member
→ Trainer

---

# LWC Components

* gymDashboard
* membershipChart
* revenueChart (In Progress)

---

# Current Functionalities

✔ Member Registration

✔ Membership Automation

✔ Workout Plan Automation

✔ Trainer Assignment

✔ Payment Management

✔ Dashboard KPIs

✔ Recent Members Table

✔ Search

✔ Sorting

✔ Pagination

✔ Recent Payments

✔ Chart.js Integration

---

# Future Enhancements

* Revenue Bar Chart
* Workout Distribution Chart
* Active vs Expired Membership Chart
* QR Payment Integration
* Payment Screenshot Upload
* Email Notifications
* Attendance Tracking
* Membership Renewal Reminders
* Responsive Dashboard
* Dashboard Refresh
* Loading Spinners
* No Data Screens

---

# Learning Outcomes

This project helped in understanding:

* Salesforce Data Model
* Object Relationships
* Apex Programming
* Trigger Framework
* SOQL
* Aggregate Queries
* Lightning Web Components
* Component Communication
* JavaScript ES6
* Chart.js Integration
* Salesforce UI Customization
* CRM Automation

---

# Project Status

🚧 Currently Under Development

Completed Modules:

* Member Management
* Membership Management
* Workout Plan
* Trainer Assignment
* Payment Management
* Dashboard Analytics

Upcoming Modules:

* Advanced Analytics
* Revenue Charts
* QR Payment
* Dashboard Optimization

---

## Author

**Kushal Konchada**

B.Tech – Artificial Intelligence & Data Science

Salesforce Developer | Full Stack Developer

