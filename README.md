# Brazilian Football Championship Dashboard

A Power BI dashboard analyzing matches, goals, team performance, and top goal scorers from the Brazilian Football Championship (*Campeonato Brasileiro Série A*).

## 📷 Dashboard Preview

<img width="1308" height="737" alt="brazilian-football" src="https://github.com/user-attachments/assets/bda89dda-460d-4631-8602-2cfd5f1bfd86" />

## 📊 Features & Visuals

- **Season Slicer**: Filter the entire report by `Year` (e.g., `2025`).
- **KPI Cards**:
  - **Total Matches**: Total matches played in the selected season (`380` in 2025).
  - **Total Goals**: Total goals scored (`959` in 2025).
  - **AVG Goals per Match**: Average goals per match (`2.52` in 2025).
- **Goals by Round**: Line chart showing total goals scored across each round of the championship.
- **Top Scorers**: Horizontal bar chart ranking the top goal scorers (`atleta`) by goals scored.
- **Wins by Team**: Column chart displaying total wins per club.
- **Home Wins and Away Wins**: Comparison between home victories and away victories.

## 🗂️ Data Model

The Power BI file (`brazilian-football-powerbi.pbix`) includes the following tables:

- `campeonato-brasileiro-full`: Match results, rounds, winners, home/away wins, total goals, and season year.
- `campeonato-brasileiro-gols`: Goal-level records linked to matches and players.
- `campeonato-brasileiro-cartoes`: Card-level records included in the model.

## 🚀 Getting Started

1. Clone this repository or download [`brazilian-football-powerbi.pbix`](./brazilian-football-powerbi.pbix).
2. Open `brazilian-football-powerbi.pbix` in **Power BI Desktop**.
3. Use the `Year` filter at the top-left to explore different seasons.
