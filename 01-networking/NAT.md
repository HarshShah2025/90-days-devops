# 🗓️ Day 6: NAT, VPN & Load Balancer — DevOps Networking Essentials

Understanding these core networking concepts is essential for any DevOps engineer working with cloud infrastructure, containers, and secure deployments.

---

## 🌐 NAT (Network Address Translation)

✅ Allows multiple devices on a private network to share a single public IP  
✅ Hides internal IPs, improving security  
✅ Common in:
- Cloud VPCs
- Home routers
- Docker/Container networks

---

## 🔐 VPN (Virtual Private Network)

✅ Encrypts data between your device and the server  
✅ Creates a secure “tunnel” over public networks  
✅ Essential for:
- Remote access to cloud resources
- Managing hybrid or multi-cloud environments
- Secure internal communication

---

## ⚖ Load Balancer

✅ Distributes incoming traffic across multiple backend servers  
✅ Improves:
- Reliability
- Scalability
- Performance  

✅ Types:
- **Layer 4 (TCP/UDP)** – Operates at the Transport Layer
- **Layer 7 (HTTP/HTTPS)** – Operates at the Application Layer (e.g., path-based routing)

✅ Widely used in:
- Kubernetes (Service type: LoadBalancer, Ingress)
- AWS ELB/ALB
- Azure Load Balancer
- NGINX, HAProxy

---

## 💡 Why These Matter for DevOps?

✅ Helps design secure, resilient, and scalable infrastructure  
✅ Ensures high availability and performance for users  
✅ Critical for modern architectures like:
- Cloud-native apps  
- Microservices  
- CI/CD pipelines  
- Multi-region failover  

---

