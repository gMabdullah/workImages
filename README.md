Overview of work done
--------------------------------

Dashboards:
----------
I have use Chart.js to draw charts on Dashboard. There were some time needs to mainpulate the data alot to before giving to the chart. I have use namely
Bar Charts, Heatmaps, Donut Charts, Progress Charts etc.

Loyalty & Coupons:
------------------
I have create a whole module for Loyalty and Coupon multiple times in different designs. Where some times it needs to pass data in different component with Redux toolkit and useState. 
It's a large JSON which need to be passed to endpoint which need to be maintain on going different step back and forth.

Logs:
----
I have implemented Logs with firebase DB using firestore, and to make it more readable get in the dashboard in tabular form where extra details can be hide and show. The table is also very dynamic which only needs
response object it will create a table filter list by their own. 

Report Builder:
---------------
The builder make a report for given bunch of filters. like orders can have pending, confirm, deliverd, statuses, date, branch, location etc type of filters. which generates reports in tabular form by grouping data
into one aspect. one Frontend, it's only one dropdown with one handler, state which is printing through by loop an array. 
