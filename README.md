# Jenkins-Parameterized-Jobs
Parameterizing jobs in Jenkins

A build Parameter allows us to pass data into our jenkins jobs. 
Using Build Parameters, we can pass any data we want like git branch name, secret credentials, hostnames and ports.....

Any Jenkins job or pipeline can be parameterized. All we need to do is check on the box on the General Settings Tab, "This project is parameterized"

![Screenshot (8)](https://user-images.githubusercontent.com/98457309/227211362-728cb435-0753-4ad0-afaa-2936a96153f0.png)

There are multiple types of parameters in Jenkins ->
Type: string, choice, credentials, File, boolean etc..
![Screenshot (9)](https://user-images.githubusercontent.com/98457309/227213037-6dfaceac-d9fd-4a3d-a530-7f756c0d0f69.png)
Name: Name of the parameter
Default value: Optional value that will be used when a user doesn't specify one
Description: Optional text that desribes how the parameter is used.

A single Jenkins job can have multiple parameters. The only restriction is that parameter name must be unique.
