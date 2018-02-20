# dala-fineract-database and dala-server stacks
storage and server setup for your dala fineract stack

To Run simply update the "yarn deploy-storage" or yarn "deploy-server" and be prompted for options.

Or 

Setup up your own custom command in your package.json scripts section

"deploy-wala-dala": "sh deploy/create-or-update-storage-stack.sh <aws-profile-name> <stack-name> <aws-region> <aurora-cluster-username> <aurora-cluster-password> <dala-infrastructure-stack-name>"

"deploy-wala-dala": "sh deploy/create-or-update-server-stack.sh <aws-profile-name> <stack-name> <aws-region> <aurora-cluster-username> <aurora-cluster-password> <dala-infrastructure-stack-name> <key-pair-name> <storage-stack-name>"
