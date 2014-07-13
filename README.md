DisasterAreaUnleashedData
=========================

0. We borrowed the database from Team Random project School Environment Explorer to do the calculation with
1. We ran the script raw_import_1.sh mammals D746F210.csv
2. We then ran the following query

  select count(distinct "Vernacular_Name") from mammals_raw;
