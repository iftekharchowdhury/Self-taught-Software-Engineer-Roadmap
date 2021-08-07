# Self-taught-Software-Engineer-Roadmap
<br>

# INTRO

<article> 
This roadmap is completely for mine. I make this for my own learning Purpose. I don't so many 
things but i still believe all those things all clear my confusion and darkness.<br>
</article><br>

**IF YOU WANT TO KNOW EVERYTHING ABOUT SYSTEM,APPLICATION and what's going on system,Then this RoadMap is for you.**

## Internet

1. How does the internet work?
2. What is HTTP?
3. Browsers and how they work?
4. DNS and How it works?
5. What is Domain Name?
6. What is hosting?

## HTML

1. Basics
2. Forms and validations
3. conventions and Best Practices

## CSS

1. Basics
2. Making Layouts
3. Responsive design and Media Queries
4. Float, positioning, Display, Box Model, CSS GRID , Flex Box

## Javascript

1. Basic
2. Syntax 
3. DOM, DOM manipulation
4. AJAX(XHR), Learn Fetch API
5. ES6+ and modular JS
6. Hoisting, Event Bubbling, scope, prototype, Shadow DOM, strict - concept

# Solve HackerRank JS problems

<article>
After Learning JS basic, syntax and core concept try to solve at least 50 basic problems using JS.Follow this link: <a>https://www.hackerrank.com/domains/tutorials/10-days-of-javascript</a>
</article>


# Learn Data Structure and Algorithms Concept

1. Learn the Basic Data Structure - 
2. Learn the Algorithms

**At least solve 100 problems using DS & Algo**

**You will face Coding Interview.**


## Project HTML, CSS, JS

<article>Try to make at least 10 projects. search for youtube, google but make yourself. Be honest!. After finishing the project, go through again everything. </article><br>

**Give yourself a timeline- like 3 months, 2 months!**

## Version Control Systems

1. Git (https://www.youtube.com/watch?v=oe21Nlq8GS4&ab_channel=LearnwithSumit)

## Repo Hosting Services

1. GitHub
2. GitLab


## Web security Knowledge

1. HTTPS
2. CORS
3. Content Security Policy
4. OWASP security Risks


# HTTP
<blockquote>
HTTP is a application layer protocol. It was designed for communication between web browsers and web servers.

## What’s in an HTTP request?

web browsers ask for the information they need to load a website. 
A typical HTTP request contains:

1. HTTP version type
2. a URL
3. an HTTP method
4. HTTP request headers
5. Optional HTTP body.

### What’s an HTTP method?

1. GET
2. POST

### What’s an HTTP method?

An HTTP response is what web clients (often browsers) receive from an Internet server in answer to an HTTP request. These responses communicate valuable information based on what was asked for in the HTTP request.

A typical HTTP response contains:

1. an HTTP status code
2. HTTP response headers
3. optional HTTP body

## What is HTTPS?

Hypertext transfer protocol secure (HTTPS) is the secure version of HTTP, which is the primary protocol used to send data between a web browser and a website. HTTPS is encrypted in order to increase security of data transfer. This is particularly important when users transmit sensitive data, such as by logging into a bank account, email service, or health insurance provider.

## How does HTTPS work?
HTTPS uses an encryption protocol to encrypt communications. The protocol is called Transport Layer Security (TLS), although formerly it was known as Secure Sockets Layer (SSL). This protocol secures communications by using what’s known as an asymmetric public key infrastructure. This type of security system uses two different keys to encrypt communications between two parties:

1. The private key - this key is controlled by the owner of a website and it’s kept, as the reader may have speculated, private. This key lives on a web server and is used to decrypt information encrypted by the public key.

2. The public key - this key is available to everyone who wants to interact with the server in a way that’s secure. Information that’s encrypted by the public key can only be decrypted by the private key.

## What is Transport Layer Security (TLS)?

A primary use case of TLS is encrypting the communication between web applications and servers, such as web browsers loading a website. 

## What does TLS do?
There are three main components to what the TLS protocol accomplishes: Encryption, Authentication, and Integrity.

> **Encryption**: hides the data being transferred from third parties.
> **Authentication**: ensures that the parties exchanging information are who they claim to be.
> **Integrity**: verifies that the data has not been forged or tampered with.

# What is CORS?

> Cross-Origin Resource Sharing

Cross-origin resource sharing (CORS) is a mechanism that allows a way for web pages to access API or assets running on a different restricted domain.

cors needs to declared at server side.

I have a domain which is www.domain-A.com. Now i want to use a picture in my domain A website. The picture is 
located at www.domain-B.com. When i sent GET request domain-B server for pictures, it will give me a cors error at browser.

Solution: i need to declare cors library at my backend code(nodejs-app.js) <br>

## Content Security Policy (CSP) 

is an added layer of security that helps to detect and mitigate certain types of attacks, including Cross Site Scripting (XSS) and data injection attacks. These attacks are used for everything from data theft to site defacement to distribution of malware.


</blockquote>

## Package Managers

1. npm

## Pick A Framework For Front End

1. React.js - Redux, mobX
2. **Modern CSS** - Styled Component, CSS module,Styled JSX, Emotion

## Web Components

1. HTML Template
2. Custom Elements
3. Shadow DOM
   
# BackEnd RoadMap

## OS and General Knowledge

1. Terminal Usage
2. How Os work in General
3. Process Management
4. Threads and Concurrency
5. Basic Terminal Command
   1. grep, awk, sed
   2. isof, curl, wget tail, head, less
   3. find, ssh, kill

6. Memory Management
7. Interprocess Communication
8. I/O Management
9. POSIX BASICS - stdin, stdout, stderr, pipes
10. Basic Networking concepts

## Learn a Language

1. Python
2. Bash
3. Go

## Back-End Frameworks

1. NodeJS
2. Django
3. .Net Core

## Relational Databases

1. PostgreSQL
2. MySQL

## NoSQL Databases

1. Document MongoDB, CouchDB
2. Column DBs Cassandra
3. InfluxDB, TimescaleDB
4. Realtime FireBase

## More about Databases

1. ORMs
2. ACID
3. Transactions
4. N+1 Problem
5. Database Normalization
6. Indexes and How they work
7. Data Replication
8. Sharding Strategies
9. CAP Theorem

## Learn about APIs

1. JSON APIs
2. SOAP
3. gRPC
4. REST
5. Authentication

### Authentication

1. Cookie Based
2. OAuth
3. Basic Authentication
4. Token Authentication
5. JWT 

## Caching

1. CDN
2. Server side - Redis, Memcached
3. Client Side

## Web Security Knowledge (Hashing Algorithms)

1. MD5 and why not to use it
2. SHA Family
3. scrypt, bcrypt

## Testing 

1. Integration Testing
2. Unit Testing
3. Functional Testing

## CI/CD 
### Design and Development Principles
1. SOLID
2. KISS
3. YAGNI
4. DRY

### Architectural Patterns

1. Monolithic Apps.
2. Microservices
3. SOA
4. Serverless

## Search Engines

1. Elasticsearch
2. Solr

## Message Brokers 

1. RabbitMQ
2. Kafka

## Containerization 

1. Docker

## Web Servers

1. Apache
2. Nginx


## Building for Scale

1. Migration Strategies
2. Horizontal vs Vertical Scaling


## Learn about Managing Servers

### Operating System

1. Linux
   1. Debian, Fedora, RHEL, CentOs, Ubuntu
2. Unix
3. Windows

## Networking, Security and Protocols

1. HTTP
2. HTTPS
3. FTP
4. SSL/TLS
5. SSH
6. PORT Forwarding
7. Basic Networking 

## Emails

1. SMTP
2. IMAPS
3. POP3S
4. DMARC
5. SPF
6. Domain Keys
   
## What is and How to setup a ------------

1. Reverse Proxy
2. Forward Proxy
3. Caching Server
4. Load Balancer
5. Firewall


## Learn Infrastructure as Code

### Service Mesh

1. Istio
2. Envoy
3. Linkerd
4. Consul

## Containers
1. Docker
2. LXC

## Configuration Management 

1. Ansible 
2. Chef
3. Puppet

## Container Orchestration 

1. Kubernetes
2. Docker Swarm
3. Mesos
4. Nomad


## Infrastructure Provisioning

1. Terraform
2. CloudFormation
3. Pulumi

# Learn how to monitor software and infrastructure 

## Infrastructure Monitoring 

1. Prometheus
2. Nagios
3. Grafana
4. Zabbix
5. Datadog
6. Monit

## Application Monitoring 

1. Jaeger
2. New Relic
3. Instana
4. AppDynamics
5. OpenTracing

## Logs Management 

1. Graylog
2. Splunk
3. Papertrail
4. Elastic Stack

## Cloud Providers
**Master only one**<br/>
1. AWS 
2. Google Cloud
3. Azure
4. Heroku



## Cloud Design Patterns 

1. Availability
2. Data Management
3. Design and Implementation
4. Management and Monitoring




# KEEP LEARNING :fist:


