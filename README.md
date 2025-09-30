# Mridulsr-The-Powerbi-connection

This repository serves as the single, reliable source for the raw Excel data used in our Power BI reports and dashboards.
By hosting the files here, we leverage GitHub's version control to track changes to our source data.

Power BI Connection Instructions
The Power BI model is connected to the raw file links in this repository. To ensure the connection works for others and stays updated, follow these steps:

Access the Raw File: Navigate to the Excel file on GitHub, click the file name, and then click the "Raw" button.

Copy the URL: Copy the resulting URL from your browser's address bar. This is the direct link Power BI needs.

Connect in Power BI: In Power BI Desktop, use "Get Data" → "Web", and paste the raw URL.

Authentication: Use Anonymous authentication if the repository is public, or the Basic method with your GitHub Personal Access Token (PAT) if the repository is private.

✨ Data Integrity & Updates
To Update Data: Simply edit the Excel files locally, and then commit and push the changes to this repository. Power BI will pull the latest version on its next scheduled refresh.

Version Control: Every data change is tracked by Git, providing a full history and the ability to roll back to previous versions if needed.
