# Graph Section

## Plot data

Vytics Desktop allows you to plot your SQL query result quickly. To plot data, follow steps below.

1. Click on **Graph** button to switch to Graph view. Click on the **minus sign** to collapse the Connection Explorer pane. ![Graph View](/img/connection/query_conn/query_con5.png)

2. Drag and drop columns from the result treeview on the left to the variable boxes on the right. In this example, **Timestamp** is dragged into **Independent Var** box and **GlobalActivePower_kW** and **GlobalReactivePower_kW** are dragged into **Dependent Vars1** box. ![Drag-drop to make New Plot](/img/connection/query_conn/query_con6.png)

3. The plot will automatically display as you drag and drop columns to the variable boxes. ![A Plot Example](/img/connection/query_conn/query_con7.png)

4. You can also show/hide series by clicking on the series legend. In this picture, **GlobalReactivePower_kW** is hidden from the view. See more graph operations in the **Project Report** section. ![Show-Hide a Series](/img/connection/query_conn/query_con8.png)

## Filter/Smooth data

Vytics offers multiple ways to filter and smooth your data. To filter/smooth data, follow steps below.

1. Click **Filtering** and then **Filtering top N values** to start filtering process. ![Filter data](/img/connection/filter_smooth/fs1.png)

2. Enter information as below and click **Add Series** to highlight 10 points having greatest values. ![Add Filter Series](/img/connection/filter_smooth/fs2.png)

3. A new series **GlobalActivePower_kW_TopN** is added to the plot. ![TopN Series added](/img/connection/filter_smooth/fs3.png)

4. Click **Smoothing** and then **Moving Average** to start smoothing process. ![Smooth data](/img/connection/filter_smooth/fs4.png)

5. Enter information as below and click **Add Series**. ![Add Smooth Series](/img/connection/filter_smooth/fs5.png)

6. A new series **GlobalActivePower_kW_MovingAverage** is added to the plot. ![MovingAverage Series added](/img/connection/filter_smooth/fs6.png)

7. Click **GlobalActivePower_kW** and **GlobalActivePower_kW_TopN** to hide them. ![Focus on MovingAverage Series](/img/connection/filter_smooth/fs7.png)

## Export chart

To export your plot, follow steps below.

1. Click **Export Chart**. ![Export Chart](/img/connection/others/export_plot1.png)

2. Select where you want to save the exported plot and enter the file name. Click **Save**.![Save Chart](/img/connection/others/export_plot2.png)
