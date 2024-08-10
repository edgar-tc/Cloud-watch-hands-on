Hey folks, I'm excited to share my recent hands-on cloud DevOps project, where I monitored the CPU utilization of my EC2 instance using CloudWatch.

I created an EC2 Linux instance through an AWS CloudFormation template. CloudFormation helps in creating and managing AWS infrastructure efficiently.

Using CloudWatch, I set up a metric for monitoring the CPU utilization of my EC2 instance. Since this instance was for demonstration purposes, the CPU utilization was naturally low.

To simulate higher utilization, I wrote a Python script that spiked the CPU usage to over 80%. I also configured an alarm for CPU utilization at 50%. With this setup, if the CPU usage exceeds 50%, I receive an alert email through the SNS service, allowing me to effectively monitor my instances.

Benefits:

Cloud optimization of AWS services helps in cutting unnecessary expenses and ensures efficient resource usage.

As he wisely said, "Passion fuels my journey in cloud DevOps, turning challenges into opportunities to innovate and optimize. Every project is a step forward in mastering the art of efficient and effective cloud solutions."

Sevices used here, AWS Cloud Formation, AWS SNS, AWS Cloud Watch.
