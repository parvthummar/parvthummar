## Hi 👋 I'm Parv Thummar

🎓 B.Tech in Computer Science & Engineering, IIIT Vadodara (Class of 2026)
🤖 AI/ML engineer building **agentic systems** — multi-agent workflows, RAG pipelines, and LLM-powered developer tools
🔐 Backend foundation in Java/Spring Boot with a strong interest in secure, reliable API design

---

## 💫 About Me

- 🔭 Currently building multi-agent systems with **LangGraph** and production RAG pipelines over vector databases
- 🧩 Comfortable across the stack an AI product actually needs: retrieval, orchestration, evaluation, and the API layer underneath it
- 🛡️ Backend roots in Spring Boot, JWT, and applied cryptography — I care about systems that are secure by construction
- 🧠 Solid foundation in Data Structures, Algorithms, and Operating Systems
- ⚡ Fun fact: I enjoy debugging backend issues more than writing new features

---

## 🌐 Profiles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parv-thummar-36aa7b258/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:parvthummar8@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white)](https://github.com/parvthummar)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=black)](https://leetcode.com/u/parvthummar2003/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?logo=codeforces&logoColor=white)](https://codeforces.com/profile/parvthummar)

---

## 💻 Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Agentic AI & LLM Engineering
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Patterns:** multi-agent orchestration · ReAct & tool calling · human-in-the-loop interrupts · structured state graphs · agentic RAG
**RAG:** chunking strategies · hybrid retrieval · reranking · RRF · HyDE · Self-RAG / CRAG · RAGAS evaluation

### Vector Databases
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

### Backend & Security
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge)

### Databases & Tools
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🚀 Featured Projects

### 🔍 CodeLens
**Semantic Code Search Platform — Query Any GitHub Repo in Plain English**

`Python` · `FastAPI` · `MongoDB` · `Pinecone` · `OpenAI API` · `React`

- Built a semantic code search platform that indexes any public GitHub repository and lets users find functions, classes, and methods using natural language instead of exact keywords
- Designed an asynchronous indexing pipeline that clones repos, extracts code entities, and embeds them into a **Pinecone** vector database, enabling **RAG-based** retrieval for ranked semantic search results
- Built a **FastAPI** backend with **MongoDB** (Motor + Beanie) for user/project metadata and **JWT**-based auth, paired with a **React 19 + Vite** frontend showing live indexing status via polling

🔗 Repo: https://github.com/parvthummar/CodeLens

---

### 🔐 Protected Pixels
**End-to-End Encrypted Photo Storage Platform**

- Built a true E2EE system where the server never accesses user data or passwords
- Implemented JWT-based authentication with a custom Spring Security filter chain
- Designed a two-key encryption model (verification key + master key)
- Used PBKDF2 for key derivation and AES-256 / AES-GCM for encryption
- Performed all cryptographic operations client-side in React to preserve zero-knowledge guarantees

🔗 Repo: https://github.com/parvthummar/Protected-Pixels

---

### 🏦 Online Banking System
**Secure Full-Stack Banking Platform**

- Engineered a secure system for account creation, fund transfers, and transaction history
- Implemented JWT access & refresh tokens with Spring Security + BCrypt
- Built REST APIs using Spring Boot, JPA/Hibernate, and MySQL
- Developed a React + Redux frontend with Material-UI dashboards

🔗 Repo: https://github.com/parvthummar/Online-Banking-System

---

### 📈 Short-Term Volatility Prediction (Bachelor's Thesis)
**Deep Learning for Financial Time Series**

- Compared Linear Regression, GARCH-LSTM, and Temporal Fusion Transformer models on S&P 500 / VIX data
- Best-performing TFT model reached **R² = 0.9697** on short-term volatility forecasting

---

## 💼 Experience

### Backend Intern — GrowIdeas Innovations (May 2025 – June 2025)

- Engineered backend logic to parse and transform complex JSON using Jackson
- Built validation and exception-handling layers to improve API reliability
- Designed optimized MySQL-backed modules using Spring Data JPA
- Collaborated with frontend teams by documenting APIs in Postman

---

## 🏆 Achievements

- ⭐ Solved 800+ DSA problems across platforms
- 🏅 Codeforces Specialist
- 📜 NVIDIA Certified in Deep Learning
- 🎯 Top 1.5% in JEE Mains

---

👀 Open to AI/ML engineering roles — agentic systems, RAG, and LLM-powered products — as well as backend and platform engineering.
