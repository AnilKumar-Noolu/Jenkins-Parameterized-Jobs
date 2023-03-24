The above Jenkins file consists of details on how to deal with the parameters of different types like string, text, boolean, toggle, password, choice..

We will follow Declarative pipeline syntax for the above Jenkinsfile where no specific agent is labelled.

You can create a new Job of type Pipeline in Jenkins and while configuring it, Do following steps:

You can directly add your code in the Script section of the pipeline or you can attach your GitHub repo with Jenkinsfile in it, Both will work.

![Screenshot (14)](https://user-images.githubusercontent.com/98457309/227581951-136af9ac-9ab7-403c-91e0-ae14d7b74a9a.png)

After adding the script, save it and then in the left side of this job, you can ind the option of Build with Parameters, click on it.

After Clicking on 'Build With Parameters', you will get the following Display:

![Screenshot (15)](https://user-images.githubusercontent.com/98457309/227583032-a5b37c8b-6fac-407f-a17d-eebabced475b.png)

![Screenshot (16)](https://user-images.githubusercontent.com/98457309/227583105-8a2dd3ab-1ea3-42ec-baba-3e853393b0df.png)

Give all the required details and click on Build at the bottom. Now the Pipeline will run and you can see the output by clicking on the build output.

![Screenshot (17)](https://user-images.githubusercontent.com/98457309/227583634-57b03a6b-d963-47c4-9366-df53ae8defe3.png)

In this way, You can make use of Parameters in Jenkinsfile Instead of Hardcoding them, You can make use of choices, passwords in some specialized usecases. 
