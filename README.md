# ShowOHI/O Website
![Deployment Status](https://github.com/hackohio/showohio/workflows/Show-site%20S3%20Deployment/badge.svg)  
Welcome to the official website for ShowOHI/O, an annual showcase hosted by OHI/O.

# How to contribute to the website
- You may want to run a local testing server if you're working with absolute paths or page builders.

**Folder Structure**:  
20**: Contains the HTML pages and asset folders for each individual event.  
assets: Contains commonly used assets (such as minified js) that may be reused across events.  
index.html: The redirect page for the hack.osu.edu/show page to the most recent event page.

**Deployment**:  
The website is deployed using a simple GitHub actions workflow using AWS's S3 CLI.
- The script is setup to deploy the repo into the /show directory
