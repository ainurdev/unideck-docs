# Advanced - Chart

The **Advanced Chart** is the premier data visualization tool in the UniDeck Advanced Widget suite. It allows you to create rich, dynamic charts by pulling data from custom data sources. Connect to any internal or external HTTP/S API through the API Hub and transform complex data arrays into insightful Bar, Line, Pie charts, and more, directly on your dashboard.

This widget is ideal for visualizing time-series data, comparing metrics, or tracking progress from virtually any data source you have access to.

### Getting Started

First, add the Advanced Chart widget to your dashboard from the **Widget Gallery**. Upon adding it, the widget will display a "No configuration found" message. This is because, like all Advanced Widgets, it must be linked to a data source and configured.

To begin, right-click on the widget and select **"Configure"** to open the main Chart Configuration panel.

### Configuration

The configuration panel is where you define your chart's data and appearance. It features a live preview that updates as you make changes and is organized into two main tabs: **Data Settings** and **Chart Settings**.

<figure><img src="../../.gitbook/assets/image (47).png" alt=""><figcaption><p>Advanced Chart Widget Configuration Modal</p></figcaption></figure>

#### Data Settings Tab

This tab is for connecting your API data to the chart's labels and datasets.

**Response Shape**

* **Response Shape**: Defines the expected structure of your API's JSON response. For most standard data arrays, "General" is sufficient.

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption><p>Response Shape Options</p></figcaption></figure>

**Labels Configuration**

This section configures the labels for the chart's primary axis (typically the x-axis).

* **Labels Array Field**: Select the JSON array from your response that contains the values or objects for your labels.
* **Label Field Key**: Specify the key within the array's objects to use for the label text. For example, if your data contains timestamps, you might select a `start_time` or `date` field.
* **Label Transformation**: Apply a transformation to the raw label values. This is especially useful for formatting. For example, select **ISO Date** to correctly parse and display date strings.

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption><p>Labels Configuration Options</p></figcaption></figure>

**Datasets Configuration**

Here, you define the data series to be plotted on the chart. You can add multiple datasets to compare different data on the same chart.

For each dataset, you can configure:

* **Label**: The name of the dataset as it will appear in the chart's legend (e.g., "Daily Sales").
* **Data Array Field**: The JSON array containing the data for this series.
* **Data Field Key**: The specific key within the data array that holds the value to be plotted.
* **Data Grouping**: This powerful feature aggregates your data. Instead of plotting raw values, you can perform a calculation. For example, select **Count** to plot the total number of items in the data array, which is perfect for creating a bar chart of daily activities. Other potential options include Sum, Average, etc.
* **Styling (Background, Border, Text Color)**: Assign unique colors to each dataset for clear visual separation in the final chart.

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption><p>Datasets Configuration Options</p></figcaption></figure>

#### Chart Settings Tab

While the Data Settings tab handles the "what," the Chart Settings tab handles the "how." This section controls the overall appearance and type of chart.

* **Chart Type**: Select the type of visualization you want to create (e.g., Bar, Line, Doughnut, Pie).
* **Chart Title**: Add an overall title to your chart.
* **Legend**: Control the visibility and position of the chart's legend.
* **Grid Lines & Axes**: Toggle the visibility of the chart's grid lines and set titles for the X and Y axes to provide clear context for your data.

<div><figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption><p>Chart Basic Settings</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption><p>Chart Common Options</p></figcaption></figure> <figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption><p>Chart Type-Specific Options</p></figcaption></figure></div>

### Sizing

The Advanced Chart widget is available in a range of large sizes to ensure your data is clear and readable. To change the size, right-click the widget, select **"Size"**, and choose an option that best fits your dashboard layout.

<table data-card-size="large" data-view="cards" data-full-width="true"><thead><tr><th align="center"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center"><strong>8x4</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-8x4.png">AdvancedChart-8x4.png</a></td></tr><tr><td align="center"><strong>8x6</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-8x6.png">AdvancedChart-8x6.png</a></td></tr><tr><td align="center"><strong>12x4</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-12x4.png">AdvancedChart-12x4.png</a></td></tr><tr><td align="center"><strong>12x6</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-12x6.png">AdvancedChart-12x6.png</a></td></tr><tr><td align="center"><strong>12x8</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-12x8.png">AdvancedChart-12x8.png</a></td></tr><tr><td align="center"><strong>6x4</strong></td><td><a href="../../.gitbook/assets/AdvancedChart-6x4.png">AdvancedChart-6x4.png</a></td></tr></tbody></table>
