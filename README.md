# Jenkins-Parameterized-Jobs
Parameterizing jobs in Jenkins

A build Parameter allows us to pass data into our jenkins jobs. 
Using Build Parameters, we can pass any data we want like git branch name, secret credentials, hostnames and ports.....

Any Jenkins job or pipeline can be parameterized. All we need to do is check on the box on the General Settings Tab, "This project is parameterized"

![Screenshot (8)](https://user-images.githubusercontent.com/98457309/227211362-728cb435-0753-4ad0-afaa-2936a96153f0.png)

There are multiple types of parameters in Jenkins 

Type: string, choice, credentials, File, boolean etc..

![Screenshot (9)](https://user-images.githubusercontent.com/98457309/227213037-6dfaceac-d9fd-4a3d-a530-7f756c0d0f69.png)

Name: Name of the parameter

Default value: Optional value that will be used when a user doesn't specify one

Description: Optional text that desribes how the parameter is used.

A single Jenkins job can have multiple parameters. The only restriction is that parameter name must be unique.

Let us Take the example of choice type Parameter:

![Screenshot (10)](https://user-images.githubusercontent.com/98457309/227214866-6cd2f43f-8ccd-4d42-884a-bb15787b4159.png)

Here we have given Name as fruits, given choices and description.

Go to Build step and select Shell, add a shell command here: echo $fruits

![Screenshot (11)](https://user-images.githubusercontent.com/98457309/227215160-88834b97-c6e5-46fa-a45b-a5a682a497d5.png)

after that save that job, and previously you used to have Build Option, Now it will be Build With Parameters, click that and select ypur favourite fruit. Once the job run is completed, you will get that output.

![Screenshot (12)](https://user-images.githubusercontent.com/98457309/227215517-97771693-00e5-4b9a-b208-f35304737924.png)

