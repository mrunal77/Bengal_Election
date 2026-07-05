# 🇮🇳 West Bengal State Assembly Elections 2026

## 🏛️ Comprehensive Election Data
The 2026 West Bengal Legislative Assembly election was held to elect all 294 members to the West Bengal Assembly. This dataset provides the most highly detailed, candidate-level, and constituency-level breakdown of the election results available anywhere. It is an indispensable resource for political scientists, data analysts, journalists, and machine learning practitioners interested in demographic and electoral behavior.

### 🌟 Key Features of this Dataset:
- **100% Complete Coverage**: Data for all 294 constituencies.
- **Deep Granularity**: Candidate-by-candidate vote shares, including the exact split between EVM (Electronic Voting Machines) and Postal ballots.
- **Demographic Overlays**: Includes reservation status (SC/ST/General) and district-level mapping for geospatial analysis.
- **Alliance Tracking**: Pre-poll alliance mapping to understand block-voting patterns.

## 📁 File Descriptions
1. **`WestBengal2026Election_Details.csv`**: The core data engine. Tracks every candidate, their party, EVM vs Postal vote splits, total votes, and whether they won or lost.
2. **`WestBengal2026Election_Constituency_Metadata.csv`**: Macro-level data. Tracks total voter turnout percentage, district mapping, and reservation status.
3. **`WestBengal2026Election_Alliance.csv`**: Maps individual political parties to their major pre-poll alliances (NDA, INDIA, Regional Blocks).

## 🚀 Ideas for Machine Learning & Analysis
- **Turnout Prediction**: Can you predict the `Cons_vote_pct` based on the number of parties competing and the district?
- **Postal Ballot Dominance**: Is there a statistical anomaly in how Postal Votes are distributed compared to EVM votes for the winning candidates?
- **Alliance Effectiveness**: Calculate the strike rate (seats won / seats contested) for each major alliance block.
- **Geospatial Mapping**: Use the `District` column to create heatmaps of party dominance across West Bengal.

## 📜 License
Released under CC0-1.0. Free to use, modify, and distribute for any academic or commercial purpose.

*If you use this dataset, please consider leaving an **Upvote**!*
