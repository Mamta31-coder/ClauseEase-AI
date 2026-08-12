# ⚖️ ClauseEase AI

### AI-Based Contract Language Simplifier

> **Simplify. Understand. Manage Complex Contracts with the Power of AI.**

ClauseEase AI is a web-based AI application that helps users understand complex legal and contractual documents by simplifying legal language and identifying important legal terms.
---

## 📌 Project Overview

ClauseEase AI provides an end-to-end platform for analyzing and simplifying legal and contractual documents.

Users can register, securely log in, upload a contract or paste contract text, select a simplification level, and analyze the document.

The application generates simplified contract text and identifies important legal terminology to make complex documents easier to understand.

The system also includes a dedicated administrative dashboard where authorized administrators can manage users, maintain the legal glossary, and view application-level analytics such as registered users, uploaded contracts, and simplification statistics.
---

## 🎯 Project Objectives

- Simplify complex contractual language
- Help non-legal users understand legal documents
- Detect important legal terminology
- Provide different levels of text simplification
- Allow users to access their previously analyzed contracts
- Provide a searchable legal glossary
- Provide administrators with application-level analytics
- Provide administrators with user and glossary management
---

## ✨ Main Features

### 👤 User Registration & Login

The application provides a complete authentication system.

Users can:

- Create an account
- Enter their personal information
- Create a password
- Log in and log out
- Manage their profile
- Change their password

### 📄 Contract Simplification

Users can provide contract content in two ways:

**Upload a document:**

- PDF
- DOCX
- TXT

**OR**

Paste contract text directly into the application.

### 🤖 AI-Based Contract Analysis

Users can select a simplification level and analyze the provided contract.

The application processes the contract and generates simplified content.

### ⚖️ Legal Term Detection

ClauseEase AI identifies important legal terminology from the contract and displays the detected terms separately from the simplified text.

Examples include:

- Liability
- Assignment
- Dispute Resolution
- Governing Law

### 📊 Simplification Levels

The application provides multiple levels of text simplification:

- Basic
- Intermediate
- Advanced

### 📁 My Uploads

Users can access their previously processed contracts through the **My Uploads** section.

### 📚 Legal Glossary

ClauseEase AI provides a dedicated glossary for understanding legal terminology.

The glossary is maintained by administrators.

### 👤 User Profile

Users can view their registered information and manage their account through the profile section.

The profile also provides a password-change facility.
---

## 👨‍💼 Admin Dashboard

ClauseEase AI includes a dedicated administrative dashboard that is accessible only to authorized administrators.

### 📈 Admin Analytics

Administrators can view application-level statistics such as:

- Total number of registered users
- Total number of uploaded contracts
- Uploads per day
- Upload distribution by simplification level
- Recent uploads

These statistics are available to administrators and are not part of the normal user interface.

### 👥 User Management

Administrators can view registered users and information such as:

- User ID
- Username
- Email
- Country
- Admin status

Administrators can also:

- Promote a user to administrator
- Remove administrator privileges
- Delete user accounts

### 📖 Glossary Management

Administrators can manage the legal glossary by:

- Adding legal terms
- Editing existing terms
- Deleting terms
- Maintaining their meanings
---

## 🔄 Project Workflow

```text
                         ClauseEase AI
                              │
                              ▼
                       Welcome Page
                              │
                              ▼
                         Registration
                              │
                              ▼
                            Login
                              │
                              ▼
                    Contract Simplifier
                       /            \
                      /              \
             Upload Document       Paste Text
              PDF/DOCX/TXT
                      \              /
                       \            /
                        ▼          ▼
                 Select Simplification
                         Level
                           │
                           ▼
                    Analyze Contract
                           │
                  ┌────────┴────────┐
                  ▼                 ▼
           Simplified Text    Legal Term Detection
                  │                 │
                  └────────┬────────┘
                           ▼
                     View Results
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
         My Uploads     Glossary      Profile
                                       
                           │
                           ▼
                   Admin Dashboard
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
         Analytics      Users        Glossary
