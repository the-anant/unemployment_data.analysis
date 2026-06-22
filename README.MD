# 📉 Unemployment Analysis with Python
### *Because behind every percentage, there's a real person's story.*

---

## 🌍 What is this project about?

Have you ever wondered what actually happened to millions of Indians when the country went into lockdown in March 2020?

This project is my attempt to answer that — not through news headlines or political debates, but through **data**.

Using a real-world unemployment dataset, I dug into how unemployment rates shifted across Indian states, how Covid-19 hit the job market like a wrecking ball, and how the country slowly started recovering. The numbers tell a story that's hard to ignore.

---

## 🎯 What I set out to do

- Understand how unemployment trends changed over time in India
- Visualize the **devastating impact of Covid-19** on the job market
- Compare unemployment rates **state by state** across India
- Find seasonal patterns and hidden spikes in the data
- Present findings that could actually mean something — not just charts for the sake of charts

---

## 🛠️ Tools & Technologies Used

| Tool | Why I used it |
|------|--------------|
| **Python** | The backbone of the entire analysis |
| **Pandas** | For wrangling and cleaning the messy real-world data |
| **Matplotlib & Seaborn** | To turn raw numbers into visuals that actually make sense |
| **Plotly** | For interactive charts you can actually explore |
| **Jupyter Notebook** | Because data science belongs in a notebook — clean, step by step |

---

## 📁 Project Structure

```
CodeAlpha_UnemploymentAnalysis/
│
├── 📓 unemployment_analysis.ipynb    # The main notebook — start here
├── 📊 unemployment_data.csv          # Dataset used for analysis
├── 📁 plots/                         # All saved visualizations
│   ├── unemployment_over_time.png
│   ├── region_wise_comparison.png
│   ├── covid_impact_chart.png
│   └── heatmap_region_month.png
└── 📄 README.md                      # You're reading it right now 😄
```

---

## 🔍 What the Analysis Covers

### 1. 📈 Unemployment Over Time
A time-series line chart that shows the overall average unemployment rate across India month by month. The spike in **April–May 2020** is impossible to miss.

### 2. 🗺️ State-by-State Breakdown
Not all states were hit equally. Haryana, Jharkhand, and Tripura faced the worst — while southern states like Karnataka and Kerala held on relatively better.

### 3. 😷 Pre-Covid vs During-Covid
A direct comparison of average unemployment rates before and after March 2020. The numbers are stark — the pandemic wiped out jobs at a scale India hadn't seen in decades.

### 4. 🌡️ Heatmap: Region × Month
A heatmap that shows which states struggled in which months. It gives a complete picture at a glance — you can immediately spot the hotspots.

---

## 💡 Key Insights I Found

> **1.** Unemployment rate jumped from ~8% pre-lockdown to over **23%** during April–May 2020 — the worst months of the first lockdown.

> **2.** States like **Haryana** consistently topped the unemployment charts, even before Covid.

> **3.** The **Labour Participation Rate** also dropped during lockdowns — meaning people weren't just losing jobs, they were giving up looking for one.

> **4.** By **July–August 2020**, the numbers started recovering as unlock phases began — but never fully returned to pre-Covid levels within the dataset period.

> **5.** There's a clear **urban vs rural divide** — states with more urban population saw sharper spikes but also faster recoveries.

---

## 🚀 How to Run This Yourself

**Step 1:** Clone this repo
```bash
git clone https://github.com/yourusername/CodeAlpha_UnemploymentAnalysis.git
cd CodeAlpha_UnemploymentAnalysis
```

**Step 2:** Install the required libraries
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

**Step 3:** Launch the notebook
```bash
jupyter notebook unemployment_analysis.ipynb
```

**Step 4:** Run all cells top to bottom and see the story unfold 📊

---

## 📊 Dataset

- **Source:** CodeAlpha Internship Dataset (provided by the organization)
- **Coverage:** Indian states, monthly unemployment data (2019–2020)
- **Key Columns:** Region, Date, Estimated Unemployment Rate (%), Estimated Employed, Labour Participation Rate (%)

---

## 🎓 What I Learned from This

Honestly, I went in thinking this was just a data visualization task. But I came out with a deeper understanding of:

- How **economic shocks** ripple through different regions differently
- Why **data cleaning matters** more than any fancy model
- How to tell a compelling story with charts — not just show pretty colors
- The real human cost behind a simple percentage on a chart

---

## 👤 About Me

**Anant** — Freelance Web Developer & Data Enthusiast from India 🇮🇳

Passionate about using technology — whether it's building websites or analyzing data — to solve real-world problems and create things that matter.


---

## 🏢 About the Internship

This project was completed as part of the **CodeAlpha Data Science Internship Program**.

CodeAlpha is a software development company focused on data-driven innovation and AI solutions. This internship gave me hands-on exposure to real datasets and practical machine learning workflows.

🌐 [www.codealpha.tech](https://www.codealpha.tech)

---

## 📜 License

This project is open for learning and reference. If you use any part of it, a small credit would be genuinely appreciated. 🙏

---

*Made with curiosity, Python, and way too much chai ☕*