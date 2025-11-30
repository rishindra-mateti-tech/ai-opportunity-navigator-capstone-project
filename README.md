📌 AI Opportunity Navigator — Capstone Project

A multi-agent career-guidance system built using Google ADK + Gemini + Gradio.
It analyzes a user’s background, skills, interests, experience level, and goals — then generates personalized opportunities, including research roles, internships, projects, and a 90-day action plan.

🚀 Overview

Choosing the right career opportunity is confusing — too many choices, not enough clarity.
This project solves that using Agentic AI.

The system uses multiple coordinated agents:

ProfileAgent — understands user background

OpportunityAgent — recommends research roles, internships, projects

PlannerAgent — creates personalized 60–90 day actionable plans

Orchestrator — runs everything in sequence using Google ADK

Gradio UI — user enters details + chats with the system

🧠 Architecture

✨ Features

✔ Multi-agent system powered by Google ADK
✔ Uses Gemini 2.5 Flash / Flash Lite models
✔ Smart text-processing tools (extract_profile, suggest_opps, score_opportunities)
✔ Clean Gradio UI with interactive chat
✔ Personalized opportunity matching based on skills, interests & goals
✔ Auto-generated 90-day action plan
✔ Handles follow-up questions and adapts
✔ Can be extended to show live job links (Indeed, LinkedIn, Google Jobs)

🧩 How It Works

User enters background
– Skills, education, goals, interests, experience level

Profile Builder
– Converts user input to structured text

Orchestrator Agent
– Runs ProfileAgent → OpportunityAgent → PlannerAgent

Agents produce:

Summary of user profile

Personalized opportunities

90-day career plan

Chat Interface
– Supports follow-up Q&A
– User can refine, ask for alternative paths, new goals, etc.

🛠️ Tech Stack

Google ADK (Agent Development Kit)

Gemini 2.5 Flash / Flash Lite

Gradio (UI)

Python

FunctionTool + SequentialAgent + LlmAgent
