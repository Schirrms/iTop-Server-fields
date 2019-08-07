# iTop-Server-fields
Some Custom fields for the Server CI

# Goal
We use some specific fileds in our organization. These are probably totally useless in another context, but as I try to put all extensions toghether...

The attrubites addes are 
* Model Number (mostly the model reference numbre from the brand company)
* S_UUID : here, we store the UUID of the system, very useful for all our datasynchronization to be sure to work on the good system (You can see the UUID as a 'Soft Serial Number', but easier to catch)
* S_Function : This field should disapear in a 'near future' : this is the business main use of the server

There is also a test function to display 'dynamic data' in the Server field, but at this time, the dynamic data are hardcoded to 'Test PS'...

# Installation
As for all my extentions, just download the zip file, and copy the 'schirrms-...' directory in your extensions directory, then rerun the setup as usual.
