Reference Architecture

https://aws.amazon.com/blogs/architecture/wordpress-best-practices-on-aws/


#Ask 

1. To host a Wordpress in a EC2 instance with a RDS Backend. (for Both Prod & Stg)
2. Load the static content in EFS Parition and should be mounted in EC2 in fstab, 
3. Create CLoudwatch logs/alarms for monitoring load and accessability (eg:- Operations team needs to be notified if the host is out of resources or is down for longer than 10 mins)
