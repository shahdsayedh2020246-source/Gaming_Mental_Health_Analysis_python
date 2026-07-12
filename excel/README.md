# 📊 Advanced Microsoft Excel Analytics Workspace

This directory contains the core Microsoft Excel analytical engineering artifacts for the **Gaming & Mental Health Project**. It features a production-grade relational Data Model built via Power Query, custom DAX measures, and a multi-view interactive dynamic Dashboard designed with a modern futuristic dark/neon UI.

---

## 📐 Database Architecture & Data Modeling
To transition from a flat-file dataset into an optimized analytical environment, a highly scalable relational database structure was built based on a custom **Star Schema** model directly inside Excel's Data Model.
* **Architecture:** Formulated a central `fact_table` capturing numeric keys and continuous variables linked directly via verified Foreign Keys (1-to-many relationships) to distinct Dimension tables (`Dim_Player`, `Dim_Game`, `Dim_Sleep`, `Dim_PhysicalStatus`, `Dim_Addiction`).
* **Data Integrity:** All relationship keys were validated to eliminate any structural redundancy and optimize cross-filtering performance across all dashboard views.

### 🗺️ Data Model Schema
<img src="Excel Schema.png" alt="Star Schema Design" width="100%">

---

## 📊 Interactive Analytics Dashboards & Deep Insights

The analytical findings were synthesized across three high-impact dashboard views tailored for deep exploration. All views are fully synchronized using advanced cross-filtering slicers:

### 1️⃣ View A: Player Profile & Platform Engagement
*Focuses on general demographics, total player distribution, playtime across different games, financial spending, and productivity scores.*

<img src="Excel Dashboard 1.png" alt="Player Profile Dashboard" width="100%">

#### 🔍 Deep Insights & Analytics:
* **Demographics & Volume:** The dataset tracks **1.0k total players** who collectively account for **6.2k daily gaming hours** and a massive total expenditure of **7.2m** across platforms. The gender split shows a heavy male dominance at **66%**, compared to **32% female** players.
* **Age & Engagement:** The distribution of gaming time by age group is tightly balanced, with **Young Adults leading at 35%**, followed closely by **Teenagers (34%)** and **Adults (31%)**.
* **Game Popularity by Hours:** *Elden Ring* commands the highest engagement with **369 total hours**, closely followed by *Starcraft II* (**355 hours**) and *Dota 2* (**332 hours**).
* **Financial Spending:** Monetization is highly successful in the **Strategy, MOBA, and MMO genres**, with each pulling in **1.1m** in total spending, while Role-Playing Games (RPGs) follow at **999.5k**.

---

### 2️⃣ View B: Addiction Risk & Mental Health
*Analyzes the deep correlations between gaming addiction levels, social isolation, and emotional stability.*

<img src="Excel Dashboard 2.png" alt="Addiction Risk Dashboard" width="100%">

#### 🔍 Deep Insights & Analytics:
* **Addiction Levels by Age:** The **Young Adult** segment exhibits the highest vulnerability to psychological strain, recording **312 players categorized with Low-to-Moderate addiction risks** and a noticeable surge in severe cases compared to Older Adults.
* **Social Impact (F2F vs. Isolation):** There is a clear, quantifiable inverse relationship between face-to-face (F2F) social interaction and gaming intensity. On average, the cohort retains **7.7 F2F social hours** against a **3.9 social score**. However, as addiction risk scales from "Low" to "Severe", the average social isolation score spikes dramatically while actual F2F hours drop down.
* **Mood & Spending Behavior:** Financial expenditure acts as an emotional coping mechanism; total spending shows an upward trajectory, peaking significantly when players experience emotional states like **Anxious, Irritable, and Depressed**.
* **Emotional Gaming Triggers:** Negative emotional states directly prolong sessions. Players suffering from **Anxiety, Irritability, Restlessness, and Depression** average the maximum limit of **7 hours of gaming time**, using games as an escapism mechanism, whereas "Excited" or "Normal" states account for only **4 hours**.

---

### 3️⃣ View C: Healthcare & Physical Well-being
*Tracks physical health indicators including sleep quality, physical pain metrics, and lifestyle balances.*

<img src="Excel Dashboard 3.png" alt="Healthcare Dashboard" width="100%">

#### 🔍 Deep Insights & Analytics:
* **Sleep Deprivation:** The average sleep duration across the entire player base sits at a restrictive **6 hours**, mirroring the average **6.15 daily gaming hours**. Sleep quality metrics reveal that a vast majority of heavy gamers report "Insomnia", "Poor", or "Very Poor" sleep cycles, with "Good" sleep being a minority.
* **Physical Strain & Ergonomics:** A staggering **43% of the analyzed population is at High Risk for Physical Pain**
