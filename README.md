# FareNet-Dashboards
## SQL Code to create complex reporting using Aggregated Search Table and Aggregated Booking Table.

The tables need to be joined to see Search and Booking numbers together but there is NO specific USERID to do so. 
Hence we need to carefully need to evaluate parameters of atmost importance to join these tables.

Join Parameters:

1.AIRLINEIATACODE
2.DATE 
3.DEPARTUREIATACODE
4.ARRIVALIATACODE
5.JOURNEYTYPE
6.OUTBOUNDFARECLASS
7.INBOUNDFARECLASS, 
8.DEPARTUREDATE
9.RETURNDATE
10.SITEEDITION [SE] 
11.DEVICE CATEGORY [DC]

Evaluate and verifiy data as the below spreadsheet.

  1. Use raw-data-code and evaluate-join-sql to compare data between Redshift and Dataset for FareNet Ddashboards
  2. Complete this Spreadsheet with customer's data
  https://docs.google.com/spreadsheets/d/1NJGJ-Vuq5LbDTy_5T7Gu6unMDuX5asuQFIHVNEJBWP8/edit#gid=1229048930
  3. Use sql-code to replicate dashboards by changing airlineiatacode.
