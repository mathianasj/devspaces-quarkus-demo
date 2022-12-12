# Dev Spaces Demo

## Devfile Creation

1. Fork this repo
1. Create a new devspace using the forked repo
    1. Show starting as vscode
    1. Everything is setup to match other developers workspaces, did not require any work to get started building and coding
    1. The terminal is actually a linux container that will match the runtime environment even if you are running on windows, mac, linux, chrome book you can still have access to a full linux terminal
1. Run the devspaces-demo
    1. access the endpoint from curl in the terminal
        ```curl http://localhost:8080/hello```
    1. Access the endpoint from the local browser
1. Now we need to start coding against a database, how will we keep this consistent across developers
    1. Update the devfile to contain a db container in addition to the workspace
    1. Run the devspaces-db-demo
    1. Show connecting to the db with vs code extension
    1. Show connecting to the db with terminal
    1. Execute the openapi endpoint to add a new task
    1. Show the database now has the entry
    1. Highlight this is identical to running the ide locally but is consistent across different workstations
1. Show the openshift deployment aspects and single click on the IDE
