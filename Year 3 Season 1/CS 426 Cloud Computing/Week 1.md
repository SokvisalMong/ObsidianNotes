IaaS = Infrastructure as a Service
PaaS = Platform as a Service
SaaS = Software as a Service

Bottom &rarr; Up order:
- Application
- Datas
- Runtime
- Middleware
- Linux/Windows

Network and Cloud Infra:
When users try to access the network, they should pass through a firewall first
Depending on the type of request:
- email: send the user to the email server then pass through another firewall before sending that email to internal servers
- application: send the user to a load balancer, then firewall, then to the application server that is configured with master and slaves. The application server also has to access the database (with more master and slave networks) through a firewall as well.

