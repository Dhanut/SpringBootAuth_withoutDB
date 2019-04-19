# SpringBootAuth_withoutDB
# All the credetial details in the application.yml file

localhost:8282/auth/token (Basic-Auth ==== username = mobile, password = pin) =============GET
localhost:8282/oauth/token (Basic-Auth ==== username = mobile, password = pin)=============POST
			   (Body = formurlencoded====== grant_type = passowrd, username = Thisaru, password =Thisaru123)
localhost:8282/oauth/check_token?token=2c2c243e-9d25-44c6-9a85-7dacfd44c32f===============GET ( with Basic Auth or No Auth)
