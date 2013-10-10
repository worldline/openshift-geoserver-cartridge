# OpenShift GeoServer Cartridge

The `GeoServer` cartridge provides [GeoServer](http://www.GeoServer.com/) on OpenShift.

## Use it

In OpenShift, first create a web application (java, python, ruby, node... as you want), 
then add a downloaded cartridge, with the following URL : http://cartreflect-claytondev.rhcloud.com/reflect?github=worldline/openshift-geoserver-cartridge

Geoserver is deployed on `/geoserver` URL

## Environment Variables

The `GeoServer` cartridge provides several environment variables to reference for ease
of use:

    OPENSHIFT_GEOSERVER_DB_HOST     	 	The GEOSERVER IP address
    OPENSHIFT_GEOSERVER_DB_PORT                 The GEOSERVER port
    OPENSHIFT_GEOSERVER_DB_LOG_DIR   		The path to the GEOSERVER log directory

## Demo

http://www.youtube.com/watch?v=8zY4kef3Nz0
