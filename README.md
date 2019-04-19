# SpringBootAuth_withoutDB

# Remove the proerties in application.yml file 

# Create 2 users 

localhost:8282/oauth/token (Basic-Auth ==== username = mobile, password = pin)=============POST
			   (Body = formurlencoded====== grant_type = passowrd, username = Thisaru, password =Thisaru123)

localhost:8282/oauth/check_token?token=2c2c243e-9d25-44c6-9a85-7dacfd44c32f===============GET ( with Basic Auth or No Auth)

localhost:8282/oauth/token (Basic-Auth ==== username = mobile, password = pin)=============POST
			   (Body = formurlencoded====== grant_type = passowrd, username = Dhanu, password =Dhanu123)

localhost:8282/oauth/check_token?token=f41cf8dc-a256-476d-a707-928088d0756b===============GET ( with Basic Auth or No Auth)

