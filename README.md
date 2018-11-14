# google-analytics

To use the Google Analytics Embed API, you first need to create a new client ID. This quick step-by-step guide is referenced from [this page](https://developers.google.com/api-client-library/javascript/start/start-js#Setup).

### Get a Google Account

First, [sign up](https://www.google.com/accounts) for a Google Account if you do not already have one.

### Create a Google project

Go to the [Google API Console](https://console.developers.google.com/project). Click **Create project**, enter a name, and click **Create**.

### Enable Google APIs

Next, you can choose which Google APIs your application needs to use and enable them for your project. Specifically for Google Analytics, we need to enable the Analytics API. To do that, do the following:

1.  [Open the API Library](https://console.developers.google.com/apis/library) in the Google API Console. If prompted, select a project or create a new one. The API Library lists all available APIs, grouped by product family and popularity.
2.  If the Analytics API isn't visible in the list, use search to find it.
3.  Select the Analytics API, then click the  **Enable**  button.
4.  If prompted, enable billing.
5.  If prompted, accept the API's Terms of Service.

### Get access keys for your application

To get an access key for Analytics API, do the following: 

1.  Open the [Credentials page](https://console.developers.google.com/apis/credentials) in the API Console.
2.  Click  **Create credentials > OAuth client ID**  and select Web application under Application type.
3.  Leave the name as it is.

By now, you should have your Client ID. At anytime, you can always go back to the [Credentials page](https://console.developers.google.com/apis/credentials) to view your Client ID for your project.
