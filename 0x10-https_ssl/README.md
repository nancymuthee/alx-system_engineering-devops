<center> <h1>HTTPS SSL</h1> </center>

HTTPS pages typically use one of two secure protocols to encrypt communications - SSL (Secure Sockets Layer) or TLS (Transport Layer Security). In the case of a website, the private key remains securely ensconced on the web server.
---

<br>
<center> <h2>General Use</h2> </center>

1. Allowed editors: vi, vim, emacs
2. All your files will be interpreted on Ubuntu 16.04 LTS
3. All your files should end with a new line
4. A README.md file, at the root of the folder of the project, is mandatory
5. All your Bash script files must be executable
6. Your Bash script must pass Shellcheck (version 0.3.7) without any error
7. The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
8. The second line of all your Bash scripts should be a comment explaining what is the script doing


<br>
<center> <h2>TASKS</h2> </center>
0.Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.

1.“Terminating SSL on HAproxy” means that HAproxy is configured to handle encrypted traffic, unencrypt it and pass it on to its destination.

2. A good habit is to enforce HTTPS traffic so that no unencrypted traffic is possible. Configure HAproxy to automatically redirect HTTP traffic to HTTPS.

<br>

@nancymuthee
