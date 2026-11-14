URBAN THREAD — STREETWEAR SHOP

FILES
- index.html: page layout, styling, and JavaScript
- products.csv: streetwear product list
- config.csv: sample key/value settings
- README.txt: setup guide

RUN IN VS CODE
1. Extract the downloaded ZIP.
2. Open VS Code > File > Open Folder.
3. Select the extracted urban_thread_streetwear folder.
4. Install the Live Server extension if needed.
5. Right-click index.html > Open with Live Server.

Keep products.csv in the same folder as index.html. The website uses fetch() to load the CSV, so open it with Live Server rather than double-clicking the HTML file.

CSV lesson examples:
- Standard comma-separated values
- Header row
- Quoted fields with commas inside descriptions
- Importing CSV data into a webpage
- Key/value configuration CSV

To add an item, add a row to products.csv in this order:
id,name,category,price,description
Use double quotes around any field containing a comma.
