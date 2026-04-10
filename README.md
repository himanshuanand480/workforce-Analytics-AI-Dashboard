# Workforce Analytics AI Dashboard

## 📌 Overview
Developed an AI-powered Workforce Analytics Dashboard that allows users to upload employee data and analyze it using natural language queries.

The system leverages prompt engineering to ensure accurate KPI calculations, structured insights, and dynamic visualization generation.

---

## 🚀 Key Features
- Upload employee dataset (CSV format)
- AI Assistant to query data using natural language
- Accurate KPI calculations (Attrition Rate, Total Employees, Salary)
- Dynamic chart generation (bar, pie, line)
- Real-time business insights from structured data
- Prompt-controlled logic to prevent incorrect outputs

---

## 🛠️ Tools & Technologies
- Emergent AI (AI App Builder)
- Prompt Engineering (LLM-based control)
- ChatGPT / LLM
- Recharts (Data Visualization)

---

## 🧠 Prompt Engineering (Core Logic)

### System-Level Prompt
Create a workforce analytics web application with an AI assistant.

Features:
1. Chat interface to ask questions about employee data
2. Use ONLY the provided dataset (no guessing)
3. Calculate correctly:
   attrition_rate = (employees who left / total employees) * 100
4. Generate charts (bar, pie, line) dynamically
5. Show KPIs:
   - Total Employees
   - Attrition Rate
   - Average Salary
6. Provide clear business insights based on data

---

### Key Constraints
- Use ONLY the uploaded dataset (no guessing)
- attrition_rate = (employees who left / total employees) * 100
