---


---

<h1 id="introduction">Introduction</h1>
<p>This repository consists of steps that can be followed to deploy java applications on AWS. The project used to deploy is virtual trading application:<br>
<a href="https://github.com/gursimran258/Trading_App">https://github.com/gursimran258/Trading_App</a></p>
<p>This project is a microservice in java configured using Springboot framework. The primary goals for this simulation REST API are registering traders, managing their accounts, buying or selling stocks, and retrieveing the quores from IEX cloud.</p>
<h1 id="docker-architecture-diagram">Docker Architecture Diagram</h1>
<p>The trading application is dockerized in order to make deployment on AWS easy.  Creating docker container for the application and successfully running the container ensures that it will run successfully on other machines that can run docker. Following is the diagram illustrating the creation of docker images and running the docker containers of the created images.</p>
<p>Following are the steps followed to dockerize the application:</p>
<ol>
<li>mvn is used to build the trading application when dockerizing the application on local machine:<br>
<code>mvn clean package</code></li>
<li>When  cloning the git repo:<br>
<code>git clone https://github.com/gursimran258/Trading_App</code></li>
<li>Docker images for trading_app and psql are build by:<br>
<code>cd Trading_App</code><br>
<code>sudo docker build -t Trading_App .</code><br>
<code>cd psql/</code><br>
<code>sudo docker build -t jrvs-psql</code></li>
</ol>
<ul>
<li>images (docker hub and local)</li>
<li>bridge network</li>
<li>containers</li>
<li>label commands</li>
<li>Two docker files
<ul>
<li>trading-app</li>
<li>talk about the process (e.g. compile and package jar and run the app)</li>
<li>jrvs-psql</li>
<li>talk about how to create tables (e.g. schema.sql)</li>
</ul>
</li>
</ul>
<h1 id="cloud-architecture-diagram">Cloud Architecture Diagram</h1>
<ul>
<li>trading app diagram  -see the diagram in cloud dep</li>
</ul>
<h1 id="elastic-beanstalk">Elastic Beanstalk</h1>
<h1 id="jenkins-cicd-pipeline">Jenkins CI/CD pipeline</h1>

