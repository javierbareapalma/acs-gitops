#### acs-gitops
## Step 1
oc apply -k bootstrap/base 
## Step 2
oc apply -k bootstrap/deploy/applications
## Step 3
# wait
## Step 4
# Profits! 