# Wordpress Web on AWS Lightsail

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/cddaf3d0-89b0-4c81-9b9d-2681c78bfcf5)


![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/f55a3643-1208-46cb-ae55-8c8612f541e3)


Copy the Public IP in the browser with /wp-admin:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/8e220d86-b6e3-459a-bc47-dc1c1a01e197)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/747c1c59-8ba0-4741-8dce-0034f4b78a96)

Enter the username 'user' an to get the pasword click on 'Connecting using SSH'

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/4418ad50-245c-403a-9f59-5f6bee995dd6)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/c684f2d2-4bc6-4432-a58a-6b68b5253ed1)

Now we are in Wordpress:


![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/ae98ae8f-6015-4339-85a0-401f3c1ad205)

Select Netwroking tab and Attach static IP:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/28f7e0df-6144-4799-9edc-e8c10ba8f801)



create static IP with a name:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/f9e0c6ad-1f0a-4499-961b-f652d15a4620)
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/a204a1e0-3df6-4f61-8646-fa8b6b6a9aa0)

create a domain:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/bd9d4892-c9a6-4cb2-b4b5-9bced1de0a08)

add a DNS record to point to the apex of your domain with the static IP from your WordPress instance:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/b96ae41f-f0e2-44e6-976b-3526bcc8bbe9)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/c229acd4-b760-4d38-866e-52d6430b96f7)

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/53d6b536-d95c-4c86-b095-e27f00a6f89c)

Now go to the Register Domain website (ex: Godaddy):
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/56c860c2-eee2-4ec0-bacd-dfa6d1fff48d)

click on Manage DNS, Nameservers, change:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/c8ec3d3e-a46f-4b23-b55c-c5892b566a93)
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/ff7cc791-7058-43bf-bdaf-f39bc8429beb)


add domain:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/938507d5-5a17-4f9f-95ca-190b860c1b17)


enable https and redirection:
![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/d9df9d97-8820-4455-8569-bce7e2e632ff)


enter email and nencrypt subscriber agreement

This is the final website:

![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/495b6ea4-a64d-4dd5-94bf-3931a574c662)

it is valid and secure:


![image](https://github.com/redjules/wordpress-web-on-AWS-Lightsail/assets/106017493/d76c898b-51f2-4874-9dd0-f0320cd0e4b7)

