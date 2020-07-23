# News-App
# Layout
● Main Screen- App contains a main screen which displays multiple news stories.

 ● List Item Contents-Each list item on the main screen displays relevant text and information about the story.

● The title of the article and the name of the section that it belongs to are required field.

● If available, author name and date published should be included. Please note not all responses will contain these pieces of data, but it is required to include them if they are present.

# Functionality
1.Main Screen Updates. Stories shown on the main screen update properly whenever new news data is fetched from the API.

2.Story Intents. Clicking on a story uses an intent to open the story in the user’s browser.

3.API Query. App queries the content.guardianapis.com api to fetch news stories related to the topic.

4.JSON Parsing. The JSON response is parsed correctly, and relevant information is stored in the app.

5.No Data Message. When there is no data to display, the app shows a default TextView that informs the user how to populate the list.

6.Response Validation. The app checks whether the device is connected to the internet and responds appropriately. The result of the request is validated to account for a bad server response or lack of server response.

7.Use of Loaders. Networking operations are done using a Loader rather than an AsyncTask.
