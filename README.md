<h1>Domain Name System</h1>
<h2>Objective</h2>
To configure a Cisco router to function as a Domain Name System (DNS) server for network endpoints in Cisco Packet Tracer by enabling DNS services, creating hostname-to-IP address mappings, and configuring endpoint devices to use the router as their DNS server. This lab aims to demonstrate how DNS resolves domain names into IP addresses, allowing devices to access network resources using hostnames instead of numerical IP addresses. The objective is to verify DNS resolution, test end-to-end connectivity, and troubleshoot DNS configuration issues to ensure reliable communication between network endpoints and internal network resources.
<h2>Program</h2>
<p align="center">
<img src="https://i.imgur.com/P4MVFMD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
On this project, we want to configure R1 to be act as a DNS server for the endpoints and having the IP addresses configured with a hostname so both IP address and hostname can be used interchangeably for DNS.
<p align="center">
<img src="https://i.imgur.com/dnnHqoP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
<img src="https://i.imgur.com/ZG9ut3J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
To verify, we configure the endpoints with an IP address of the DNS server portion and ping any endpoint with its hostname from R1 to verify that it has been configured correctly.
