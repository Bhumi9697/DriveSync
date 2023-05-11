README for the Drive Sync:

This program allows you to authorize and sign in to your Google Drive account, and then list the metadata for the first 10 files in your Drive.

To execute the program:

Go to the Google Cloud Console and create a new project.
In the sidebar, navigate to APIs & Services > Dashboard and click "+ ENABLE APIS AND SERVICES". Search for and enable the "Google Drive API".
In the sidebar, navigate to APIs & Services > Credentials and create a new OAuth 2.0 client ID. Choose "Web application" as the application type, add "http://localhost:8080" to the Authorized JavaScript origins, and add "http://localhost:8080/oauth2callback" to the Authorized redirect URIs.
Copy the client ID and API key and replace the placeholders for CLIENT_ID and API_KEY in the code with your own values.
Save the changes to the code and open the HTML file in a web browser.
Click the "Authorize" button to sign in to your Google account.
Once authorized, click the "View List" button to list the metadata for the files in your Drive.
You can see the Download button next to each file which enables you to download the respective file.
The Refresh button is used to refresh the access token if it has expired.
The Sign Out button is used to revoke the user's authentication and remove the access token.
