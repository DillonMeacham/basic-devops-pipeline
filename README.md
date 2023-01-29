<h1>Basic DevOps Pipeline</h1>

<h2>Description</h2>
In this project, we will be creating a basic DevOps pipeline all the way from making a code change to deploying that change to a production environment. The change we will be making is changing the header text on our page from "DevOps is Great!" to "DevOps is Awesome!"
<img src="https://imgur.com/Jk68Xzw.png" height="60%" width="60%" />
<br />
 - Let me go over the tools we will be utilizing in this project.
<br />
GitHub: The source control repo, where the application code is stored. We will be forking the repo from https://github.com/linuxacademy/devops-essentials-sample-app
<br />
<br />
Staging & Prod Server: There will be a server for verifying and testing changes, and another simulating the production environment.
<br />
<br />
Jenkins: We will use Jenkins for the entire orchestration process of this project. Taking code from GitHub, deploying it to the staging, and then handling deployment to production. 
<br />
<br />

<h2>Project walk-through:</h2>

I will start by forking the sample app repo from Linux Academy, which contains a basic HTML page that says "DevOps is Great" https://github.com/linuxacademy/devops-essentials-sample-app
<br />
<br />
<img src="https://imgur.com/whm8x8M.png" height="80%" width="80%" />
<img src="https://imgur.com/KH25T3H.png" height="80%" width="80%" />
<br />
<br />

Now we're going to configure the Jenkins CI server to point to the forked repo, which will scan and detect all the branches within that repo.
<br />
<br />
<img src="https://imgur.com/05RqBng.png" height="80%" width="80%" />
<img src="https://imgur.com/s25lF3d.png" height="80%" width="80%" />
<br />
<br />
After making code changes, make a pull request and merge new changes to personal fork master branch, which represent code that is ready to be deployed to production.
<br />
<br />
<img src="https://imgur.com/HB9QSt9.png" height="80%" width="80%"/>
<img src="https://imgur.com/gbPhGbD.png" height="80%" width="80%"/>
<br />
<br />
We are now going to return back to Jenkins CI server and deploy the change. It is important to verify the changes in the staging server before confirming the deployment to production.
<br />
<br />
<img src="https://imgur.com/Zy1TzrC.png" height="80%" width="80%" />
<img src="https://imgur.com/ggEUCJs.png" height="80%" width="80%" />
<img src="https://imgur.com/mLL1yYh.png" height="80%" width="80%" />
<br />
<br />
Thank you for following along.
