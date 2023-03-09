# UsefulTableau
Tableau hints and tips


# SUMIF
```
SUM(IF MONTH([Date])>6 THEN [Value] ELSE 0 END)
```


# Exclude 
Ignores a dimension when calculating, so in the below you could have a table with each region and this could be the denominator - to allow you calc what % of total headcount each region has.
```
{Exclude [Region] : Sum([Headcount])}
```
