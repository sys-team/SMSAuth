SMSAuth
============

register
------------

Request to register the new phone number or change passsword for the registered phone number. Sends the sms message with activation code

### variables:
* phone - phone number
* password - new password

### returns:
result = "ok" if success or error text if an error occurs

    <response>
        <result>ok</result>
    </response>

activate
------------
Activates the new number or confirms password change for the registered one.

### variables:
* code - activation code from sms message

### returns:
result = "ok" if success or error text if an error occurs

    <response>
        <result>ok</result>
    </response>
    
auth
------------
Authentificates registed user

### variables:
* phone - phone number
* password - new password

### returns:
* access token if success or error text if an error occurs

	<response>
		<access-token>da82b653-8ed2-4963-a6e0-50d6d5010e1b</access-token>
	</response>



