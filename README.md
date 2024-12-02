Interactive Leaflet Map - README
Overview
This project generates an HTML file featuring an interactive map created with the Leaflet library, centered on New York City. Additionally, the HTML output is converted into a static PDF file to showcase the layout and content of the page. The map includes a marker with a popup that reads "New York City!" and allows basic interaction in the browser.

Features
Displays the current date dynamically.
Interactive map using Leaflet, centered on New York City (coordinates: -74.006, 40.7128).
Marker with a popup labeled "New York City!".
Static PDF version of the HTML output for non-interactive sharing.
Requirements
To execute the code and generate the HTML and PDF:

Python 3.x
weasyprint library (to convert HTML to PDF)
Internet access (to load Leaflet scripts and OpenStreetMap tiles)
Instructions
Run the Code:
Use Python to execute the provided script.
The HTML content is written directly in the script, rendering a basic interactive webpage.
Output:
The interactive HTML page contains:
Title and author information.
The current date, which can be dynamically generated in a real-time environment.
A Leaflet map centered on New York City with interactive features.
A PDF version of the page is also generated and saved in the specified directory for static viewing.
Generated Files:
Interactive_Leaflet_Map.pdf: A static representation of the webpage.
Notes
The interactive features of the map, such as zooming and popups, are only available in the HTML version.
To render the map in an actual project, save the HTML output to a file and open it in a browser.
Customize the map by modifying the coordinates, marker popups, or map tiles in the script.
License
This project is open-source and available under the MIT License. Contributions and modifications are welcome!
