# Basketball Players Statistics
The program reads the statistics of basketball players from Wikipedia, saves them in an Excel file and generates a graph to compare the values.

* The program needs a list with Wikipedia links of the various interested players and a list with their names.
* The information extracted from Wikipedia is organized by columns and each row represents a year of the player's career.

* The statistics are: 

Games played | Games started	| Minutes per game | Field goal percentage | 3-point field-goal percentage | Free-throw percentage | Rebounds per game | Assists per game | Steals per game | Blocks per game | Points per game
------------ | ------------- | ------------ | ------------- | ------------ | ------------- | ------------ | ------------- | ------------ | ------------- | ------------ | 

* This information is stored in an Excel file, where each player is on a different sheet, the latter named after the player himself.

* Finally, is plotted on a chart the "Point per game" values of each player trought the years. Same things can be done using another 'key' of the table above.
(The values of each players are plotted on the same chart, but if you want a different chart for each player you can simply include the last 4 rows of the code inside the for loop)

