# FlightDelay Document Upload

This project uploads documents to a Dropbox account. To link it with your Dropbox, follow these steps:

1. [Create a Dropbox API app](https://www.dropbox.com/developers/apps) and generate an **access token**.
2. Open `index.html` and replace `YOUR_DROPBOX_ACCESS_TOKEN` with your token.
3. By default, uploaded files are stored under `/FlightDelayUploads` in your Dropbox. Each company will have its own folder inside this location.
4. Open `index.html` in a browser, provide a company name and select the documents to upload. The script will automatically create the necessary folders.

No additional build or test steps are required.
