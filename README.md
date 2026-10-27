
<div align="center">

# 🚦 ROAD ACCIDENT ANALYSIS DASHBOARD

### *the numbers behind the road*

**One dataset. Different perspectives. Better questions.**

An interactive Excel dashboard exploring road accident patterns across years, states, vehicle types, accident severity, and lighting conditions.

[📊 View Dashboard](#-the-dashboard) · [🔎 Explore the Analysis](#-reading-the-data) · [🧰 Tools & Techniques](#-behind-the-dashboard) · [📁 Get the Files](#-inside-the-repository)

<br>

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Data_Storytelling-F2B705?style=flat-square)
![Project Type](https://img.shields.io/badge/Project-Interactive_Dashboard-145374?style=flat-square)

</div>

---

## 🟡 Before we get into the numbers…

Road accidents are often reduced to a single statistic. But a total by itself doesn't tell us *when* accidents were recorded, *where* patterns differ, or how the distribution changes across vehicle types and accident severity.

That's where this project comes in.

**Road Accident Analysis Dashboard** is an Excel-based data analytics project built to make accident data easier to explore through charts, comparisons, and interactive filters.

Developed as part of my data analytics learning journey, this project gave me an opportunity to apply spreadsheet-based analytical techniques and turn structured data into a visual dashboard.

Instead of presenting one static answer, the dashboard offers multiple ways to look at the data.

> The point isn't to make the numbers look impressive. It's to make them easier to question, compare, and understand.

---

## 📊 The Dashboard

<div align="center">

![Road Accident Analysis Dashboard — Excel dashboard preview](Dashboard.jpg)

*The dashboard brings yearly trends, state-level comparisons, vehicle types, accident severity, and lighting conditions into one view.*

</div>

Built in Microsoft Excel, the dashboard brings multiple views of accident data together in one place.

### A quick look at what's inside

| Dashboard view | What it helps explore |
|---|---|
| 📈 Year-wise trend | How recorded accident counts vary across 2018–2023 |
| 🗺️ State-wise comparison | Differences in recorded accident counts across states |
| 🚘 Vehicle type | How accident counts are distributed across vehicle categories |
| 🩹 Accident severity | The distribution of recorded accidents by severity category |
| 🌗 Lighting conditions | Differences across daylight, dusk, dawn, and dark conditions |
| 🎛️ Interactive filters | Narrowing the dashboard view by available categories |

These describe the views visible in the dashboard preview, not conclusions about accident causes or road safety outcomes.

---

## 🔎 Reading the Data

Here's the story the dashboard is designed to help investigate.

<details>
<summary><strong>📈 01 — The timeline: 2018 to 2023</strong></summary>

The year-wise line chart provides a view of recorded accident counts across six years.

It offers a starting point for questions such as:

- How does the recorded count change from year to year?
- Which years show higher or lower values in the displayed data?
- Does the pattern change when the year filter is adjusted?

The chart helps explore recorded trends. It does not, by itself, explain why a change occurred.

</details>

<details>
<summary><strong>🗺️ 02 — The geography: state-wise comparisons</strong></summary>

The horizontal bar chart compares recorded accident counts across states.

This view makes it easier to compare categories within the selected dataset and examine how the displayed distribution changes.

Comparing raw counts is not the same as comparing accident risk. Population, traffic volume, reporting practices, and other context would be needed to interpret risk properly.

</details>

<details>
<summary><strong>🚘 03 — The vehicles: categories and severity</strong></summary>

The stacked column chart groups recorded accident counts by vehicle type and separates the displayed values by accident severity.

The dashboard includes categories such as auto-rickshaws, buses, cars, cycles, pedestrians, trucks, and two-wheelers.

This view supports comparisons across categories and severity levels. It should not be treated as proof that a particular vehicle type causes more accidents without additional context.

</details>

<details>
<summary><strong>🩹 04 — The severity breakdown</strong></summary>

The dashboard includes a separate chart for the distribution of accident counts across the displayed severity categories:

- Fatal
- Minor
- Serious

Viewing these categories together helps distinguish the overall count from its severity breakdown.

The exact proportions and totals should be read from the workbook with its current filters applied.

</details>

<details>
<summary><strong>🌗 05 — The conditions: lighting</strong></summary>

The lighting-conditions chart compares recorded accident counts across categories visible in the dashboard, including daylight, dusk, dawn, and dark conditions.

It creates an opportunity to ask how the displayed counts differ by lighting category.

However, the chart alone cannot establish that lighting caused an accident or determine the relative risk of travelling under a particular condition.

</details>

<details>
<summary><strong>🎛️ 06 — The interactive layer</strong></summary>

The dashboard preview shows filtering controls for:

- Year
- State name
- Accident severity
- Vehicle type involved
- Lighting conditions

These controls make the workbook more useful than a static chart: they allow the displayed data to be narrowed to selected categories.

For the interactive experience, open the Excel workbook rather than relying only on the screenshot.

</details>

---

## 🧰 Behind the Dashboard

This project uses spreadsheet-based analysis and visualisation to turn structured data into an interactive reporting experience.

| Tool or technique | Role in the project |
|---|---|
| Microsoft Excel | Workbook and dashboard environment |
| PivotTables | Organising and summarising data for analysis |
| PivotCharts | Presenting comparisons and trends visually |
| Interactive filters / slicers | Exploring selected categories |
| KPI and chart layout | Bringing multiple analytical views together |

The emphasis is on making the information accessible: a reader should be able to move from the overall picture to a more focused comparison without needing to interpret a raw table alone.

The list above reflects the techniques described for the project and visible in its dashboard. It is not a claim that every possible Excel analytics technique was used.

---

## 🧭 A Small Data-Reading Guide

A dashboard can make patterns easier to spot, but reading those patterns carefully matters just as much.

| When you see… | Remember to ask… |
|---|---|
| A higher count | Higher compared with which category or period? |
| A year-to-year change | Are the underlying periods and filters comparable? |
| A state with a larger count | How would population or traffic exposure affect the comparison? |
| A difference between severity categories | What does the category represent in the source data? |
| A difference across lighting conditions | Are these raw counts, rates, or something else? |

This is an exploratory dashboard, not a causal study or a predictive model. Its purpose is to help users examine the recorded data and form better questions.

---

## 📁 Inside the Repository

```text
Road-Accident-Analysis-Dashboard/
│
├── Dashboard.jpg
│   └── Static preview of the dashboard
│
├── Road_Accident_Dashboard_Project.xlsx
│   └── Excel workbook and interactive analysis
│
└── README.md
    └── Project story, dashboard guide, and documentation
```

### Want to explore it yourself?

**1. Start with the preview**

[Open Dashboard.jpg](Dashboard.jpg)

A quick visual overview of the dashboard layout and the categories it explores.

**2. Get the Excel workbook**

[Open Road_Accident_Dashboard_Project.xlsx](Road_Accident_Dashboard_Project.xlsx)

On the workbook's GitHub page, use the download option to save the file.

**3. Explore it in Microsoft Excel**

Open the downloaded workbook in Excel and use the available interactive filters to investigate different views of the data.

**4. Keep the distinction in mind**

`Dashboard.jpg` is a static image. The Excel workbook is the file to use when you want to interact with the dashboard.

---

## 💡 Why This Project?

Because data analysis isn't only about calculations.

It's also about deciding how information should be organised, which comparisons are useful, and how to make a complex dataset easier to explore.

This project brings together practical data analytics concepts:

- Summarising structured data
- Comparing categories and time periods
- Exploring accident severity and vehicle-related patterns
- Designing charts for easier interpretation
- Using interactive filters to investigate the data

Excel makes this kind of exploration approachable, while the dashboard format gives the analysis a more visual, usable form.

And one reminder worth keeping: **a chart can reveal a pattern without explaining its cause.** Good analysis knows the difference.

---

## 🎓 Part of My Data Analytics Journey

This project is connected to my **Data Analytics Trainee training through Accenture Anudip Foundation (July–November 2024)**.

The training was part of my journey into working with data, exploring analytical tools, and learning how to present information through practical projects.

Building dashboards like this helped me connect analytical concepts with hands-on work: organising information, comparing categories, and communicating what a visualisation can — and cannot — tell us.

For me, this project is more than a collection of charts. It's one of the steps that helped me practise turning data into something people can explore and understand.

---

## 🔭 If I Were to Take It Further…

The current dashboard offers a foundation for further exploration. Some possible next steps:

- 📍 Add a more detailed geographical view, if suitable location data is available.
- 📊 Build a Power BI version for a different dashboard experience.
- 📉 Add carefully defined comparison metrics and year-over-year calculations.
- 🔍 Investigate additional relationships between accident categories.
- 📝 Document validated findings with exact values, clear filters, and appropriate context.
- 🔄 Explore a repeatable data-refresh workflow.

These are future possibilities, not features claimed to exist in the current workbook.

---

## 👩🏻‍💻 A Little About the Developer

<div align="center">

### Sneha Singh

**M.Sc. Computer Science @ DAVV**  
*Data Analytics · Software Development · Practical Technology Projects*

</div>

I enjoy taking concepts beyond theory and turning them into projects people can actually explore and use.

From spreadsheet dashboards to Python-based exploratory analysis, I'm interested in finding useful ways to work with data, recognise patterns, and communicate what the numbers reveal.

This dashboard is one experiment in that journey — built around curiosity, visualisation, and the habit of asking better questions.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-myselfsneha-181717?style=flat-square&logo=github)](https://github.com/myselfsneha)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/singh--sneha/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore-145374?style=flat-square)](https://myselfsneha.github.io/sneha-portfolio/)

</div>

---

<div align="center">

### 🚦 Built with Excel. Driven by curiosity.

*The dashboard gives us a view of the numbers. Asking the right questions gives those numbers context.*

**Thanks for stopping by!** 🌻

</div>
