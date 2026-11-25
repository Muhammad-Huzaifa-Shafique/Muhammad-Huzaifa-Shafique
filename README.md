# Muhammad Huzaifa Shafique

**AI and machine learning graduate student, looking for AI/ML engineer roles.** Master of Science in Technology with an emphasis in AI, Pittsburg State University (Kansas, USA). GPA 4.0, graduating December 2026.

I build and test machine-learning and retrieval-augmented generation (RAG) systems in Python, and I publish how well they work, including where they fall short.

[Portfolio site](https://muhammad-huzaifa-shafique.github.io) | [How I build](https://muhammad-huzaifa-shafique.github.io/method.html) | [LinkedIn](https://www.linkedin.com/in/muhammad-huzaifa-shafique) (my full CV is in the Featured section)

## Main projects: AI and machine learning

| Project | What it shows for an AI/ML role | Built with |
|---|---|---|
| [Casefile](https://github.com/Muhammad-Huzaifa-Shafique/Penetration_Testing), a local RAG assistant ([explainer](https://muhammad-huzaifa-shafique.github.io/casefile.html)) | A full retrieval pipeline over 22,720 chunks, three embedding setups compared, a five-rule system prompt, and a citation checker with 58 unit tests | Python, Ollama, Llama 3.1 8B, Chroma |
| [CyberAI](https://github.com/Muhammad-Huzaifa-Shafique/CyberAI), threat triage and an ML pipeline ([explainer](https://muhammad-huzaifa-shafique.github.io/cyberai.html)) | A triage tool, plus an architecture note on its pipeline: logistic regression, Isolation Forest anomaly detection, a drift monitor, a human-review queue and a chat assistant that shows its evidence. Accuracy is not measured, and the README says why | Python, scikit-learn, Flask, SQLite, VirusTotal API |
| [Sales Forecasting Neural Network](https://github.com/Muhammad-Huzaifa-Shafique/Sales-Forecasting-Neural-Network) ([explainer](https://muhammad-huzaifa-shafique.github.io/forecasting.html)) | A neural network tested against four baselines on 12 months it never saw, with about 12% lower error than the best baseline. A version that made results worse stays in the results table | Python, scikit-learn, pandas |
| [Gapminder Dashboard](https://github.com/Muhammad-Huzaifa-Shafique/Dashboard) ([live report](https://muhammad-huzaifa-shafique.github.io/Dashboard/Animation_data.html), [explainer](https://muhammad-huzaifa-shafique.github.io/dashboard.html)) | Exploratory analysis and clear reporting: population-weighted life expectancy rose on every continent, led by Asia (42.9 to 69.4 years) | R, Quarto, Plotly |

## Data engineering projects (the step before modeling)

| Project | What it shows | Built with |
|---|---|---|
| [Oklahoma Legislature Vote Extractor](https://github.com/Muhammad-Huzaifa-Shafique/Oklahoma-Legislature-Vote-Extractor) ([data checks](https://muhammad-huzaifa-shafique.github.io/data-engineering.html)) | A team project with classmates; my part was the House votes. I checked the output against its own counts: seat counts add up on 99.99% of votes, but member rows cover about 76% of counted seats, and I have not traced why | Python, aiohttp, asyncio |
| [Fixed-Width Data Extractor](https://github.com/Muhammad-Huzaifa-Shafique/Fixed-Width-Data-Extractor) | Built with a classmate: turns messy fixed-width reports into clean Excel tables | Python, pandas, openpyxl |

Each project README says what the project shows and where it falls short.

## How I build

- **Prompts with checks behind them.** Casefile's system prompt has five rules, including saying what is missing instead of guessing and treating retrieved text as data, not instructions. A citation checker confirms that cited passages exist and quoted commands match. [Read the real prompts](https://muhammad-huzaifa-shafique.github.io/method.html).
- **Baselines first.** The forecasting network is judged against four simple methods on months it never saw.
- **Limits published.** Every project says what it does not show.

## Skills

- **Machine learning and LLMs:** scikit-learn (neural networks, logistic regression, Isolation Forest, ensembles), time-series features, model evaluation against baselines, anomaly detection, drift monitoring, RAG, embeddings and vector search (Chroma), TF-IDF retrieval, prompt engineering, local LLMs (Ollama, Llama 3.1)
- **Python and data:** Python, Pandas, NumPy, SQL, R, REST APIs, Flask, SQLite, unit testing, Git
- **Security:** penetration testing, vulnerability assessment, threat intelligence, Kali Linux, Nmap, Metasploit

## Background

- **Graduate Teaching Assistant**, Pittsburg State University (Aug 2026 to present)
- **Master of Science in Technology, emphasis in AI**, Pittsburg State University (Aug 2025 to Dec 2026, expected)
- **Laboratory Teaching Assistant**, COMSATS University Islamabad (Aug 2023 to Jan 2024)
- **B.Sc. in Physics**, COMSATS University Islamabad, Pakistan (2019 to 2023)
- **Certifications and badges:** Claude 101 and AI Fluency: Framework & Foundations (Anthropic); Data Science and Machine Learning using Python (Lahore University of Management Sciences); Google Developer Program badges [Learning](https://developers.google.com/profile/badges/recognitions/learnings) and [Joined the Google Developer Program](https://developers.google.com/profile/badges/profile/created-profile)
