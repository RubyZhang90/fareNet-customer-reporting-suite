# FareNet-Dashboards
SQL Code to create complex reporting using Aggregated Search Table and Aggregated Booking Table.

The tables need to be joined to see Search and Booking numbers together but there is NO specific USERID to do so. 
Hence we need to carefully evaluate which parameter are of atmost importance to join these tables.

Mandatory Join Parameters:
DATE, DEPARTUREIATACODE, ARRIVALIATACODE, JOURNEY_TYPE
OUTBOUND_FARECLASS, INBOUND_FARECLASS, 
DEPARTURE DATE (added on request not necessarily needed)

Additional fields which may cause difference to actual bookings:  	
FLIGHT_TYPE [FT]
SITE EDITION [SE]
DEVICE CATEGORY [DC]

Evaluate and verifiy data for each additional join before finalizing the code for every client.

  1. Use raw-data-code and evaluate-join-sql to do so
  2. Complete this Spreadsheet with customer's data
  https://docs.google.com/spreadsheets/d/1NJGJ-Vuq5LbDTy_5T7Gu6unMDuX5asuQFIHVNEJBWP8/edit#gid=1229048930
