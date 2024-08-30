SELECT DISTINCT(CITY)
<br>
FROM STATION
<br>
WHERE
<br>
LEFT(CITY,1) IN ('A', 'E', 'I', 'O', 'U')
<br>
AND
<br>
RIGHT(CITY,1) IN ('A', 'E', 'I', 'O', 'U');

