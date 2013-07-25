SMSAuth
============

auth
------------

Sends the sms message with code for token service

### variables:
* mobile_number - phone number

### returns:
Id of mobile phone account if success or error text if an error occurs

    <response>
        <account-id>0000</account-id>
    </response>

token
------------
Authentificates user

### variables:
* account_id - account id recived from auth service
* sms_code - code from sms nessage

### returns:
access token if success or error text if an error occurs

	<response> 
		<access-token>0000<access-token> 
	</response> 