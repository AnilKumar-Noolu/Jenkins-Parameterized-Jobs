# Jenkins-Parameterized-Jobs
This Repo is for Parameterizing jobs in Jenkins

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

![Screenshot (10)](https://user-images.githubusercontent.com/98457309/227216587-a53356b2-a2d7-44e8-a19a-3359afd758ae.png)

Here we have given Name as fruits, given choices and description.

Go to Build step and select Shell, add a shell command here: echo $fruits

![Screenshot (11)](https://user-images.githubusercontent.com/98457309/227216716-c1d263a3-d521-4e8e-9aa4-5b02671d2459.png)

after that save that job, and previously you used to have Build Option, Now it will be Build With Parameters, click that and select ypur favourite fruit. 

![Screenshot (12)](https://user-images.githubusercontent.com/98457309/227216811-019bb5a1-a437-4365-8243-6ec39187cd51.png)

Once the job run is completed, you will get the desired output.
![Screenshot (13)](https://user-images.githubusercontent.com/98457309/227216926-7e4cefc3-83df-4c6e-9daf-880433f2da33.png)




