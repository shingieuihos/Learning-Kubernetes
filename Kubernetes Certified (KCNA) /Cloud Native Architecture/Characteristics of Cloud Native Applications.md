## Characteristics of Cloud Native Applications
Cloud Native Applications harness the power of the cloud to provide increased resilience, agility, operability, and observability. Let's dive a bit deeper into these characteristics.

![Software Development Timeline](https://mygitpicks.s3.af-south-1.amazonaws.com/Software+Development+Evolution+Timeline.png)

### Resiliency
Resilient applications are designed to withstand failures and continue to function or recover quickly. They typically make use of patterns such as redundancy, failover, and graceful degradation. Self-healing, where systems automatically detect and recover from failure, is a key aspect of resilient cloud-native applications. Kubernetes, for instance, has a built-in self-healing mechanism where it maintains a desired number of pod replicas and replaces failed instances.

### Agility
Agility in the context of cloud-native applications refers to the ability to quickly build, modify, and deploy applications. Agile practices such as microservices and continuous delivery pipelines, backed by automation, promote rapid iteration and responsiveness to change.

### Operability
Operability encompasses the ease of deploying, running, and managing applications. Cloud-native applications are designed to be easily monitored, configured, and maintained. They typically leverage automation and Infrastructure as Code (IaC) tools like Terraform to streamline operations and minimise toil.

### Observability
Observability is the ability to understand the internal state of your system based on the outputs it generates. It's a critical component in diagnosing issues and understanding how an application behaves in the wild. Logging, monitoring, and tracing (collectively known as the 'three pillars of observability') are vital practices to understand the state and performance of cloud-native applications.

It is important as part of your studies especially if you’re planning on taking the KCNA exam to remember these characteristics! A friendly anagram for this is “RAOO: Racoons are Often Observant”

### What Is Cloud Native Architecture?
Cloud native architecture concerns the design of applications or services that were made specifically to exist in the cloud, rather than in a more traditional on-premises infrastructure. A successful cloud native architecture needs to be easy to maintain and supported by a next-generation cloud, while also being cost efficient and self-healing. Compared to legacy systems, cloud native architectures have a greater level of flexibility, without having to rely on physical servers.

This is where microservices and serverless functions can play a large and important role. Microservices are the core of cloud native application architecture, and they have become a key tool for companies that are making the move to the cloud. Microservices arrange an application into multiple, independent services, each of which serves a specific function. Many software companies take advantage of microservices because they support DevOps, enable flexibility, and improve scalability, while also reducing costs. Cloud native microservices communicate with each other via APIs and use event-driven architecture, which serves to enhance the overall performance of each application.

### 1. Mission of the Cloud Native Computing Foundation.
The Foundation’s mission is to make cloud native computing ubiquitous. The CNCF Cloud Native Definition v1.0 says:

Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.

These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

The Cloud Native Computing Foundation seeks to drive adoption of this paradigm by fostering and sustaining an ecosystem of open source, vendor-neutral projects. We democratize state-of-the-art patterns to make these innovations accessible for everyone.
