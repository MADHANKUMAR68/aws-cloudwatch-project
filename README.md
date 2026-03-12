# AWS CLOUDWATCH PROJECT DETAILS
DESCRIPTION :This is the demo project for using cloudwatch to monitoring the cpu utilization and trigger alarm using SNS service

STEP1 :Create EC2 instance and login to terminal ,prerequest install python and put the cpuspike program file inside the ec2 instance..

STEP2 :Check inside cloudwatch monitor your instance ,The cpuutilization is normal now ,add alarm to your instance using cloudwatch(cpuutilization)..

STEP3 :After that in your terminal run the python program (cpuspike.py)..after few  minuetes your cpuutilization get high..

STEP4 :Check your instance state in cloudwatch its already get spike the cpuutilization..

STEP5 :Check your email and confirm the notification from AWS..

that's it..
