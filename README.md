<h1>Install CloudWatch </h1>
<h2>Description</h2>
In this project I will download and install the CloudWatch Agent and configure it to capture 3 log files from an EC2 instance

/ var / log / secure


/ var / log / httpd/ access_log

/ var / log / httpd / error_log

I  will also configure an instance role allowing the agent to store the above config into parameter store AND allow the agent to inject the logging and metric data into CW and CW Logs.


<h2>Environments Used </h2>

 <b>AWS</b> 

<h2>Project walk-through:</h2>

 <h3> Install CloudWatch Agent <h3/>
   
<img src="https://i.imgur.com/UeoOfrq.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

  <h3> Create CloudWatch Role  <h3/>
    
<img src="https://i.imgur.com/G4g0W0F.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
<img src="https://i.imgur.com/mTDNany.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

<h3> Config CloudWatch   <h3/>
<img src="https://i.imgur.com/VOio5DZ.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

<h3> Store Config CloudWatch inside Parameter Store   <h3/> 
img src="https://i.imgur.com/JjeWznB.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

<h3> Test Log and Metrics   <h3/>
 img src="https://i.imgur.com/p1uFqGk.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
img src="https://i.imgur.com/fCzGnfd.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
