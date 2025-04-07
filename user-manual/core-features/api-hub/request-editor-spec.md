# Request Editor Spec

The Request Editor in UniDeck's API Hub is designed to help you easily create, configure, and manage API requests within your dashboards. This document outlines the specifications and capabilities of the Request Editor, ensuring you can effectively integrate APIs with your dashboards.

### Request Editor Components

1\. HTTP Method

* **Description:** Select the HTTP method for your API request.
* **Supported Methods:**
  * `GET`
  * `POST`
  * `PUT`
  * `DELETE`
  * `PATCH`
  * `HEAD`
  * `OPTIONS`

#### 2. Request URL

* **Description:** Define the full URL endpoint for your API request.
* **Capabilities:**
  * Supports dynamic variables for URL parameters.
  * Support for internal and in-house requests for Enterprise users

#### 3. Headers

* **Description:** Include custom HTTP headers in your request.
* **Common Use-Cases:**
  * `Content-Type`: Define the format of your request payload (e.g., `application/json`).
  * `Accept`: Specify the format for the response content (e.g., `application/json`).
  * Custom headers required by specific APIs (e.g., `X-Api-Version`).
* **Capabilities:**
  * Easily toggle individual headers on or off without deletion.
  * Dynamically manage header lists for efficient experimentation.

#### 4. Query Parameters

* **Description:** Attach additional query parameters as key-value pairs.
* **Capabilities:**
  * Dynamically add, remove, or reorder parameters.
  * Enable or disable parameters individually.

#### 5. Request Body

* **Description:** Define data to be sent with requests that support payloads (`POST`, `PUT`, `PATCH`).
* **Supported Formats:**
  * **JSON:** Structured JSON data with validation and syntax highlighting.
  * **Text:** Plain text payloads.
  * **Form URL-Encoded:** Key-value pairs encoded for form submission.
  * **Multipart/Form-Data:** For file uploads and mixed data formats.

#### 6. Authentication

* **Description:** Secure your API requests with authentication.
* **Supported Authentication Methods:**
  * **None:** For public APIs or APIs with no authentication.
  * **Basic Auth:** Username and password-based authentication.
  * **Bearer Token:** Token-based authentication.

#### 7. Pagination

* **Description:** Automatically handle paginated API responses.
* **Specifications:**
  * Only supported if the API follows the standard pagination parameters:
    * `page`: Number indicating the current page.
    * `per_page`: Number indicating items per page.
* **Capabilities:**
  * Automatically iterate through pages to collect complete datasets.

#### 8. Response Handling

* **Description:** View API response details directly within the Request Editor.
* **Response Information:**
  * **HTTP Status Code:** Quickly identify response status.
  * **Headers:** View response headers returned from the API.
  * **Response Body:** Examine returned content with formatted JSON/XML.
  * **Timing Metrics:** Display request duration for performance insights.

### Using the Request Editor Effectively

1. **Select the appropriate HTTP Method** for your API request.
2. **Enter the endpoint URL**, including any necessary path or dynamic variables.
3. **Configure Headers** as required by your target API.
4. **Define Query Parameters** to refine your data retrieval.
5. **Specify the Request Body** for applicable HTTP methods.
6. **Configure Authentication** if the API endpoint requires credentials.
7. **Set Pagination** if applicable, using standard `page` and `per_page` parameters.
8. **Execute the request** by clicking "Send".
9. **Review and analyze the r**
10. **esponse** within the integrated response viewer.

By understanding and utilizing these Request Editor specifications, you can effectively integrate diverse APIs and enrich your UniDeck dashboards with real-time data and insights.
