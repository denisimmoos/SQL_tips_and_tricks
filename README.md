# SQL_tips_and_tricks

## get last row

<pre>
SELECT * (
   SELECT * FROM t_table WHERE ... ORDER BY ENDE DESC;
) WHERE rownum =1;

</pre>
