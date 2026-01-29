# Customer Support Intelligence Dashboard

## 🚀 Project Overview

An AI-powered customer support intelligence system designed to provide a **360° view of enterprise customers**, their product entitlements, support cases, releases, and vulnerabilities. The system centralizes fragmented data into a single dashboard to help support engineers resolve cases faster and with better context.

This project is a **recreated demo inspired by an enterprise internship experience** and uses mock data and abstractions to remain NDA-safe.

---

## 🎯 Problem Statement

Enterprise SaaS organizations supporting universities and large institutions face challenges such as:

* Customer data scattered across multiple tools (ServiceNow, KBs, release notes, docs)
* Lack of visibility into customer entitlements and ERP lifecycle stage
* Slow case resolution due to missing context
* Manual effort to understand releases, defects, and vulnerabilities

**Goal:** Build a unified system that connects customer, product, and case data, enhanced with AI-driven insights.

---

## 🏗️ System Architecture

The system follows a modular, enterprise-style workflow:

* **Customer → Product → Module Mapping**
  Maps each customer to their entitled product lines, products, and modules.

* **Case Intake Layer**
  A structured form captures case details such as priority, environment, product, and description.

* **Unified Dashboard**
  Displays customer cases alongside releases, KB articles, planned activities, and vulnerabilities.

* **AI Intelligence Layer**
  Adds summarization, recommendations, and question answering using RAG.

Architecture diagrams are available in the `architecture/` folder.

---

## 🖥️ Key Features

### 1. Customer Case Intake

* Structured case submission form
* Fields include case number, account, product line, module, priority, environment, and description
* Input validation and standardized formats

### 2. Customer & Entitlement Mapping

* Customer-product-module relationships
* ERP lifecycle tracking (Onboarding, Transition, Steady State)
* Region and cloud deployment awareness

### 3. Support Dashboard

* Centralized view of all customer cases
* Contextual panels for:

  * Documentation
  * Planned and unplanned customer activities
  * Defects and KB articles
  * Releases (recent, upcoming, maintenance)
  * Third-party vulnerabilities

### 4. AI-Powered Insights

* Case summarization
* Context-aware recommendations
* Intelligent question answering
* LLM-assisted case pre-filling

---

## 🤖 AI Components

### Retrieval-Augmented Generation (RAG)

* Retrieves relevant knowledge base articles, release notes, and documentation
* Grounds LLM responses in enterprise data

### Summarization

* Converts long case descriptions and documents into concise summaries

### Recommendation Engine

* Suggests relevant releases, KBs, and next steps based on case context

### Intelligent Questioning

* Allows support engineers to ask natural language questions about customer context

> AI logic is demonstrated conceptually using mock workflows and documented design decisions.

---

## 📊 Sample Data

The `data/` folder includes mock datasets representing:

* Universities and institutions
* ERP phases (Banner SaaS, Managed Cloud, On-Premise)
* Regions and patching zones

All data is anonymized and created purely for demonstration purposes.

---

## 🎥 Demo Walkthrough

A recorded walkthrough explains:

* Problem statement
* System workflow
* Case submission flow
* Dashboard insights
* AI feature integration

🎥 **Demo Video (Concept Walkthrough):**  
https://drive.google.com/file/d/1WiE9XrQiWKWB8zMnXth1Z0ssM8eC1Bzu/view

> The video focuses on explaining the system flow, architecture, and AI-driven concepts using the demo setup.

---

## 🛠️ Tech Stack

* **Frontend:** React.js
* **Backend:** FastAPI (conceptual design)
* **Data:** CSV / JSON (mocked)
* **AI:** LLM + RAG (conceptual)
* **Cloud:** AWS (architecture-level)

---

## 🧠 Key Learnings

* Designing enterprise-scale workflows
* Structuring customer support intelligence systems
* Applying AI to real business problems
* Translating complex requirements into dashboards
* Communicating technical solutions effectively

---

## 🔐 Disclaimer

This project is a **recreated demo inspired by enterprise internship work**. It does not include proprietary code, real customer data, or internal systems. All names, data, and workflows are generalized for learning and demonstration purposes.

---

## 📌 Author

**Navyasri Cherukuri**
Aspiring Software Engineer | Web Development | AI-driven Systems
