Task 1: Secure Running Environment?

It is important to understand the differences and security capabilities of the concepts listed below. Choose two out of the four concepts and write a short explanation of them and their respective security capabilities and incapabilities.

Focus on giving a good overview of the security limits for the concepts.

TPM
Enclave
Container
Virtualization
Max 300 words excluding sources.

- A TPM is a security chip that resides on a PC's motherboard or within its processor, providing security functionalities to store sensitive information. The TPM module handles data encryption, managing and generating it.

Here are its capabilities: The TPM allows cryptographic keys to be stored in isolation from the rest of the system, thus reducing the risk of key theft. It also the integrity of software components during startup, checking that the system has not been compromised. it strengthens users authentication.

But it also has uncapabilities. Since it is physical hardware, its security depends on its material integrity. It cannot protect against all forms of post-boot attacks


- Containers represent a type of operating system virtualization. They can be utilized to run anything from small services to larger applications, with all necessary executables contained inside. While containers share the host OS kernel, they maintain logical separation from one another.

In terms of security : 
Containers can minimize the impact of vulnerabilities within an application as they are isolated in their own namespace. 
However, since all containers share the same kernel as the host OS, a security flaw could potentially compromise all active containers. Additionally, if a container has "privileged access" to the host, it could gain control over the entire system. Compared to virtual machines, the isolation provided by containers is less robust than that of a full virtual machine environment.

Sources : 
- https://www.intel.fr/content/www/fr/fr/business/enterprise-computers/resources/trusted-platform-module.html#:~:text=Un%20TPM%20est%20une%20puce,prendre%20en%20charge%20TPM%202.0.
- https://fr.wikipedia.org/wiki/Trusted_Platform_Module
- https://www.ionos.fr/digitalguide/serveur/configuration/trusted-platform-module/

- https://azure.microsoft.com/fr-fr/resources/cloud-computing-dictionary/what-is-a-container
- https://www.netapp.com/fr/devops-solutions/what-are-containers/
