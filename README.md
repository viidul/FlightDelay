# FlightDelay Document Upload

This project uploads documents to a Dropbox account. To link it with your Dropbox, follow these steps:

1. [Create a Dropbox API app](https://www.dropbox.com/developers/apps) and generate an **access token**.
2. Open `index.html` and replace `YOUR_DROPBOX_ACCESS_TOKEN` with your token.
3. Start a simple web server in this directory so the page can make network requests:
   ```bash
   python3 -m http.server 8080
   ```
   Then browse to `http://localhost:8080/index.html`.
4. By default, uploaded files are stored under `/FlightDelayUploads` in your Dropbox. Each company will have its own folder inside this location.
5. Use the form to select documents and upload them. Errors will be logged to the browser console if something goes wrong.

No additional build or test steps are required.
