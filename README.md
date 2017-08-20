This project is licensed under APACHE 2.0. 

<h1>Initial Code Contributors </h1> 

1. Sanjay Dorairaj
2. Tom Seddon
3. Roseanna Hopper

Usage Instructions:

Server Side Installation:

The server is based on node and MySQL

Download the code and type

<code> cd node_rest_server </code>
<code> npm install </code>
<code> node server.js </code>

You will need to set up a MySQL instance and import the USDA food database. The format of the import is the same 
as the CSV file in the data director demo_food_data_final.csv

Database name is usdafood

Client Side Instructions:

On the client side 

js/bar_chart.js - Used to draw the bar chart
js/ts_parallel_chart.js - Used to draw the parallel lines chart
js/search_panel.js - Used to implement the search panel. The search panel interacts with the node backend
js/hos_panel.js - Used to implement the Hall of Shame panel
js/load_data.js - Used to load the data. 

The client uses the papaparse library to parse the input CSV file and the typeahead library to allow for
typeahead functionality in the Search box


