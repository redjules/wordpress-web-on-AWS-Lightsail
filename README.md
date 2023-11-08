# Wordpress Web on AWS Lightsail

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/cddaf3d0-89b0-4c81-9b9d-2681c78bfcf5)


![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/f55a3643-1208-46cb-ae55-8c8612f541e3)


Copy the Public IP in the browser with /wp-admin:

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/3bc32e88-89d2-40d9-80ea-81f2191bdb72)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/7079c504-a8d4-46ac-a300-ae01b83f692f)

Enter the username 'user' an to get the pasword click on 'Connecting using SSH'

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/4418ad50-245c-403a-9f59-5f6bee995dd6)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/c684f2d2-4bc6-4432-a58a-6b68b5253ed1)

Now we are in Wordpress:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/fe3eee07-9508-4b14-ae8e-cffa7b9771a9)

Select Netwroking tab and Attach static IP:

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/47b2ba6a-8ca7-49a1-abe8-6ef0f62ab7ef)


create static IP with a name:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/f9e0c6ad-1f0a-4499-961b-f652d15a4620)
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/a204a1e0-3df6-4f61-8646-fa8b6b6a9aa0)

create a domain:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/44007e55-9533-48eb-bfae-66c661678a08)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/c272d222-ee1c-438b-870e-4d78a8ac985d)

add a DNS record to point to the apex of your domain with the static IP from your WordPress instance:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/2fa1dd4a-1efa-407e-af3d-fd797e277c8e)
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/fbde21f9-f00f-44c0-ab1c-11a89bdbb8ac)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/0eaaf0fb-8ebb-403d-9d37-b687ebe8fc20)

Now go to the Register Domain website (ex: Godaddy):
