# everything-counts-assignment2-25000148737

# Video Game Sales

## Project aims

The project has three core aims:

1. **To characterise the overall sales distribution** of video games and demonstrate the extent to which the market is dominated by a small number of high-performing titles.

2. **To analyse genre- and region-level patterns** using descriptive statistics, visualisation, hypothesis testing, and regression modelling.

3. **To examine indie and cosy-style games as distinct market segments**, highlighting how they differ from mainstream titles in terms of scale, variance, sustainability, and regional dynamics.

---

## Data and methods

The analysis uses the `vgsales.csv` dataset, which contains information on video game titles, platforms, publishers, genres, release years, and regional sales figures (North America, Europe, Japan, Other, and Global).

The methodological approach includes:

- **Data cleaning and validation**, including type correction, duplicate removal, and regional consistency checks.
- **Descriptive statistics** to summarise sales distributions and category frequencies.
- **Visual exploration** (histograms, boxplots, scatter plots) to reveal market concentration, genre differences, and regional relationships.
- **Inferential analysis**, including:
  - a two-sample *t*-test comparing mean global sales between genre groups;
  - a multiple linear regression model predicting log-transformed global sales from regional sales and year, with robust standard errors.
- **Segment-specific analyses** for:
  - *cosy-style games*, operationalised using genre and title-based proxies;
  - *indie or indie-adjacent games*, proxied via publisher classification.

---

## Key analytical themes

Several cross-cutting themes structure the analysis:

- **Market concentration and the “long tail”**: Most titles sell modestly, while a small minority dominate global revenue.
- **Genre as economic structure**: Genres shape not only gameplay but also typical sales ranges, variance, and risk profiles.
- **Regional power dynamics**: North America is a strong predictor of global success, but important deviations reflect region-specific appeal.
- **Indie and cosy sustainability**: Indie and cosy-style games often operate with lower average sales but contribute disproportionately to diversity, innovation, and long-tail value.
- **Limits of prediction**: Regression diagnostics highlight the difficulty of forecasting blockbuster success in creative industries.

---

## Contribution and relevance

This project contributes an **applied, industry-relevant perspective** on video game sales by:

- demonstrating how standard statistical tools can be used responsibly in a highly skewed, creative-market context;
- showing why averages and single “success metrics” are insufficient for understanding indie and cosy game ecosystems;
- bridging quantitative analysis with qualitative insights relevant to developers, publishers, platform holders, and consultants.

This is created for the Everything Counts Module on Statistics at The London Interdisciplianry School Master's, 2025 for student 25000148737. 

AI Declaration: AI has been used for part of the code generated only for the section labelled '6. Regression: modelling log(Global_Sales)', with the rest being salvaged from previous projects, self-taught or learnt with lecture  materials for this assignment. All other code and markdown notes like conclusions are my own work. 
