# 🚀 AI GTM Company Enrichment & CRM Automation Platform

An AI-powered GTM automation platform built using Clay, n8n, Groq LLM, Google Sheets, and HubSpot CRM. Company data is first enriched using Clay, then processed
through an automated AI workflow to generate GTM insights, lead intelligence, CRM records, and outreach-ready research.

---

# 📌 Overview

Sales teams spend significant time researching companies before outreach.

This workflow automates that process by:

* Researching companies using AI
* Generating structured GTM insights
* Identifying customer pain points
* Recommending solution opportunities
* Calculating lead priority
* Creating companies inside HubSpot CRM
* Storing research inside Google Sheets

The result is a complete AI-powered company enrichment pipeline.

---

# 🎯 Features

✅ Company Research

* Company summary
* Industry
* Products & Services
* Target Customers

---

✅ GTM Intelligence

* Pain Points
* Business Opportunities
* Recommended Solution
* CRM Stage
* Lead Score
* Priority Level

---

✅ Sales Enablement

* Personalized Email Opening
* Cold Email Subject
* Cold Email Draft

---

✅ CRM Automation

Automatically creates:

* Company in HubSpot
* CRM Activity Repository
* AI Research Repository

---

# 🛠 Tech Stack

Clay (Company Enrichment)
n8n
Groq LLM
Google Sheets
HubSpot CRM

---

# 📊 Workflow Architecture

Company List (Google Sheets)

↓

Import Companies

↓

Loop Over Companies

↓

Groq AI Research Agent

↓

Research JSON Formatter

↓

AI Research Repository (Google Sheets)

↓

Create Company in HubSpot

↓

CRM Activity Repository

---

# 📂 Workflow Steps

## 1. Import Company List

Reads companies from Google Sheets.

Input Example

* Company Name
* Website

---

## 2. Process Companies

Processes companies one by one.

---

## 3. AI GTM Research Agent

Uses Groq LLM to generate

* Business Summary
* Products & Services
* Target Customers
* Pain Points
* Opportunities
* Lead Score
* Priority
* Personalized Email
* Cold Email Draft

---

## 4. JSON Formatter

Converts AI response into structured JSON.

---

## 5. AI Research Repository

Stores AI-generated research inside Google Sheets.

---

## 6. HubSpot Automation

Creates Company records automatically.

Mapped Properties

* Company Name
* Website
* About Us
* Description
* Domain
* CRM Stage
* Lead Score
* Priority

---

## 7. CRM Activity Repository

Stores CRM activity logs for reporting.

---

# 📈 Example Output

For each company the workflow generates:

* Business Summary
* Products & Services
* Target Customers
* Pain Points
* Opportunities
* Recommended Solution
* CRM Stage
* Lead Score
* Priority
* Personalized Email Opening
* Cold Email Subject
* Cold Email Draft

---

# 📸 Screenshots

Add screenshots here.

Recommended:

1. Complete Workflow
2. AI Research Output
3. JSON Formatter
4. Google Sheets Repository
5. HubSpot Company Record

---

# 🎥 Demo

Loom Video

(Add your Loom link)

---

# 💡 Future Improvements

* Clay Integration
* Apollo Integration
* LinkedIn Data Enrichment
* Multi-LLM Support
* Contact Creation
* Deal Creation
* Email Automation
* Lead Scoring Improvements
* CRM Analytics Dashboard

---

# 📚 Learning Outcomes

This project demonstrates:

* AI Workflow Automation
* Prompt Engineering
* JSON Data Transformation
* CRM Automation
* HubSpot Integration
* Google Sheets Automation
* n8n Workflow Design
* LLM Integration

---

# 👩‍💻 Author

**Archana Krishnan**

AI Automation | GTM Automation | Workflow Automation | HubSpot | n8n | Generative AI

LinkedIn:
(Add LinkedIn URL)

GitHub:
(Add GitHub URL)
