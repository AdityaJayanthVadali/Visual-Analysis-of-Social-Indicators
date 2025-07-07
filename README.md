
# 🌍 Global Governance & Development Analytics

**Exploring Political Systems, Inequality, Trust, and Development Outcomes Across 128 Countries**  
*By Aditya Jayanth Vadali, Aditya Seshabhatter, Vaishakh Dineshan*

---

## 📌 Project Objective

This project investigates how political freedom, corruption, trust in institutions, and wealth inequality influence the overall development and quality of life in a country. Using a dataset spanning 128 nations and 12 key governance indicators, the team performs in-depth correlation analysis and visualization using **Python**, **R**, and **Tableau**.

---

## 🗃️ Dataset Description

The dataset includes 12 columns across 128 countries:

| Column | Description |
|--------|-------------|
| `country` | Country Name |
| `gini_index` | Wealth inequality score |
| `corruption_perceptions_index` | Public corruption perception |
| `freedom_house_democracy_index` | Measure of democratic freedoms |
| `hdi` | Human Development Index |
| `press_freedom_index` | Press censorship/freedom score |
| `economist_democracy_index` | Democracy score (Economist) |
| `populism_index` | Populism and polarization metric |
| `effective_coverage_of_health_services_index` | Public healthcare reach |
| `trust_in_news_media_index` | Trust in news |
| `trust_in_government_index` | Trust in government |
| `trust_in_science_index` | Trust in scientific institutions |

---

## 🔍 Exploratory Analysis Highlights

- Countries with **higher GINI index** (more inequality) tend to have:
  - Lower HDI (correlation: **-0.33**)
  - Higher corruption (**-0.40**)
  - Lower trust in government (**-0.43**)

- **Corruption** negatively correlates with human development (**-0.69**) and effective health coverage (**-0.79**).

- **Trust indexes** (news, science, government) are highly interconnected (**0.59–0.62** correlation).

- Countries with **higher HDI** exhibit:
  - Better democracy (freedom house and economist indexes)
  - Better healthcare coverage
  - Lower inequality

- **Populist countries** tend to have higher corruption (**+0.47**) and lower trust.

---

## 🧪 Tools Used

- **Python (seaborn, matplotlib, pandas)** – 3D scatter plots, correlation matrix
- **R (ggplot2, countrycode)** – Bar charts, continent-level press freedom
- **Tableau** – HDI choropleth, trust heatmaps, bubble charts for corruption

---

## 📊 Key Visualizations

### 1. Correlation Heatmap

![Correlation Heatmap](extracted_images/Visual Analytics Project (1)_page4_img1.jpeg)

---

### 2. HDI Choropleth by Country

![HDI Map](extracted_images/Final Paper (1)_page1_img1.jpeg)

- European countries show the highest HDI.
- African nations show lower HDI and GINI.

---

### 3. GINI Index vs Health Coverage

![GINI vs Coverage](extracted_images/Final Paper (1)_page1_img2.png)

- Health coverage drops slightly as inequality increases (for GINI < 50).

---

### 4. Trust vs Trust: Government & News Media

![Scatterplot: Trust](extracted_images/Final Paper (1)_page2_img1.png)

- Trust in news and government are highly correlated.
- Countries like China, Pakistan show high trust; U.S., Germany show lower trust.

---

### 5. Press Freedom by Country

![Press Freedom](extracted_images/Final Paper (1)_page2_img2.png)

- Oceania and Northern Europe lead with high press freedom.
- Asia has the lowest regional average.

---

### 6. Corruption Perception by Country

![Corruption](extracted_images/Final Paper (1)_page2_img3.png)

- New Zealand has highest CPI (~88).
- South Sudan ranks lowest (~12).
- Corruption correlates inversely with HDI.

---

### 7. Income Inequality vs Populism

![GINI vs Populism](extracted_images/Final Paper (1)_page2_img4.jpeg)

- Weak positive correlation; most countries cluster in the mid-range.

---

## 🧠 Insights & Use Cases

**Potential Applications:**
- Policy reform and governance improvement
- Cross-country benchmarking for development agencies
- Investment and geopolitical risk scoring
- Media strategy and freedom-of-press advocacy
- Public health planning with trust and inequality dimensions

---

## 📚 Technical Summary

- **Python** was used for complex scatter plots and matrix analysis using `matplotlib`, `numpy`, and `pandas`.
- **R** created layered bar plots and grouped visualizations by continent using `ggplot2` and `countrycode`.
- **Tableau** integrated choropleth and bubble plots, enriching narrative and geographic context.
- Data was enhanced with continent tags to assess regional variation and generalize visual narratives.

---

## 🏁 Final Thoughts

This project revealed rich interrelations between trust, governance, freedom, and development. While correlation ≠ causation, the visual and quantitative synthesis helps policymakers and analysts uncover levers that improve a country’s trajectory.

---

## 🧑‍💻 Contributors

- **Aditya Jayanth Vadali** – av8317@rit.edu  
- **Aditya Seshabhatter** – as2797@rit.edu  
- **Vaishakh Dineshan** – vd8521@rit.edu

---

> 📁 Source data: `country_information(1).csv`  
> 📄 Project components: [Final Paper](Final%20Paper%20(1).pdf), [Presentation](Visual%20Analytics%20Project%20(1).pdf), [Notebook](FinalProject.ipynb)
