I have add some measures in this dashboard.
here it is
Total Sales = SUM(SalesData[Sales])

Total Quantity = SUM(SalesData[Quantity])

Average Sales = AVERAGE(SalesData[Sales])

Sales per Unit = DIVIDE([Total Sales], [Total Quantity], 0)
