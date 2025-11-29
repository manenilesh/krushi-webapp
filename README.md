# flask_krushikart
Reverse Proxy







Create Jenkins Credentials for DockerHub Token
    -   ID- dockerhub-token	
    -   Name- DockerHub access token for Jenkins pipeline	
    -   Kind- Secret text	



Create Jenkins Server [ Server for Configure all Jenkins File and add agent of Node ]
    -   Enter GitHub project Name
    -   POll SCM
    -   Pipeline Script
    -   Script
    -   Mention Node's Label



Create Node [Node for Implement actions on worker Node]
    -   Enter Configuration
    -   Enter Label
    -   Launch method
        -   Launch agent SSH
        -   Host - Worker machine IP
        -   Credentials
            -   username
            -   SSH Private-Key
                -   Server machine
    -   Availability
        -   keep this agent online
    



Copy Server SSH public-Key 
    -   Copy in to Worker Machine in Authorized Key

