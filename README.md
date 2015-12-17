#ranchertest

simple webserver to test rancher deployment

To deploy the app to rancher
===========
rancher-compose --debug  --url {rancher server:port} --access-key {key generated in rancher} --secret-key {matching secret key} -p ranchertest up

