# Top-Songs-Pivot
Using pivot tables to uncover which artists have the most songs in the top 5000.

This project examines a 5000 row spreadsheet containing data on the top 5000 songs from 1901 on, using a pivot table to uncover which artists have the most songs in the top 5000, what they are, and what year they came out. The songs were scored based on popularity from various geographic categories, such as USA, England, Europe, etc. The source of the raw score data is unknown. 

## Process

1. Selected all of the data within the worksheet and then created a new pivot table.

2. Made a pivot table which can be filtered by 'year' and which contains two rows: 'artist' and 'name'.

   * All of an artist's songs are listed underneath their name.

3. Updated pivot table to contain values for:

   1. How many songs an artist has in the top 5000.
   2. The sum of the final_score of their songs.

4. Sorted the pivot table by descending sum of the final_score.

The top 5 artists with the highest raw scores are as follows:

1. The Beatles
2. Madonna
3. Elvis Presley
4. Michael Jackson
5. The Rolling Stones
