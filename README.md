# Tunnels
Visualisation of UK tunnels from web scraping Wikipedia

3 Primary files (view read only copies of .ipynb files on https://nbviewer.jupyter.org):
1. 'Web_scraping_tunnel_information.ipynb' - Webscraping wikipedia for tunnel information. Outputs 'tunnels_list.csv'.
2. 'Preparing_traffic_data.ipynb' - Cleans 'dft_traffic_counts_aadf_by_direction.csv' into a usable format. Outputs 'traffic_data.csv'.
3. 'Creating_html_map.ipynb' - Overlays tunnel and traffic data visualisations onto a HTML map of UK.

4 input files
1. 'dft_traffic_counts_aadf_by_direction.csv' - From https://data.gov.uk/dataset/208c0e7b-353f-4e2d-8b7a-1a7118467acc/gb-road-traffic-counts
2. 'tunnels_list.csv'
3. 'traffic_data.csv'
4. 'Local_Authority_Districts_December_2016_Ultra_Generalised_Clipped_Boundaries_in_Great_Britain.geojson' from https://data.gov.uk/dataset/b7109abe-06f2-4bb3-94a5-e2db2ac83b47/local-authority-districts-december-2016-ultra-generalised-clipped-boundaries-in-great-britain (not uploaded)
