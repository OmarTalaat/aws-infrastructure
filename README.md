



# AWS-WebApp-Stack
    this stack created by Omar Othman , infrastructure and Server Stack For High Availability Web App Deployment.
     
# how to run 

    for infrastructure:
        for creation:
            ./create.sh infrastructure  network.yml network-parameters.json
        for update
           ./update.sh infrastructure  network.yml network-parameters.json
        for destroy
           ./destroy.sh infrastructure

    for serve:
        for creation:
            ./create.sh server  server.yml server-parameters.json
        for update
            ./update.sh server  server.yml server-parameters.json
        for destroy
           ./destroy.sh  server
 # The files included are:
        flowchart.jpeg
        create.sh 
        update.sh
        network.yml
        network-parameters.json
        server.yml
        server-parameters.json
        destroy.yml
        README.md




# Url of the project


    http://serve-loadb-hk7dm2yxbnlt-542669547.us-east-1.elb.amazonaws.com/
