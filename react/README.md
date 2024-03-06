Title: Deploy a Mearn Application to a Linux Server
1.Explain the Architecture 
2.Test Application Locally(Docker test)
3.Set up Production server(Ansible)
4. Push Application to Git
5.Clone Application onto Production server
6.Set up Nginx web server and set up server block configurations(Ansible)
7.Run the application after configuring the environment.
#############################
#############################
#############################
Solutions: 
2.To test applications locally write a dockerfile based on the project requirement. Then build the docker file and then run the docker image mentioning the port. Here is a sample of my dockerfile: 


3. To install all the required items to the Ubuntu server, Ansible is used here. Based on the project requirement we write our playbook file and inventory.



