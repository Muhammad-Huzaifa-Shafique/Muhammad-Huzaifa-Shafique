# Muhammad Huzaifa Shafique

**AI & Machine Learning graduate student** | M.S. in Artificial Intelligence (4.0/4.0 GPA), Pittsburg State University, Kansas, USA

I design, build and test retrieval-augmented generation (RAG) systems, local large language model (LLM) tools and AI-powered cybersecurity tools in Python. I am open to AI/ML opportunities.

**Connect:** [LinkedIn](https://www.linkedin.com/in/muhammad-huzaifa-shafique) (my full CV is in the Featured section)

## What I work on

- **Retrieval-augmented generation (RAG):** assistants that answer questions from trusted documents and cite their sources
- **Local LLMs:** running models such as Llama 3.1 on my own computer, so no data is sent to a cloud AI service
- **AI for cybersecurity:** tools that help check suspicious links, emails and files, plus a penetration-testing knowledge assistant

## Projects

### [CyberAI: Threat Triage Tool](https://github.com/Muhammad-Huzaifa-Shafique/CyberAI)

A Python tool that checks whether a link, email or PDF looks safe and returns a **Clean**, **Suspicious** or **Malware** verdict with the reasons behind it. It combines VirusTotal reports, DNS and domain data, spam blocklists and email checks (look-alike sender domains, SPF/DMARC records, DKIM signatures, phishing wording, Reply-To mismatch) into one weighted risk score. It works from the command line or a Flask web page, exports PDF reports and saves every result to a local history.

*Python, Flask, SQLite, VirusTotal API*

### [Interactive Data Visualization Dashboard (Gapminder)](https://github.com/Muhammad-Huzaifa-Shafique/Dashboard)

An interactive report with two animated charts on the Gapminder dataset (1,704 country-year records, 142 countries, from 1952 to 2007). Population-weighted life expectancy rose on every continent, led by Asia (42.9 to 69.4 years) and Africa (38.8 to 54.6 years). [Open the live report](https://muhammad-huzaifa-shafique.github.io/Dashboard/Animation_data.html)

*R, Quarto, Plotly*

### Penetration Testing Knowledge Assistant (local RAG)

A local, offline assistant that answers penetration-testing questions from public documentation (the HackTricks wiki and security-tool manual pages) using Llama 3.1 8B through Ollama, with numbered source citations. I compared three embedding indexes of 22,720 chunks each on 7 test questions, and wrote a source checker (covered by 58 unit tests) that verifies every citation points to a passage that was actually retrieved. The source code is private for now.

*Python, Ollama, Llama 3.1, Chroma*

## Skills

- **AI and machine learning:** machine learning, LLMs, generative AI, RAG, NLP, embeddings, vector databases (Chroma), prompt engineering, retrieval evaluation, local LLM deployment (Ollama)
- **Programming and data:** Python, SQL, R, Pandas, NumPy, scikit-learn, statistical analysis, REST APIs, Git
- **Cybersecurity:** penetration testing, vulnerability assessment, threat intelligence, Kali Linux, Nmap, Metasploit

## Background

- **Graduate Teaching Assistant**, Pittsburg State University (2026 to present)
- **M.S. in Artificial Intelligence**, Pittsburg State University (2025 to present)
- **B.S. in Physics**, COMSATS University Islamabad, Pakistan (2019 to 2023)
- **Certifications:** Claude 101 and AI Fluency: Framework & Foundations (Anthropic); Data Science and Machine Learning using Python (Lahore University of Management Sciences)
