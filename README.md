# tamiltoken-node-validator
validate uptime of node and pinned content

# we will use to 
https://github.com/AudiusProject/py-ipfs-api.git



~/Documents/repos/tamiltoken-node-validator

## kava laptop (ubunutu mate)
virtualenv --python /usr/bin/python3.6  .

pip install -r requirements.txt


## kava windows desktop
virtualenv --python "/c/Python38/python.exe" .

source ./Scripts/activate

/c/Python38/Scripts/pip install -r requirements.txt

/c/Python38/python app.py


# Branching strategy
git flow init

# 
every node validators will ramdomly select CIS's and peer ID from public json (published by lambda)

and verify node's availability and content PIN status and record in orbitdb.


every node validator/pin 

