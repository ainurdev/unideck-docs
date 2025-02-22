# GitHub Personal - Notifications

The **GitHub Personal Notifications Widget** in UniDeck enables you to monitor your GitHub notifications directly from your dashboard, ensuring you stay informed about activities and updates relevant to your repositories and collaborations.

### Widget Sizes

To accommodate different user preferences and dashboard layouts, the GitHub Personal Notifications Widget is available in the following sizes:

* **Medium**: Provides a balanced view, displaying a list of recent notifications with essential details.
* **Large**: Offers an extensive overview, showcasing more notifications with additional information for in-depth monitoring.

<table data-card-size="large" data-view="cards" data-full-width="true"><thead><tr><th align="center"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">Medium</td><td><a href="../../.gitbook/assets/GithubPersonalNotifications-3x3.png">GithubPersonalNotifications-3x3.png</a></td></tr><tr><td align="center">Large</td><td><a href="../../.gitbook/assets/GithubPersonalNotifications-4x4.png">GithubPersonalNotifications-4x4.png</a></td></tr></tbody></table>

### Functionality

Designed to integrate seamlessly with your GitHub Personal account, the GitHub Personal Notifications Widget allows you to:

* **Monitor Notifications**: View and track your GitHub notifications, including mentions, commits, pull requests, and issues, ensuring you stay updated on activities that matter to you.
* **Stay Informed**: Receive real-time updates on repository activities, facilitating prompt responses and efficient collaboration.

### Important Note on GitHub Personal Integration

Please note that the GitHub Personal integration differs from the standard GitHub integration. It requires a Personal Access Token (PAT) for authentication. To set up this integration:

{% hint style="info" %}
The guide below is for advanced users, instead, you can use the step-by-step flow on the integrations section of your Account modal on [UniDeck](https://dash.unideck.app)
{% endhint %}

1. **Generate a Personal Access Token (PAT)**:
   * Log in to your GitHub account.
   * Navigate to your account settings.
   * Go to "Developer settings" and select "Personal access tokens."
   * Click on "Generate new token" and assign it a descriptive name.
   * Select the appropriate scopes/permissions required for accessing your notifications.
   * Generate the token and **copy it** for use in UniDeck.
2. **Connect Your GitHub Personal Account to UniDeck**:
   * In UniDeck, navigate to the integrations section.
   * Select "GitHub Personal" and initiate the connection process.
   * When prompted, paste the PAT you generated to authenticate the integration.

For detailed instructions, please refer to the integration connection modal within UniDeck.

### Configuration and Context Menu

The GitHub Personal Notifications Widget offers customizable settings to tailor its functionality to your needs:

* **View Options**:
  * **All Notifications**: Displays all notifications associated with your account.
  * **Participating**: Shows notifications where you are directly involved or mentioned.
* **Time Frame Filters**:
  * **Since**: Set a start date to view notifications from a specific point in time.
  * **Until**: Define an end date to filter notifications up to a certain date.

To access these options, right-click on the widget to open the context menu and select your preferred settings.

By incorporating the GitHub Personal Notifications Widget into your UniDeck dashboard, you can efficiently manage and respond to your GitHub activities, ensuring that you remain engaged and proactive in your development projects.
