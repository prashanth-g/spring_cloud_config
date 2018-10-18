# spring_cloud_config

## Start config service

    $ cd config-service

    $ gradle bootRun

## Start client service

    $ cd config-service

    $ gradle bootRun

Centralized properties will be loaded from https://github.com/prashanth-g/spring_cloud_centralized_config.git

## Refresh config changes 

    $ curl http://localhost:8080/actuator/refresh --request POcdST -d {} -H "Content-Type: application/json"
