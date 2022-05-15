# ZG-OlxScrapper

We developed a script to scrapper data from OLX website. To support this code, Jsoup package was used. We've also used openCSV package
to export our scrapped data to a CSV file.

This script intend to get data from OLX website. We tested this script using Iphone 11 search. The state of this search was Goias, and
its region was Goiania. To standarize the results, we've used lowest price filter. Then we collect the title, price, address and url of the announcements.

After scrapping, we calculate the average price of the products. Then we create a filtered list based on products which have price lower than the average. And this filtered list was exported to a CSV file