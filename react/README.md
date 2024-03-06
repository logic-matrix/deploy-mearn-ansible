Title: Deploy a Mearn Application to a Linux Server
<br>1.Explain the Architecture 
<br>2.Test Application Locally(Docker test)
<br>3.Set up Production server(Ansible)
<br>4. Push Application to Git
<br>5.Clone Application onto Production server
<br>6.Set up Nginx web server and set up server block configurations(Ansible)
<br>7.Run the application after configuring the environment.
<br>
<br>
#############################
#############################
#############################
<br>
<br>
Solutions: 
2.To test applications locally write a dockerfile based on the project requirement. Then build the docker file and then run the docker image mentioning the port. Here is a sample of my dockerfile: 


3. To install all the required items to the Ubuntu server, Ansible is used here. Based on the project requirement we write our playbook file and inventory.



