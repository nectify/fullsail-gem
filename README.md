shipyard-cli
============

shipyard client side


to register your deployments call:


  ShipyardCli.deploy(application, environment, status,[commit_hash])


application [a-z A-Z 0-9]: name of your application

environment [a-z A-Z 0-9]: environmement deployemts for exemple 'development', 'staging'...

status [0-9]]: '-1' in progress   /  '0' done

commit_hash (optional): commit hash from git, other...