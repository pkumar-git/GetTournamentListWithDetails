# USTAGetTournamentListWithDetails

This UiPath application retrieves USTA tournament details for every USTA tournament  from the USTA tournaments website: https://playtennis.usta.com/tournaments. It retrieves details like tournament level, name, venue, deadline information etc and stores the details in an Excel sheet. The Excel file is saved in the C:\Users\pdksa\Documents\Tournaments\USTA folder.

This application requires the latest USTALibrary package to be available (available on https://github.com/pkumar-git/). It uses Chrome browser to access the USTA website.

Currently it retrieves only junior tournaments for the "18 and under" age division, though it is a straightforward change to retrieve any other/all age divisions. It also retrieves all levels of tournaments, and again, it is a straightfoward change to retrieve only certain levels of tournaments. Only tournaments whose registration status is open are retrieved.
