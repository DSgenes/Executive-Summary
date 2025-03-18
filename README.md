# Executive-Summary

# Scenario

   You've just received an email marked "URGENT" from the executives at Adventure Works. They've heard about your expertise in data analytics and have a pressing request: "We need a 
   comprehensive Power BI report and dashboard ASAP!" Now, the room you find yourself in isn't just any room; you're in the executive suite of Adventure Works, surrounded by the company's top 
   minds. These decision-makers juggle multi-million-dollar budgets, eyeing global expansion and continually adapting to ever-changing market dynamics. They don't just want data; they need 
   actionable insights, and they need them now. 

   The executives understand that in the modern business landscape, data isn't just an asset; it's the essence of strategic decision-making. As you look around, you see various department 
   heads clutching different pieces of the data puzzle—sales printouts, customer demographics, and inventory reports—but they're fragmented, disjointed, and not speaking to each other. The 
   executives look to you to make the data understandable and actionable. You've been given a significant responsibility: to harness the potential of sales and customer data that will 
   influence high-stakes decision-making. So, are you ready to dive in?

# Overview :

  • Utilize the table, column chart, line chart, KPI, and Q&A visuals to bring data to life.

  • Implement forecasting on your line chart to anticipate future trends.

  • Employ the Q&A visual to enable a more natural conversation with data.

---------------------------------------------------------------------------------------------------------------------------

# Step 1: Create Core Visualizations (Table)

# 1. Add a Table Visualization:

   • In the Visualizations pane, select the Table icon to add an empty table to the canvas.

# 2. Select Fields:

   • Expand the Sales table in the Fields pane and drag the following fields to the Columns well: Product ID, Product Name, Order ID, Order Status, and Order Total.

![image_alt](https://github.com/DSgenes/Executive-Summary/blob/5c7a604c541b6c36fe2b38a44cdf91ea35163ae2/Screenshot%201.png)

# 3. Format Table:

   • In the Format tab, choose the Minimal style preset from the Style dropdown.

![image_alt](https://github.com/DSgenes/Executive-Summary/blob/cce402be006fc4a59134a564ab3072b48a7e3521/Screenshot%202.png)

# 4. Resize and Position:

   • Resize the table visualization and position it on the right side of the canvas.

# Column Chart Visualization

# 1. Add Clustered Column Chart:

   • In the Visualizations pane, select the Clustered Column Chart icon.

# 2. Add Fields to the Chart:

   • Drag Product Category from the Sales table to the X-Axis well.

   • Drag Order Total from the Sales table to the Y-Axis well.
  
# 3. Format Chart:

   • In the Format tab, go to Columns > Colors and set the color to Dark Blue (#2D386D).

# 4. Add Tooltips:

   • Drag Order Quantity and Product Weight from the Sales table into the Tooltips field well.

# 5. Sort Data:

   • Click the ellipsis in the top right corner of the chart, select Sort Axis, and choose Sum of Order Total. Then, select Sort ascending to arrange the data in ascending order.

# 6. Observe Results:

  • Review the column chart and note the Product Category with the lowest Order Total.

![image_alt](https://github.com/DSgenes/Executive-Summary/blob/beae5640fd5370d160774fe130f486ccb0482d69/Screenshot%203.png)

# Line Chart Visualization

# 1. Add Line Chart:

   • In the Visualizations pane, select the Line Chart icon.

# 2. Add Fields to the Chart:

   • Drag OrderDate from the Sales table to the X-Axis well.

   • Drag Order Total to the Y-Axis well.

# 3. Resize and Position:

   • Resize the Line Chart and position it below the Column Chart, next to the Table Visualization in the center of the canvas.

![image_alt](https://github.com/DSgenes/Executive-Summary/blob/63a676670f8fb5b9500b726f9fabb67ae2250b65/Screenshot%204.png)

# Step 2: Create KPIs

# 1. Add KPI Visualization:

    • In the Visualizations pane, select the KPI icon.

# 2. First KPI:

    • Drag Order Total from the Sales table to the Value field well.

    • Drag OrderDate from the Sales table to the Trend Axis field well.

# 3. Add Two More KPIs:

    • For the second KPI, drag Customer ID from the Customers table to the Value field well and OrderDate from the Sales table to the Trend Axis.
  
    • For the third KPI, drag City from the Customers table to the Value field well and OrderDate from the Sales table to the Trend Axis.

![image_alt]()

# Step 3: Set Up Forecasting

# 1. Select Line Chart:

    • Click on the Line Chart visualization you previously created.

# 2. Enable Forecasting :

    • In the Visualizations pane, select the Analytics tab (magnifying glass icon).

    • Toggle the Forecast switch to enable forecasting on the chart.

# 3. Adjust Parameters:

    • Set Seasonality to 12 to account for monthly trends.

    • Adjust the Confidence interval to 99% to ensure high forecast accuracy.

    • Click Apply to apply the changes.

# 4. Observe Results:

    • Review the line chart and note the day of the month with the lowest Order Total for Q1 2023.

![image_alt]()

# Step 4: Configure Q&A

# 1. Add Q&A Visualization:

   • In the Visualizations pane, locate and select the Q&A icon (chat bubble).

# 2. Resize and Position Q&A Box:

   • Resize the Q&A box by dragging its corners, and reposition it on the left side of the canvas by dragging the title bar.

# 3. Ask Questions:

   • Inside the Q&A box, you'll see the text prompt Ask a question about your data. Type the following queries and note the results:

      • Which Customer City has the lowest average Order Total?

      • Which Product Category has the highest average Order Quantity?
 
      • Which Product Subcategory has the highest Product Weight?

![image_alt]()

![image_alt]()

![image_alt]()
