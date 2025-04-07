# API Hub

One of the main goals of creating UniDeck was to provide a way to easily integrate your custom data and have an easy to use and customize dashboard unlike the existing solutions. The API Hub is the core of this functionality. It allows you to connect to any HTTP API and use the data in your dashboards.

You probably have previously used similar tools like Postman, Insomnia or even cURL to test and share your APIs. The API Hub is similar to these tools, but it is designed to be used with-in UniDeck and be easy to shared with your team. It is also designed to be used with-in the context of a dashboard, so you can easily visualize the data you are working with.

### API Hub Overview

The API Hub's interface is designed to be simple and easy to use. It consists of a few main sections:

* **API Requests**: This is where you can create and manage your API requests. You can create new requests, edit existing ones, and delete or duplicate requests.
* **Create new request - Edit request**: This is where you can create a new request or edit an existing one after selecting it on **API Reqeuests**. You can specify the request method (GET, POST, PUT, DELETE), the URL, any headers, authentication method, body or query parameters you want to include in the request.
* **Response**: This is where you can see the response from the API request. You can view the response body and status code. You can also see any errors that occurred during the request.

### Request Editor

The request editor is where you can create and edit your API requests. It consists of a few main sections:

* **Request Method**: This is where you can select the HTTP method for your request. You can choose from GET, POST, PUT, DELETE, PATCH, OPTIONS and HEAD.
* **URL**: This is where you can enter the URL for your request. This URL needs to be accessible on the internet or on your local network serving UniDeck Enterprise.
* **Query Parameters**: This is where you can add any query parameters you want to include in the request. You can add as many query parameters as you need. The query parameters will be automatically encoded for you.
  * **Pagination**: If your API supports pagination, you can click on "Enable Pagination" to automatically add pagination parameters to your request. This will only work if your API supports pagination via `page` and `per_page` query parameters.
* **Headers**: This is where you can add any headers you want to include in the request. You can add as many headers as you need. The headers will be automatically encoded for you.
* **Auth**: This is where you can select the authentication method for your request. You can choose from None, Basic Auth and Bearer Token.
  * **Basic Auth**: This is where you can enter the username and password for basic authentication. The username and password will be automatically encoded for you.
  * **Bearer Token**: This is where you can enter the bearer token for authentication. You can also customize the prefix for the token. The token will be automatically encoded for you if needed.
* **Body**: This is where you can enter the body for your request. You can only send text based body types like `application/json`, `application/x-www-form-urlencoded`, `text/plain`, `text/html` and `application/xml`. The content-type needs to be manually set in the headers. The body will be automatically encoded for you if needed.
