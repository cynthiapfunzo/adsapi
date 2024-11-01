create an API that pulls all relevant papers regarding SAAO's telescopes and displays them on your webpage. This can be done using the ADS Developer API's Search API, which allows you to query academic papers by keywords, institutions, author names, and other parameters.

Here’s a general approach to setting it up:

Define the Search Query:

Use keywords specific to SAAO’s telescopes (e.g., "SALT telescope", "Lesedi telescope") to ensure you capture all relevant papers.
ADS allows you to search by author, institution, or custom keywords, so you could filter results to include papers mentioning SAAO directly or the telescope names.
Obtain an ADS API Key:

You’ll need to create an ADS account and generate an API key for authentication.
Use this key in your API requests to access the data.
Build the API Endpoint:

Create a backend endpoint on your server that calls the ADS API to fetch papers based on your query.
Store or cache results locally to reduce the number of requests and stay within rate limits.
Display on the SAAO Webpage:

Format the data you receive from ADS to show details like the paper title, authors, abstract, and a link to the full text.
You could integrate filters or sorting options, allowing users to filter papers by telescope, year, or author.
Set up Regular Updates:

Run the API request on a schedule or based on triggers (e.g., once a week) to keep the displayed papers up-to-date.
