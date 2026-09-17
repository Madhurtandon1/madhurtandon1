# Madhur Tandon
BIT Mesra CSE '27 · Full-Stack & Backend Developer · Undergraduate Researcher · ex-Intern @Voyaz


[![Madhurtandon1](https://img.shields.io/badge/@Madhurtandon1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Madhurtandon1)
[![Email](https://img.shields.io/badge/madhurrtandon123@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:madhurrtandon123@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhur-tandon-264b8b354)

I'm a Computer Science undergraduate at BIT Mesra, currently doing undergraduate research on adaptive recommendation systems. I build full-stack applications and machine learning systems, with most of my work spanning React/Next.js on the frontend and Node.js, FastAPI, PostgreSQL, and MongoDB on the backend.

On the ML side, I've worked with models and pipelines for credit risk classification, and recommendation systems. My projects include an ML-powered loan eligibility platform, and recommendation systems for personalized Hindi poetry. My research focused on adaptive user modeling and recommendation systems, including content-based, collaborative, and hybrid approaches and a Two-Tower neural retrieval model.

## Featured Projects

### Projects
1. **[Inventory Pro](https://github.com/Madhurtandon1/InventoryPro_V2)**: Multi-tenant inventory and order SaaS on the MERN stack, with JWT access/refresh auth, role checks through a middleware factory, and tenant-scoped queries plus compound unique indexes keeping each shop's data separate. Orders deduct stock inside a MongoDB transaction and stream out a PDF invoice. Benchmarked on a live Atlas cluster: replacing a save loop with one `bulkWrite` made 100-item orders **92x faster**, and running the dashboard's queries in parallel took it from 823 ms to 156 ms. [Live demo](https://inventory-pro-v2-gamma.vercel.app)
2. **[Memory Bridge](https://github.com/Madhurtandon1/Memory_Bridge_v2)**: Memory companion for people living with Alzheimer's and dementia. Users type or record a memory, and Gemini transcribes the audio, pulls out the people, places and events, and writes it up as a first-person story. A chat assistant answers questions using only what that user has stored. Runs as three services (React, Node/Express with Prisma and PostgreSQL, FastAPI), with a constant-time key check on internal calls, separate rate limits for general, auth, AI and chat traffic, and Redis caching that fails soft if the cache goes down. [Live demo](https://memory-bridge-v2.vercel.app/)
3. **[DhanSetu](https://github.com/Madhurtandon1/dhansetu2)**: Loan eligibility platform for NBCFDC schemes, built for Smart India Hackathon 2025, where we were Grand Finalists. A KNN model sorts applicants into risk bands so officers can assess people with very little paperwork. React, Node/Express, MongoDB. [Live demo](https://dhansetu2-live.vercel.app/)
4. **[Urban Retail Inventory Analytics](https://github.com/Madhurtandon1/solving_inventory_Inefficiencies-using-Advanced-SQL-Analytics_2)**: SQL case study from an IIT Guwahati challenge. Stored procedures take 109,500 rows of raw inventory data (30 products, 5 stores) through bronze and silver layers into 7 relational tables, with ROW_NUMBER() CTEs clearing out duplicate product IDs on the way. Reorder points use average daily sales over the last 30 days against a 7-day lead time, and turnover and stockout-rate queries feed a Power BI operations dashboard.
5. **[Amazon India Sales Analysis](https://github.com/Madhurtandon1/Amazon_data_analysis)**: Cleaning and EDA on 121K Amazon India fashion orders from April to June 2022 in Pandas, Seaborn and SciPy, finished as a 4-page Power BI dashboard. Sets brought in half the revenue at the highest average order value (₹833), and Maharashtra and Karnataka together placed 47% of all orders.

### Achievements
1. **Smart India Hackathon 2025 — Grand Finalist** (Dhansetu).
2. **Flipkart GRiD Gridlock 2.0 Finalist** — built Namma Traffic with team ML Baddies.

## Experience
- **Undergraduate Researcher, BIT Mesra** (Jan 2026 – present): Working under Dr. Komal Naaz on a Hindi poetry recommender: a React and Node.js app on PostgreSQL that suggests poems by cosine similarity over a Rasa-annotated dataset. I built and evaluated a Three-Profile adaptive user model and a Two-Tower neural retrieval model, which reached 98% and 98.5% Hit@5. [Code](https://github.com/Punit870/poetry-recommendation-system) · [Live](https://poetry-recommendation-system.vercel.app/)
- **Full-Stack Developer Intern, Voyaz** (Dec 2025 – Jun 2026, remote): Built the complete React frontend for [voyaz.in](https://www.voyaz.in) and shipped it on Vercel, including an EMI calculator that recomputes payments as inputs change. Also set up a WhatsApp flow that captures leads and logs them straight to Excel, so nobody types them in by hand.

## Activity

![snake gif](https://raw.githubusercontent.com/Madhurtandon1/madhurtandon1/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)
![snake gif](https://raw.githubusercontent.com/Madhurtandon1/madhurtandon1/output/github-contribution-grid-snake.svg#gh-light-mode-only)
