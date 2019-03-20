
# NOS

## Help us to create better

![Help us to create better](https://raw.githubusercontent.com/PixelsCamp/hackathon/master/v3.0/assets/nos_help-us-to-create-better.jpg "Help us to create better")

## Context

In the original words of Steve Jobs: “Creativity is just connecting things. When you ask creative people how they did something, they feel a little guilty because they didn’t really do it, the just saw something. It seemed obvious to them after a while”.
 
The importance to remotely administrate your house internet gateway access (your router) has been rapidly growing. Be it for eco-friendly initiatives, enforcing conscious use by children or just technological bragging rights, remote management is everywhere.
 
At NOS, we have been adding support for this type of remote control in our internet products.
 
Learning from client feedback and multiple product iterations, we’ve managed to create a robust and functional rich solution: NOS NET. On it, and using desktop or mobile devices, you can remotely (as in anywhere in the world) manage your router on all available configurations.
 
On this year’s edition of Pixel Camp, not only will you be able to explore this cloud-based solution, you’ll also do it using NOS - not publicly available yet - new residential gateway equipment. This new router combines stability and performance with new broadband capabilities resulting in an internet experience better then ever seen.

## Details

NOS NET solution is exposed via easily accessible APIs that, once used in an authenticated form, allow for authorized router management.
Accounts for physical present routers will be provided allowing participants to set their development imagination run amok. We want to see how wild innovation can get!
No idea, technology or device should be left out. You have the device, you have de functionalities, you have the APIs.
Want to support this solution in your old JavaME phone? Have a thing about automation using residential available products? Interested in using a physical product for a more social or ecological activity? You think current solution (desktop or mobile) user friendliness is just lame? 
The best idea will be rewarded and after event  usability is guaranteed.
We want you, nay, we need you! Help us connect the dots!

## Resources

NOS NET API Doc: http://nos-apidocs.cloudapp.net/swagger-ui/?url=http://nos-apidocs.cloudapp.net/sites/default/files/blueprints/swagger-apis/nosnet/Nos%20Net%20FE%20API%20-%20v35%20-%20swagger.json#/
 
NOS NET API Endpoint https://tyr-prod.apigee.net/v5/nosroutermanager/
 
OAuth Authorize Endpoint: https://tyr-prod.apigee.net/nos_oauth2_v2_prd/authorize?redirect_uri=https%3A%2F%2Faminhanet.nos.pt%2Fv5%2FInicio&client_id={client_id}&response_type=token&state=XYZ&scope=user_profile
 
Redirect URI with token: https://aminhanet.nos.pt/v5/Inicio#access_token={access_token}&scope={scope}&state={state}&expires_in={expires_in}
 
OAuth Flow type:  Implicit Grant flow
 
How to get Credentials? Talk to us on Slack #NOS channel.
