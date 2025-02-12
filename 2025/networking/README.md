# Heading 1🛜Networking
 OSI & TCP IP Models?

*️⃣ OSI (Open Systems Interconnection) Model TCP (Transmission Control protocol/Internet Protocol) Model are framework that explain how data travels over a network, such as the internet. The divide the communication process into different layers, each with a specific role.

*️⃣ 7 Layers of OSI Model

1️⃣ Physical Layer - Sends raw data as electrical signals or light.

(Example: Wi-Fi, Ethernet cables fiber optics).

2️⃣ Data Link Layer - Manages direct connections between devices using MAC addresses.

(Example: A switch connecting computers in a local network.)

3️⃣ Network Layer - Handles IP addressing and routing data across network.

(Example: A router forwarding data based on IP addresses).

4️⃣ Transport Layer - Ensures reliable data delivery with error checking and flow control.

(Example: TCP (reliable data),UPD (fast but no guarantee).

5️⃣ Session Layer - Manages communication sessions(start, stop, resume).

(Example: Logging into a website and maintaining a session).

6️⃣ Presentation Layer - Converts and encrypts data for security and compatibility.

(Example: SSL encryption for secure websites).

7️⃣ Application Layer - Provides services and apps to the user.

(Example: Web browsers (Chrome),email apps(Gmail).

*️⃣ 4 Layer of TCP IP Model

1️⃣ Network Access Layer - Handles physical connections.

(Example: Wi-Fi, Ethernet cables, MAC addresses).

2️⃣ Internet Layer: Manages IP addresses and routing .

(Example: IP addresses ,routers).

3️⃣ Transport Layer - Ensures correct delivery of data .

(Example: TCP for reliability UPD for speed).

4️⃣ Application Layer: Provides user-facing application

(Example: ( HTTP,FTP, emails).

📍 Networking Protocol and Ports!

1️⃣ HTTP (Hypertext Transfer Protocol)

Port: 8080

Used for communication between web server and browsers.

2️⃣ HTTPS (Secure HTTP)

Port: 443

Encrypted version of HTTP for secure web communication.

3️⃣ SSH (Secure shell)

Port: 22

secure remote login to server for configuration and management.

4️⃣ FTP (File Transfer protocol)

Port: 21

Used to transfer files between client and server.

5️⃣ SFTP (Secure File Transfer protocol)

port: 22(same as SSH)

Secure file transfer over SSH.

6️⃣ DNS (Domain name system)

Port: 53

Resolves domain names to IP addresses.

7️⃣ SMTP (Simple Mail Transfer protocol)

Port: 25, 587, 465

Used for sending emails.

8️⃣ IMAP (Internet Message Access Protocol)

Port: 143, 993

Retrieves emails from servers.

9️⃣ POP3 (Post Office Protocol)

Port: 110, 995

Another protocol for receiving emails.

🔟 NPT (Network Time Protocol)

Port: 123

Syncs time across systems.

📍Important Protocols and Ports Required for DevOps!

1. Git over SSH (Git Source Control)

Port: 22

Secure Git Operations Over SSH .

2. Jenkins

Port; 8080 (default)

CI/CD Automation Tool.

3. Docker Daemon

Port: 2375, 2376

For Managing Docker Containers Remotely.

4. Kubernetes API Server

Port: 6443

Manages Kubernetes clusters.

5. Prometheus

Port: 9090

Monitoring System for DevOps.

6. Grafana

Port: 3000

Visualization tool for monitoring Dashboards.

7. ELK Stack (Elasticsearch, Logstash, Kibana)

Elasticsearch: 9200, 9300

Logstash: 5044

Kibana: 5601

8. Ansible

protocol: SSH

Port: 22 (No additional port required).

9. Terraform Remote Execution

HTTPS: 443 for API communication with cloud providers.
