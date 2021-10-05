# geographics
explore 3D Visualization of Geo Graphics of Las Vegas City

# install additional packages:
$ conda install --channel conda-forge jupyter_contrib_nbextension <br />
$ conda install --channel conda-forge geopandas <br />
$ conda install -c conda-forge pymapd <br />
$ conda install -c conda-forge osmnx <br />

# stackoverflow helper room
install new kernel from conda env -
https://stackoverflow.com/questions/53004311/how-to-add-conda-environment-to-jupyter-lab

# sample code reference
https://realpython.com/location-based-app-with-geodjango-tutorial/

# run commands
$ docker run --name=postgis -d -e POSTGRES_USER=user001 -e POSTGRES_PASS=123456789 -e POSTGRES_DBNAME=gis -p 5432:5432 kartoza/postgis:9.6-2.4
$ source env/bin/activate
$ ./run_server.sh
