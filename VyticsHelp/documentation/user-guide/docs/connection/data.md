# Data Section

## Open connection and query data

Vytics Desktop allows you to query all connections in SQL language. To query data from a connection, follow steps below.

1. Double left click to open a connection. If a connection is a text file, this will also query the data from the connection. ![Open Connection](/img/connection/query_conn/query_con1.png)

2. The default query and queried data will be shown. ![Query Result](/img/connection/query_conn/query_con2.png)

3. You can modify the SQL query to fit your needs. Vytics offers auto-complete feature and context sensitive editor. ![Edit Query](/img/connection/query_conn/query_con3.png)

4. After editting the SQL query, click **Execute** or press **F5** to run the query. The result will be updated in the data grid at the bottom. ![Excute Query](/img/connection/query_conn/query_con4.png)

## Add custom column

Before plotting any dataset, you should check for data types to prevent unexpected result. To add a custom column, follow steps below.

1. Open and query **home_energy** connection (file home_energy_consumption.csv). Click **Columns Info** to see columns information. ![Open home_energy connection](/img/connection/custom_col/custom_col1.png)

2. Notice the **Timestamp** column has the data type of **String**, which is not correct. There are 2 options to solve this issue: 1) change the SQL query to cast the **Timestamp** column to **DateTime** data type or 2) add a custom column. In this section, we will use approach (2). ![View column data types](/img/connection/custom_col/custom_col2.png)

3. Right click anywhere on the data grid header and select **Add Custom Field**. ![Open context menu](/img/connection/custom_col/custom_col3.png)

4. The **Add Custom Field** dialog will display. There is a **Quick Help** on the right hand side for your convenience. Start typing **Timestamp** in the left text area. ![Add custom field dialog](/img/connection/custom_col/custom_col4.png)

5. At the bottom, select **DateTime** as return data type and enter **Timestamp2** as new field name. Click **Add Field** to complete. ![Set data type and enter new field name](/img/connection/custom_col/custom_col5.png)

6. You will see new field **Timestamp2** added to your result. ![New custom field is added](/img/connection/custom_col/custom_col6.png)

## Export data

Vytics allows you to export data in 2 different formats. Each export format has multiple options that you can use (e.g., export all or just visible columns, with or without header, etc.)

1. Click **CSV Export** to export data to csv file. ![CSV Export](/img/connection/others/export_csv1.png)

2. Select where you want to save the exported data and enter the file name. Click **Save** to write data to disk. ![Save CSV](/img/connection/others/export_csv2.png)

## Query history

Vytics saves all executed queries and group them by date. To retrieve past queries, follow steps below:

1. Click **Open Query History**. ![Open Query History](/img/connection/others/query_history1.png)

2. Query history dialog will open. A list of dates is displayed on the left and all queries that are executed on the selected date are displayed in the text area on the right hand side. ![View Query History](/img/connection/others/query_history2.png)
