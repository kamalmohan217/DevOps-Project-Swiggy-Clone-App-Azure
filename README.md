# DevOps-Project-Swiggy-Clone-App-Azure

![image](https://github.com/user-attachments/assets/9242ffdc-132a-4785-b853-8dcb82e2e7ec)

For this project I kept the source code in the Azure Repos as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/b31c4959-d138-4366-8457-52fc1ec33ac1)

The service connection has been created for Docker Registry as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/7ede4d31-b621-4a86-8309-5e850dc80c2d)

The screenshot for azure pipeline has been shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/0ff3ec77-f4eb-4dc2-8daf-6936480c395c)

After runnging the Azure Pipeline the screenshot for SonarQube and swiggy app (ReactJs based User Interface which runs on port 3000) is shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/a28837a3-2a6d-480f-b672-89458cfb09e6)
![image](https://github.com/user-attachments/assets/dd4c4d1b-f841-4ff0-8e71-b421dd5fccf3)

Entry for Azure DNS Zone is shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/ee6526da-ba2c-4aae-8584-aa892722f962)

Finally we can access the swiggy clone app as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/57aaf533-3414-4633-a254-8983ae1edf14)


```
The swiggy-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry swiggy-clone-auth --docker-server=https://swiggycontainer24registry.azurecr.io --docker-username=swiggycontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX -n swiggy
```

<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:- https://github.com/kamalmohan217/Swiggy-Clone-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://muditmathur121.medium.com/securing-swiggy-clone-app-deployment-on-aws-a-comprehensive-guide-to-building-a-devsecops-pipeline-67bdd7ea004e
```
