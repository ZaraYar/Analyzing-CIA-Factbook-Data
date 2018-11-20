# Analyzing-CIA-Factbook-Data

we'll work with data from the CIA World Factbook, a compendium of statistics about all of the countries on Earth. The Factbook contains demographic information like:

- population - The population as of 2015.
- population_growth - The annual population growth rate, as a percentage.
- area - The total land and water area.

When working in the Jupyter notebook environment, we can actually use pandas to run SQL queries and display the results neatly as a DataFrame object. We create a sqlite3.Connection instance and then use pandas.read_sql_query(sql, con) to handle running the query and returning the results in a table:

we're using SQLite, because First, most data analysts and data scientists in the industry use a SQL GUI based tool, which:

- let you write queries and save them for later
- let you run queries against multiple enterprise database systems (MySQL, Postgres, etc.)
- return results as a table
- create standard visualizations like line charts, bar plots, and histograms from the results table without any programming
