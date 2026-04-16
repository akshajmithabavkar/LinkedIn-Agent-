# 🤖 LinkedIn Profile Optimization AI Agent

An automated workflow agent built on **agent.ai** that performs deep analysis of LinkedIn profiles to provide personalized branding suggestions.

## 🚀 Overview
This agent automates the process of profile auditing. By simply providing a profile URL, the agent scrapes the data, processes it through an LLM, and returns a formatted report on how to improve headlines, about sections, and experience descriptions.

## 🛠️ Tech Stack
- **Platform:** Agent.ai (AI Orchestration)
- **Model:** GPT-4o mini
- **Integrations:** LinkedIn Scraper API
- **Logic Flow:** Sequential Workflow

## 📋 The Workflow Logic
The agent follows a 4-step sequence:
1. **User Input:** Captures the target LinkedIn URL.
2. **Data Extraction:** Retrieves `professional_info` using a dedicated LinkedIn tool.
3. **AI Reasoning:** Passes the raw data to `gpt-4o-mini` to identify gaps in professional branding.
4. **Final Delivery:** Outputs a structured report.

## 📸 Backend Workflow
![Agent Workflow](workflow.jpg)

## 🔗 Live Demo
[https://agent.ai/agent/55gwjdntb1qzxr5k]
