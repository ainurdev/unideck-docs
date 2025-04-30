# Google Workspace Users

The **Google Workspace Users** widget in UniDeck allows you to quickly search for your teammates by name or email, browse their basic information in a list view, and open a full user profile, all without leaving your dashboard.

***

### Widget Sizes

To fit any dashboard layout, the Google Workspace Users widget supports two sizes:

<table data-card-size="large" data-view="cards" data-full-width="true"><thead><tr><th align="center"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">Medium</td><td><a href="../../.gitbook/assets/Screen Shot 2025-04-30 at 21.15.20.png">Screen Shot 2025-04-30 at 21.15.20.png</a></td></tr><tr><td align="center">Large</td><td><a href="../../.gitbook/assets/Screen Shot 2025-04-30 at 21.15.26.png">Screen Shot 2025-04-30 at 21.15.26.png</a></td></tr></tbody></table>

***

* **Search Bar**\
  Enter any part of a user’s name or email to filter the list in real time.
* **List View**\
  Displays for each user:
  * Avatar
  * Full Name
  * Primary Email
  * _(Optional)_ Last Login

***

#### Modal View

Clicking any user's avatar in the list opens the menu to access their user profile, providing a detailed, full-screen panel:

<figure><img src="../../.gitbook/assets/image (45).png" alt="" width="391"><figcaption><p>User Profile Modal</p></figcaption></figure>

| Field             | Description                                    |
| ----------------- | ---------------------------------------------- |
| **Primary Email** | The user’s main address                        |
| **Created**       | Account creation date                          |
| **Org Unit**      | The user’s organizational unit in Workspace    |
| **Last Login**    | Timestamp of the last sign-in                  |
| **Admin**         | Whether the account has super-admin privileges |
| **2SV Enrolled**  | Two-step verification status                   |
| **Mailbox Setup** | Whether Gmail is provisioned for this user     |
| **Suspended**     | Suspension status of the account               |
| **Aliases**       | List of all email aliases for the user         |

***

#### Configuration & Context Menu

Right-click anywhere on the widget to open its context menu:

* **Show Last Login Time**\
  Toggle the “Last Login” column in the list view.
* **Google Account**\
  Manage which Google Workspace connection the widget uses.
* **Size**\
  Switch among Extra Small, Small, Medium, or Large.
* **Learn More**\
  Jump directly to this documentation page.
* **Delete**\
  Remove the widget from your dashboard.

_No further setup is required beyond connecting at least one Google Workspace account._

***

#### Permissions

Ensure your UniDeck integration has the following OAuth scopes to fetch user data and aliases:

* `admin.directory.user.readonly`

{% hint style="warning" %}
You will be requested to login again with your Google account if the permission is not provided to UniDeck
{% endhint %}

***

_Last updated: April 2025_
