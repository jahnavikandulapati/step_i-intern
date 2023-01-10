
  9. Fetch data of all the matches where the final scores of both teams are tied and order it in descending order of the date.
  ```bash
SELECT * FROM matches
WHERE result = 'tie'
ORDER BY date DESC;
```




