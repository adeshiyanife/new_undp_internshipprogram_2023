# STEP IN CREATING AND REPORTING DATA VIRTUALIZATION USING POWER BI

Download Power BI deskstop using https://aka.ms/power-bi-desktop and take follow the steps below
1. In order to import the data, Open Power BI Desktop. The application interface should look similar to this:
2. Click on Get data, and then in the list of data sources, select Web and then click Connect.
3. On the web dialog box, enter the following URL and then select OK: https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/customers.csv .  Follow the same process for these other two links:https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/products.csv and  https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/orders.csv
4. To explore the data, go to the left-side edge, select the Model tab, and then you cn arrange the tables.
5. In the orders table, select the Revenue field and then in the Properties pane, set its Format property to Currency:
6. Click on the products table and right-click the Category field (or open its ⋮ menu) and select Create hierarchy. This step creates a hierarchy named Category Hierarchy. You may need to expand or scroll in the products table to see this - you can also see it in the Fields pane:
7. on the products table, right-click the ProductName field (or open its ⋮ menu) and  then select Add to hierarchy > Category Hierarchy. This adds the ProductName field to the hierarchy you created previously.
8. While on the Fields pane, right-click Category Hierarchy (or open its … menu) and select Rename. Then rename the hierarchy to Categorized Product.
9. On the far left hand corner,select the Table View, then in the Data pane, select the customers table.Select the City column header, and then set its Data Category property to City.
10. # To create a REPORT, Go to the File menu, select Options and Settings. Then select Options, and in the Security section, ensure that Use Map and Filled Map visuals is enabled and select OK.
11. On the left-side edge, select the Report view tab and view the report design interface.
12. Select any empty area on the report to de-select the text box. Then in the Data pane, expand Products and select the Categorized Products field. This step adds a table to the report.
13. While still on the table still selected, in the Data pane, expand Orders and select Revenue. A Revenue column is added to the table. You may need to expand the size of the table to see it.
14. With the table still selected, in the Visualizations pane, select the Stacked column chart visualization. The table is changed to a column chart showing revenue by category.
15. select the ↓ icon to turn on drill-down. Then in the chart, select the second column to drill down and see the revenue for the individual products in this category. This capability is possible because you defined a hierarchy of categories and products.
16. Select a blank area of the report, and then in the Data pane, select the Quantity field in the orders table and the Category field in the products table. This step results in another column chart showing sales quantity by product category.
17. elect a blank area of the report, and then in the Data pane, select the City field in the customers table and then select the Revenue field in the orders table. This results in a map showing sales revenue by city. Rearrange and resize the visualizations as needed:
18. On the File menu, select Save. Then save the file with an appropriate .pbix file name. You can open the file and explore data modeling and visualization further at your leisure.
18. 
    









 