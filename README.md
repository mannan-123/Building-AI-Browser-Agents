---
# Building AI Browser Agents

This repository contains code examples and notebooks designed to accompany the Building AI Browser Agents course by DeepLearning.AI. The course demonstrates how to build autonomous browser-based agents that interact with web pages and take actions.
---

## What You’ll Learn

- The fundamentals of autonomous web agents: architecture, decision-making, limitations, and interaction with webpages.
- How to build browser agents that perform tasks such as scraping content, filling out forms, signing up for newsletters, and summarizing webpages.
- An introduction to the AgentQ framework: combining Monte Carlo Tree Search (MCTS), self-critique mechanisms, and Direct Preference Optimization (DPO) to enable agents to self-correct and improve.

---

## Setup Instructions

1. **Clone the repository**

2. **Install dependencies**

   ```bash
   pip install playwright selenium transformers openai
   ```

3. **Run the notebooks or scripts**

   - Launch Jupyter and open files
   - Execute the demonstration scripts to see agent interactions in action

---

## Getting Started

- Begin with the “Simple Web Agent” notebook to understand how to load a webpage, extract data, and interact (click, fill form) via code.
- Move to the “Autonomous Web Agent” example where the agent chains actions (navigate → extract → act) across multiple webpages.
- Explore the “AgentQ & MCTS” notebook to understand self-critique loops, decision-tree search, and optimization of agent behavior.
- Finally, customize the examples for your own target websites or tasks to build your own browser-agent system.

---

## Why This Matters

As web-based services remain ubiquitous, building intelligent agents that can **observe**, **reason**, and **act** in browser environments unlocks automation at a new level. This course equips you with the theory and practical tools to build **robust** browser agents that go beyond simple scripting-agents that can learn and adapt.

---
