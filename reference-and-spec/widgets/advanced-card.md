# Advanced - Card

The **Advanced Card** widget is a powerful and versatile component in UniDeck's suite of Advanced Widgets. It is designed to display a single, key data point or metric from a custom data source, making it perfect for dashboards that track important numbers, statistics, or statuses.

As part of the Advanced Widget family, the Advanced Card connects to custom data sources through UniDeck's **API Hub**. This allows you to use any custom HTTP API endpoint as your data source, with requests sent directly from your browser. This method ensures seamless compatibility with both public APIs and internal company or local network services.

### Features

* **Connect to Custom Data Sources**: Pull data from any external or internal service with a compatible HTTP/S API.
* **Centralized API Management**: Leverage the API Hub to configure, share, and manage your data sources efficiently.
* **Precise Data Mapping**: Visually map the exact data point from your API's JSON response to be displayed on the card.
* **Dynamic Display**: Customize the card with a title, icon, and optional prefix or suffix to provide clear context for your data.
* **Rich Styling Options**: Choose from multiple visual styles, including Light, Dark, Colorful, and Modern themes, with optional blurred effects.
* **Error Handling**: Define a fallback value to display in case the data source is unavailable or returns an error.
* **Live Preview**: Instantly see how your card will look as you adjust its configuration.

### Configuration

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption><p>Advanced Card Widget Configuration Modal</p></figcaption></figure>

To begin, add the Advanced Card widget to your dashboard from the Widget Gallery. The primary setup is done within the configuration panel. To access it, right-click the widget and select **"Configure"**.

The configuration panel is divided into several sections:

#### 1. Data Mapping

This section determines which piece of data from your API response will be shown.

* **Response Field**: Select the specific field from the API's JSON response that contains the value you want to display. The widget supports nested JSON objects using dot notation (e.g., `data.count`).

#### 2. Value Transformation

Here, you can apply transformations to the raw value received from your data source before it is displayed.

* **Transform Value**: Apply formatting or perform calculations on the original value.

#### 3. Fallback

Define the widget's behavior when it cannot retrieve data from the source.

* **Fallback Value**: Enter a default value to display if the API call fails.
* **Show Error**: Check this box to display an explicit error message on the widget upon failure.

#### 4. Card Display Customization

This area allows you to control the appearance and context of your displayed data.

* **Title**: Set the text that appears at the top of the card.
* **Display**:
  * **Prefix & Suffix**: Add text before or after the main value for context (e.g., a currency symbol as a prefix or "Widgets" as a suffix).
  * **Icon**: Choose an icon to display on the card and toggle its visibility.
  * **Size**: Adjust the font size of the main value (e.g., Small, Medium, Large).
  * **Style**: Select a visual theme for the card.

After making your changes, click **"Save Settings"** to apply the configuration.

### Styling and Sizing

You can quickly change the look and feel of your Advanced Card widget directly from the dashboard. Right-click the widget to open the context menu.

<table data-card-size="large" data-view="cards" data-full-width="true"><thead><tr><th align="center"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center"><strong>2x1</strong></td><td><a href="../../.gitbook/assets/AdvancedCard-2x1.png">AdvancedCard-2x1.png</a></td></tr><tr><td align="center"><strong>2x2</strong></td><td><a href="../../.gitbook/assets/AdvancedCard-2x2.png">AdvancedCard-2x2.png</a></td></tr><tr><td align="center"><strong>3x1</strong></td><td><a href="../../.gitbook/assets/AdvancedCard-3x1.png">AdvancedCard-3x1.png</a></td></tr><tr><td align="center"><strong>3x2</strong></td><td><a href="../../.gitbook/assets/AdvancedCard-3x2.png">AdvancedCard-3x2.png</a></td></tr><tr><td align="center"><strong>3x3</strong></td><td><a href="../../.gitbook/assets/AdvancedCard-3x3.png">AdvancedCard-3x3.png</a></td></tr></tbody></table>

* **Style**: Choose from a wide range of visual themes to match your dashboard's aesthetic. Each style is available in a standard and a "Blurred" variant.
  * Default
  * Light
  * Dark
  * Colorful
  * Modern
* **Size**: Select from a list of predefined sizes to best fit your card into your dashboard layout.
