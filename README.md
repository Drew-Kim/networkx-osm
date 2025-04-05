# OSM Road Parser
Convert a Open Street Maps `.map` format file into a networkx directional graph.

# Compatibility
python 3.6  
networkx v2

# Installation
```sh
pip install -r requirements.txt
```

# Examples
![OSM exporter](doc/osm_road_exporter.png)
![Networkx graph](doc/osm_networkx_graph.png)
![OSM to SHP](doc/osm_to_shp.png)

- Download osm data and display the networkx graph into matplotlib.

    ```sh
    python examples/display_osm_graph.py
    ```
- Load osm data from a `.map` file and convert the graph to shapefile
    ```sh
    # Requires osgeo python package --> https://pythongisandstuff.wordpress.com/2016/04/13/installing-gdal-ogr-for-python-on-windows/
    python examples/convert_osm_to_shp.py
    ```
