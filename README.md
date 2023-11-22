# Identity manager

Identity manager (IdM) enabler is responsible for managing identities on the access control process. IdM is the enabler in charge to authenticate user and applications and other entities and checks if the user, password or token are valid for performing the identity process.

In combination with AuthzServer enabler it offers complete access control solution to Assis-IoT project.

# Identity Manager deployment

- [x] Must have docker and docker-compose installed.

### Go to the folder.
````
cd identity-manager/docker
````

##### On the path over the docker-compose.yml file excecute on the terminal.

```
docker-compose up -d
```



# For more info on Identitiy Manager see wiki page. [here](https://assist-iot-enablers-documentation.readthedocs.io/en/latest/verticals/cybersecurity/identity_manager_enabler.html)

# For a step by step configuration of Identitiy Manager see this document. [here](docker/docs/ASSIST-IoT_IDM_step_by_step.pdf)
