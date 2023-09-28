# groovy-cli-maven-cockroachdb-single-node-without-ssl-index

## Description
Creates a small database table
called `dog`. This table, `dog`, has been normalized to 3NF.
All output normally
seen in a terminal will be in `log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

A groovy maven build, that connects to single node
cockroach database without ssl.

## Tech stack
- groovy
- maven
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
