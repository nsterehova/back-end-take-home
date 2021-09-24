Application is written using python (3.9.7), which needs to be installed.
Run guest_logix_web_server.py in CMD.
Open a url http://127.0.0.1:8080
Following api methods are available:
/get_airlines -> prints list of airlines loaded from the csv file
/get_airports -> prints list of airports loaded from the csv file
/get_routes -> prints list of routes loaded from the csv file
/get_route -> search the route for the origin and destination provided. Additional parameters: 
      mode, defaulted to 'full', if 'test' value is provided file name is expected to have _test part before the extension. example: airlines_test.csv
      show_all_routes, defaulted to 'false' means show the shortest route, if 'true' value is provided - all found routes will be listed
      max_connections, defaulted to 99
Following files, located in the current folder, are expected:
      airlines.csv
      airports.csv
      routes.cvs

