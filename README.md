# FIFA World Cup Dashboard

## 1. Overview

The Tableau dashboard displays historical analytics on all FIFA World Cup tournaments from 1930 to 2014. It shows a visualization of tournament statistics, team performance, host countries, winners, and even match details for all World Cups. It is possible to explore all World Cups and understand trends in goals scored, team participation, and even hosting rights.

## 2. Purpose

This dashboard will be a resource for sports analysts, researchers and fans of the FIFA World Cup, who will be able to use it in understanding how tournaments have changed over time. The user can discover patterns regarding the teams, host country, competitive statistics and the ability to look back at specific tournaments to see the matchups of finals and the locations of the stadiums. This tool allows for data-driven storytelling regarding World Cup history and enables the stakeholders to make better informed decisions at tournament planning and for analysing team performance.

## 3. Tech Stack<br>

The dashboard was built using the following tools and technologies:
- 📊 Tableau Public – Main data visualization platform used for report creation.
- 🧠 LOD (Level of Detail) expressions – Used for calculated field, and dynamic visuals.
- 📁 File Format – .twb for development and .png for dashboard previews.

## 4. Data Source

Dataset - world_cup_result.xlsx file is available in this repository.

This dataset is based on FIFA world cup from 1930 to 2014. It contains 10 columns and more than 1000 records.

## 5. Visualizations

The dashboard utilizes different types of visualizations to represent data in an easily understandable format, allows for deeper insights into the FIFA World Cup.

**1. Countries won FIFA world cup (Table)**<br>
At the top of the dashboard, it is given how many world cups each country has won. For example, Brazil has won the highest number of world cups, while Spain, England, France, and Germany has won only one world cup.

**2. Team by total semi-finals and finals (Butterfly Chart)**<br>
This chart provides data visualizations in a butterfly shape. At the center of this chart, a list of teams that qualified for semi-finals and finals is given. This chart has two bar charts, one on the left side for semi-finals and one on the right side for finals. It shows how many times a particular team has been qualified for semi-finals and finals.

**3. Countries that hosted world cup (Bar Chart)**<br>
This is a bar chart showing different countries that hosted or organized the FIFA world cup. It gives information about how many times a particular country has hosted the world cup, for example, Mexico, Italy, Germany, France, and Brazil hosted it twice, whereas others hosted it once.

**4. Competition Stats by Year(Stacked Bar Chart)**<br>
This visualization is used to represent the overall statistics of FIFA world cup. It provides information regarding how many goals are scored, how many matches are played, and how many teams are qualified in a particular year. For example, in the year 1950 and 2014, a total of 259 goals are scored, 86 matches are played, and 45 teams are qualified.

**5. Winners and top teams by world cup year and final's stadium (Table)**<br>
The table shows general information about the FIFA world cup such as year, winner, runner-up, third place, fourth place, hosting country, and stadium. For example, the first FIFA world cup took place in the year 1930 in Uruguay at Estadio Centenario stadium. Uruguay is the winner of the first FIFA world cup, Argentina is the runner-up, USA is at third place, and Yugoslavia is at fourth place.

**6. Countries qualified for the world cup (Bar Chart)**<br>
This bar chart illustrates which teams (countries) and the number of times they have qualified for the World Cup. For example, Brazil has qualified the most (20 times) in the World Cup.

**6. Audience by country and year (Map)**<br>
The map visualization shows various countries that hosted the world cup in the year ranging from 1930 to 2014. It also shows the audience present in that country. It shows audience color-wise, i.e., the darker shade of color indicates more audience. USA has more audience for the world cup because it is given more emphasis.

## 6. Filters
On the dashboard, tools are used for a better user experience. There is only one filter used in the dashboard, which is a map visualization located at the bottom corner, controlling all the visualization data. The user can apply the filter by selecting a specific country, which filters all visualised data for that country type. This provides the user with easy insights about the world cup.

## 7. Screenshots

![Dashboard Preview](https://github.com/HRSalet/FIFA-World-Cup-Dashboard/blob/main/Snaphot%20of%20Dashboard.png)
