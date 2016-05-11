---
layout: default
---

## @revmischa - Amazon Web Services Thought Lord

### Who Am I?
I am a software engineering professional based in San Francisco. I have a wealth of experience with software development and operations, and one of my specialties is AWS architecture and provisioning. I'm advertising my services as a consultant on designing, implementing, automating, improving and saving time and money with AWS. 

### What Have I Done?
* Live-migrated a health-tech company's infrastructure from a traditional datacenter to a HIPAA-compliant, secure AWS environment.
* Implemented functionality with EC2, S3, SNS, SQS, Lambda, CloudWatch, CloudFront, ElasticCache, API Gateway, RDS PostgreSQL, Route53, CodeDeploy, IAM, IoT, SES.
* Released a [command-line tool suite](https://github.com/revmischa/udo) named "Unemployed DevOps" for wrangling clusters with AutoScaling Groups and CodeDeploy.
* Presented a [talk on AWS](https://github.com/revmischa/lazyaws) about best practices, automating everything and how to simplify your setup using standard unix tools that have been around for decades.
* Designed monitoring and alerting systems based around CloudWatch, Lambda, SQS, Slack.
* Reduced costs by eliminating wasteful services, using AutoScaling, removing special snowflake instances, optimizing request flow and server load to take full advantage of EC2 instances.
* Massively streamlined deployments with AWS-native CodeDeploy.
* Reduced web application server load and optimized static file delivery with nginx and CloudFront CDN.
* Created highly available web application services and RDS multi-AZ database failover.

### Do I Know What I'm Doing?
I do not claim to know everything about AWS, but I do have access to many people who are highly knowledgeable. When I need advice or have questions I often speak with Amazon directly either via support or in-person at their AWS Loft in San Francisco. They have guided me and validated my general approach and specific deployments. 

### What Can I Do For You?
Review your infrastructure, cut down costs, validate security models, make recommendations on efficiency improvements, and most importantly, automate the heck out of everything. 
I am not seeking long-term employment doing AWS management. You should have everything automated anyway. I will help you get there. I am first and foremost a lazy engineer.

### How Do I Do It?
* Automate common tasks like deployment, reading tags, SSHing into hosts and much more using awscli bash scripts or boto3 python scripts.
* Consolidate useful scripts and commands using a simple Makefile.
* [Create RPMs](https://github.com/revmischa/lazyaws/tree/master/rpm) for instance configuration, dependencies, provisioning.
* [Use Udo](https://github.com/revmischa/udo), a simple command-line interface for defining clusters and roles for instances using AutoScaling groups. Define packages to install and generate reusable cloud-init scripts for each cluster and role.
* Create CloudWatch lambdas and alerts for monitoring and notifications.
* Consolidate disparate services into PostgreSQL, which can act as your [pubsub message passing server](https://github.com/revmischa/pgnotify-demos), [full-text search](http://www.postgresql.org/docs/9.3/static/tsearch2.html) (still using ElasticSearch? for shame...), [JSONB](https://www.depesz.com/2014/03/25/waiting-for-9-4-introduce-jsonb-a-structured-format-for-storing-json/) for document stores and much much more. You are using PostgreSQL, right?

### What I Won't Do For you
* Configure your Oracle license
* Defend your hare-brained microservices architecture idea
* Read HackerNews comments
* Create enterprise java build systems
* Waste time with configuration management systems for AWS (seriously stop doing this it's wrong)
* Troubleshoot your Elastic Beanstalk setup. You probably don't need EB anyway. Use Udo and AutoScaling groups instead.

### Sounds Interesting, Now What?
[Hit me up](contact) and we can chat and see if I can help you out. If I can't, no problemo.
