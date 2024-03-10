# CD12352 - Infrastructure as Code Project Solution
# [Dai Bui]

## Spin up instructions
Switch to folder `starter`. Open Git Bash terminal.
Run `sh ./scripts/create_stack.sh udagram-network-dev network.yml network-parameters.json`
Run `sh ./scripts/create_stack.sh udagram-app-dev udagram.yml udagram-parameters.json`

## Tear down instructions
Switch to folder `starter`. Open Git Bash terminal.
Run `sh ./scripts/delete_stack.sh udagram-app-dev`
Run `sh ./scripts/delete_stack.sh udagram-network-dev`

## Other considerations
Output of udagram.yml is Application Load Balancer DNS Domain.
Open the DNS Domain on browser to see the web application
http://udagra-appli-gsivg99mg4dz-1558411198.us-east-1.elb.amazonaws.com
