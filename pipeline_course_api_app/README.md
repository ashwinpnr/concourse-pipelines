# Course API Concourse Pipeline
Concourse pipeline to deploy Course API in https://github.com/ashwinpnr/SpringBootApplications.git

The pipeline downloads the source code, build the project and upload jar file to S3 repository
Then this jar is pushed to pcf.

Prerequisites 
------------------
1)AWS S3 bucket needs to be created. Have to get keyid and accesskey also.

2)Have a pcf setup
   
   Free Development Account can be created : https://run.pivotal.io/
