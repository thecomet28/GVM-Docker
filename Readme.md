![Greenbone Vulnerability Management with OpenVAS](https://github.com/SCS-Labs/Images/raw/main/scs-gvm.png)

This setup is based on Greenbone Vulnerability Management and OpenVAS. We have made improvements to help stability and functionality.

You want to send GVM/OpenVAS results to Elasticsearch, try our [GVM Logstash project](https://github.com/Secure-Compliance-Solutions-LLC/gvm-logstash).

## Documentation
* [View our detailed instructions on gitbook](https://securecompliance.gitbook.io/projects/openvas-greenbone-deployment-full-guide)

If you would like something added to the documentation please create a issue [GVM-Docker Gitbook Repo](https://github.com/Secure-Compliance-Solutions-LLC/gitbook/issues)

## Architecture

The key points to take away from the diagram below, is the way our setup establishes connection with the remote sensor, and the available ports on the GMV-Docker container. You can still use any add on tools you've used in the past with OpenVAS on 9390. One of the latest/best upgrades allows you connect directly to postgres using your favorite database tool. 

![GVM Container Architecture](https://securecompliance.co/wp-content/uploads/2020/11/SCS-GVM-Docker.svg)
