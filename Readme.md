---


---

<h1 id="introduction">Introduction</h1>
<p>This repository contains the process to deploy the java project on the cloud. The project used to deploy is Trading Application:<br>
<a href="https://github.com/gursimran258/Trading_App">https://github.com/gursimran258/Trading_App</a></p>
<p>This project is a microservice in java configured using Springboot framework with database in PostgreSQL database. It consumes IEX cloud API.</p>
<h1 id="docker-architecture-diagram">Docker Architecture Diagram</h1>
<ul>
<li>
<p>trading_app docker diagram including:</p>
</li>
<li>
<p>use <a href="http://draw.io/">draw.io</a> and AWS icons (it’s already in <a href="http://draw.io/">draw.io</a> library)</p>
</li>
<li>
<p>images (docker hub and local)</p>
</li>
<li>
<p>bridge network</p>
</li>
<li>
<p>containers</p>
</li>
<li>
<p>label commands</p>
</li>
<li>
<p>Two docker files</p>
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
<li>trading app diagram
<ul>
<li>use <a href="http://draw.io/">draw.io</a> and aws icons (it’s in the <a href="http://draw.io/">draw.io</a> library)</li>
<li>include ec2, alb, auto scaling, target group, rds</li>
<li>security groups</li>
<li>label all important ports(e.g. ALB HTTP, ec2 tpc:5000, RDS tcp:5432)</li>
</ul>
</li>
</ul>
<h1 id="elastic-beanstalk-todo">Elastic Beanstalk (TODO)</h1>
<h1 id="jenkins-cicd-pipeline-todo">Jenkins CI/CD pipeline (TODO)</h1>

