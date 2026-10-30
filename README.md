# Formula 1 Race Intelligence

Formula 1 Race Intelligence is an interactive data visualization project developed using Tableau. It aims to explore and understand different aspects of Formula 1 racing by presenting important information through graphical representations. The project covers team and driver performance, tyre-compound analysis, Grand Prix hosting statistics, podium achievements, and race reliability. These visualizations make it easier to identify patterns, compare results, and understand performance trends throughout the available seasons.

## Project Scenarios

### 1. F1 Team Performance Strategist

This scenario focuses on evaluating team and driver performance and understanding how different strategies influence race outcomes.

- **Constructor Championship Points Trend:** presents a season-wise comparison of championship points earned by different Formula 1 teams.
- **Tyre Compound Performance by Circuit Type:** analyzes podium outcomes in relation to the starting tyre compound and the type of circuit.
- **Driver Talent and Performance Ranking:** compares driver performance during a selected season using available championship statistics.

### 2. Motorsport Broadcast Analyst

This scenario highlights important statistics and achievements that can help explain Formula 1 history and performance to viewers.

- **All-Time Driver Points Leaderboard:** ranks drivers according to the total championship points accumulated across the available seasons.
- **Countries Hosting the Most Grand Prix Rounds:** displays the countries that have hosted the greatest number of Grand Prix races, based on distinct race counts.
- **Podium Achievements by Driver and Team:** provides a comparison of podium finishes achieved by individual drivers and their associated teams.

### 3. F1 Technical Regulation Analyst

This scenario examines race reliability and retirement-related information to identify patterns in driver and team performance.

- **DNF Reasons by Team:** illustrates the recorded reasons for races not finished by drivers from different teams.
- **DNF Patterns by Circuit Type and Driver:** studies how retirement occurrences are distributed among drivers and different circuit types.
- **Driver and Team Reliability Trend:** compares race-completion rates across seasons to provide an overview of driver and team reliability.

## Dataset Description

The project uses multiple data tables to cover different aspects of Formula 1 racing. Each sheet contributes specific information required for the visual analysis.

| Sheet | Description |
|---|---|
| `circuits` | Contains details and relevant information about Formula 1 circuits. |
| `championship_standings` | Stores driver championship standings and points earned during different seasons. |
| `lap_intelligence` | Provides lap-level information that can be used for more detailed race analysis. |
| `qualifying_results` | Contains the results and information recorded during qualifying sessions. |
| `race_results` | Includes race outcomes, driver and team details, finishing positions, tyre information, and retirement-related records. |

## Sharing Through Tableau Public

The completed Tableau project can be shared online through Tableau Public, allowing other users to access and explore the visualizations through a web browser.

1. Open the saved workbook using Tableau Public Edition.
2. Sign in with an existing Tableau Public account or create a free account.
3. From the menu, navigate to **Server → Tableau Public → Save to Tableau Public** (the option's wording may vary depending on the software version).
4. After publishing is complete, visit your Tableau Public profile to find the uploaded visualization.
5. Select **Share** to copy the public URL and share the project with others.

## Tools Used

The following tools and platforms were used in developing and managing the project:

- **Tableau** — used to build interactive charts, visualizations, dashboards, filters, and story presentations.
- **Microsoft Excel / Spreadsheet Data** — used for viewing, organizing, inspecting, and preparing the dataset for analysis.
- **GitHub** — used for maintaining the project repository, managing files, tracking changes, and sharing project resources.

## Notes and Limitations

- The analysis is restricted to the seasons and records available in the supplied dataset. Information from the latest season may be incomplete, which can affect comparisons and overall statistics.
- Championship standings are recorded at the driver level. Therefore, team-level point calculations depend on correctly identifying the team associated with each driver during the respective season.
- The country hosting a Grand Prix is different from the nationality of the participating driver. Any analysis based on driver nationality requires a reliable nationality field or a separately verified reference table.
- DNF analysis depends on the status categories and retirement information recorded in the dataset. These classifications should be checked carefully before drawing conclusions.
- Combining tables that contain different levels of detail can result in duplicated records and inaccurate totals. Row counts and aggregated values should be checked after joining tables, while Tableau relationships should be preferred where appropriate.
- The visualizations are intended to identify patterns, comparisons, and relationships within Formula 1 data. However, the trends displayed do not independently establish the underlying causes of particular race outcomes or retirement events.
