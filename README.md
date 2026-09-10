<img width="1255" height="833" alt="Screenshot 2026-09-03 141113" src="https://github.com/user-attachments/assets/23fa12d3-66bc-4974-90a0-9a441e104b39" />


[Summary_organized.md](https://github.com/user-attachments/files/32038769/Summary_organized.md)



<!-- Start of picture text -->
a Ledger<br>32 0) I 36 #32 Rings<br>= f<br><!-- End of picture text -->



<!-- Start of picture text -->
a<br>| :<br><!-- End of picture text -->

e 

e 

e 

e 

e 

e e 

e 

1. **Area chart** — total stock over time 

2. **Horizontal bar chart** — stock by category, latest date 

3. **Pie chart** — stock composition, latest date 

4. **Grouped bar chart** — added / sold / repaired, per entry (last 15 shown) 

5. **Stacked area chart** — each category's share of stock over time 

# Filters 

- **Date range** — quick filters for last 7, 14, 30 days, or all time 

- **Category toggles** — chips to show/hide individual categories; KPIs and charts recalculate live from whichever categories are active 

**Entries table** — the 10 most recent dated rows in range, for a quick raw-numbers check alongside the charts 

# Tech 

Plain HTML/CSS/JS, <u>Chart.js (https://www.chartjs.org/) for charts, and PapaParse (https://www.papaparse.com/) to parse</u> the CSV pulled from Google Sheets. No build step, no backend — open the HTML file in any browser. 

# Setup 

1. In Google Sheets: **File → Share → Publish to web** , select the correct sheet tab, format **CSV** , and publish. 

2. Drop the resulting link into the `CSV_URL` / sheet-connect step in the HTML file. 

3. Host the file anywhere static (GitHub Pages works well) — Google's publish link needs `https://` , not a local file, to sync reliably. 

