# Stock-Dashboard-API-Grafana
This project creates a live stock price dashboard using the Finnhub API, Python, Google Sheets, and Grafana. It fetches real-time financial data, updates it in a Google Sheet, and visualizes it in Grafana. With seamless integration and minimal setup, this tool provides an efficient way to monitor stock prices dynamically.


Dashboard [Link](http://localhost:3000/public-dashboards/df2a6d59ad4a48ff9ce6b28eeeafc504)

Google Sheet [Link](https://docs.google.com/spreadsheets/d/1bD8diTR-EL8Lqr-bcmJXm8_Kn3CkzB4i1UBK9cYGKBw/edit?usp=sharing)

## Features

- Fetch real-time stock prices using Finnhub API.
- Store stock data in a Google Sheet for easy access.
- Visualize data in Grafana with dynamic dashboards.

---

## Setup and Installation

### 1. Run the Code with IPython
1. Install IPython, google-auth-oauthlib, gspread & requests is not already available:
   ```bash 
   pip install ipython
   pip install google-auth-oauthlib gspread requests

### 2. Start IPython in your terminal or Jupyter Notebook:

### 3. Copy and paste the code file (Stock_API_Code) into IPython (using %paste)

---

## Generate the Finnhub API Key
1. Visit Finnhub.io and sign up for an account. [Finnhub Link](https://www.finnhub.io/)
2. Navigate to your dashboard to get the API Key.
3. Replace the placeholder in the script:
4. ![image](https://github.com/user-attachments/assets/67df6bda-7744-4607-acd6-3b789d72b0b4)

---

## Publish Your Google Sheet (for more Details visit [Link](https://support.google.com/docs/answer/183965?hl=en&co=GENIE.Platform%3DDesktop#zippy=))

* When you publish a chart to the web, people can see the data used to create it. Be careful when publishing a chart with private or sensitive info.
* Any changes you make to the original document will be updated in the published version. The automatic update might take a few minutes.
* To remove a file from the web, you must stop publishing it. Learn how to stop publishing a file.
* To stop sharing a file with collaborators, learn how to change sharing permissions.

1. In Google Docs, Sheets, or Slides, open a file.
2. At the top, click File and then Share and then Publish to web.
3. Choose a publishing option:
* Spreadsheet: Publish the entire spreadsheet or individual sheets. You can also choose a publishing format.
* Presentation: Choose how quickly to advance the slides.
4. Click Publish.
5. Copy the URL and send it to anyone you’d like to see the file. Or, embed it into your website.

---

### Get JSON Credentials for Google Sheets
1. Follow Google's Guide to generate Service Account credentials.
2. Download the JSON file.
3. Replace the credentials in the script:
![image](https://github.com/user-attachments/assets/afdb815e-1038-493d-aa6c-996263c90457)

---

### Install Grafana
1. Download Grafana from Grafana Downloads. [Link](https://grafana.com/grafana/download)
2. Install Grafana on your system.
3. Go to Plugin's and install Infinity 
4. Add Google Sheets as a data source.
Create a dashboard to visualize stock prices.
![image](https://github.com/user-attachments/assets/c1d9c22d-55ae-4dc6-8a59-e26bb6d8a11b)

---

## Visualizing Data in Grafana
1. Configure your Google Sheet as a data source in Grafana.
2. Use the copied Google Sheets URL for real-time updates.
3. Create panels and customize your dashboard to monitor stock prices.
![image](https://github.com/user-attachments/assets/b5d82e2d-bc7f-4797-9862-12d2373d44d0)


---

## Project Workflow
1. Fetch stock data using Finnhub API.
2. Update the data into a Google Sheet.
3. Visualize the Google Sheet data in Grafana.
