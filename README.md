# ATM Fund
The base endpoint is: https://atm.fund/api.php

## Check Email
All items have some of the following properties

request method GET

Parameter	|	value
---------	|	-----------
key	| key production
action	| check_email
email	| youremail@domain.com

## Check Username
All items have some of the following properties

request method GET

Parameter	|	value
---------	|	-----------
key	| key production
action	| check_username
username	| yourusername

## Verification Account
All items have some of the following properties

request method GET

Parameter	|	value
---------	|	-----------
key	| key production
action	| change_ver
email	| youremail@domain.com

## Registration Account
All items have some of the following properties

request method POST

Parameter	|	value
---------	|	-----------
key	| key production
action	| input_id

Field	|	required
---------	|	-----------
fullname	| yes
username	| yes
email | yes
password  | yes
sponsor | no
