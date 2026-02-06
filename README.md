# Day-41-100-Days-challenge-in-cybersecurity-
## 🚩 Day 41: Web Foundations & The Hacker's Perspective

> **"You can’t hack what you don’t understand."**

Today was a strategic pivot. Before diving into web application exploitation, I dedicated Day 41 to master the fundamental architecture of the web. Understanding how content is rendered is the critical first step to understanding how it can be manipulated.

### 🏗️ What I Focused On
1. **The Distributed Application:** Analyzing how browsers (clients) request and render code from remote servers.
2. **The Great Divide:**
    * **Frontend (Client-Side):** The "Untrusted Territory." Investigated HTML, CSS, and JS as the primary interface for user-driven attacks.
    * **Backend (Server-Side):** The "Brain." Focused on how logical execution and database operations (MySQL/MongoDB) process sensitive data.
3. **The Security Tech Stack:** * **Dynamic Data:** How React/Angular can lead to DOM-based XSS.
    * **Server Logic:** How PHP/Node.js handle file inclusions and command execution.

### 🪜 HTML Breakdown (The Attack Surface)
* **Tags:** Instructions that can be injected (e.g., `<script>`).
* **Attributes:** Extra info where malicious payloads often hide (e.g., `onerror`, `src`).
* **Structure:** Understanding the `<head>` (metadata/security headers) vs the `<body>` (rendered content).

### 💭 Reflection
Web vulnerabilities are rarely random; they are the result of how data flows through the structure. By understanding the 'Blue Team' side of development, my 'Red Team' perspective becomes significantly sharper.
