Virtual Private Cloud (VPC)
This guide explores how virtual private clouds work and discusses the features and benefits of this emerging offering that provides public cloud tenants a private cloud-like experience.
What is a virtual private cloud (VPC)?
A VPC is a public cloud offering that lets an enterprise establish its own private cloud-like computing environment on shared public cloud infrastructure. A VPC gives an enterprise the ability to define and control a virtual network that is logically isolated from all other public cloud tenants, creating a private, secure place on the public cloud.

Imagine that a cloud provider’s infrastructure is a residential apartment building with multiple families living inside. Being a public cloud tenant is akin to sharing an apartment with a few roommates. In contrast, having a VPC is like having your own private condominium—no one else has the key, and no one can enter the space without your permission.

A VPC’s logical isolation is implemented using virtual network functions and security features that give an enterprise customer granular control over which IP addresses or applications can access particular resources. It is analogous to the “friends-only” or “public/private” controls on social media accounts used to restrict who can or can’t see your otherwise public posts.

Discover how IBM can help you on your VPC journey.

Features
VPCs are a “best of both worlds” approach to cloud computing. They give customers many of the advantages of private clouds, while leveraging public cloud resources and savings. The following are some key features of the VPC model:

Agility: Control the size of your virtual network and deploy cloud resources whenever your business needs them. You can scale these resources dynamically and in real-time.
Availability: Redundant resources and highly fault-tolerant availability zone architectures mean your applications and workloads are highly available.
Security: Because the VPC is a logically isolated network, your data and applications won’t share space or mix with those of the cloud provider’s other customers. You have full control over how resources and workloads are accessed, and by whom.
Affordability: VPC customers can take advantage of the public cloud’s cost-effectiveness, such as saving on hardware costs, labor times, and other resources.
Benefits
Each VPC’s main features readily translate into a benefit to help your business achieve agility, increased innovation, and faster growth.

Flexible business growth: Because cloud infrastructure resources—including virtual servers, storage, and networking—can be deployed dynamically, VPC customers can easily adapt to changes in business needs.
Satisfied customers: In today’s “always-on” digital business environments, customers expect uptime ratios of nearly 100%. The high availability of VPC environments enables reliable online experiences that build customer loyalty and increase trust in your brand.
Reduced risk across the entire data lifecycle: VPCs enjoy high levels of security at the instance or subnet level, or both. This gives you peace of mind and further increases the trust of your customers.
More resources to channel toward business innovation: With reduced costs and fewer demands on your internal IT team, you can focus your efforts on achieving key business goals and exercising core competencies.
Architecture
In a VPC, you can deploy cloud resources into your own isolated virtual network. These cloud resources—also known as logical instances—fall into three categories.

Compute: Virtual server instances (VSIs, also known as virtual servers) are presented to the user as virtual CPUs (vCPUs) with a predetermined amount of computing power, memory, etc.
Storage: VPC customers are typically allocated a certain block storage quota per account, with the ability to purchase more. It is akin to purchasing additional hard drive space. Recommendations for storage are based on the nature of your workload.
Networking: You can deploy virtual versions of various networking functions into your virtual private cloud account to enable or restrict access to its resources. These include public gateways, which are deployed so that all or some areas of your VPC environment can be made available on the public-facing Internet; load balancers, which distribute traffic across multiple VSIs to optimize availability and performance;  and routers, which direct traffic and enable communication between network segments. Direct or dedicated links enable rapid and secure communications between your on-premises enterprise IT environment or your private cloud and your VPC resources on public cloud.
Three-tier architecture in a VPC
The majority of today’s applications are designed with a three-tier architecture comprised of the following interconnected tiers:

The web or presentation tier, which takes requests from web browsers and presents information created by, or stored within, the other layers to end users.
The application tier, which houses the business logic and is where most processing takes place.
The database tier, comprised of database servers that store the data processed in the application tier.
To create a three-tier application architecture on a VPC, you assign each tier its own subnet, which will give it its own IP address range. Each layer is automatically assigned its own unique ACL.

For a more detailed explanation of how to create this architecture in a VPC and deploy applications to it, see the blog post “Virtual Private Cloud: The Tech and the Test.”

Security
VPCs achieve high levels of security by creating virtualized replicas of the security features used to control access to resources housed in traditional data centers. These security features enable customers to define virtual networks in logically isolated parts of the public cloud and control which IP addresses have access to which resources.

Two types of network access controls comprise the layers of VPC security:

Access control lists (ACLs): An ACL is a list of rules that limit who can access a particular subnet within your VPC. A subnet is a portion or subdivision of your VPC; the ACL defines the set of IP addresses or applications granted access to it.
Security group: With a security group, you can create groups of resources (which may be situated in more than one subnet) and assign uniform access rules to them. For example, if you have three applications in three different subnets, and you want them all to be public Internet-facing, you can place them in the same security group. Security groups act like virtual firewalls, controlling the flow of traffic to your virtual servers, no matter which subnet they are in.
VPC vs. …
VPC vs. virtual private network (VPN)
A virtual private network (VPN) makes a connection to the public Internet as secure as a connection to a private network by creating an encrypted tunnel through which the information travels. You can deploy a VPN-as-a-Service (VPNaaS) on your VPC to establish a secure site-to-site communication channel between your VPC and your on-premises environment or other location. Using a VPN, you can connect subnets in multiple VPCs so that they function as if they were on a single network.

VPC vs. private cloud
Private cloud and virtual private cloud are sometimes—and mistakenly—used interchangeably.  In fact, a virtual private cloud is actually a public cloud offering. A private cloud is a single-tenant cloud environment owned, operated, and managed by the enterprise, and hosted most commonly on-premises or in a dedicated space or facility. By contrast, a VPC is hosted on multi-tenant architecture, but each customer’s data and workloads are logically separate from those of all other tenants. The cloud provider is responsible for ensuring this logical isolation.

VPC vs. public cloud
A virtual private cloud is a single-tenant concept that gives you the opportunity to create a private space within the public cloud’s architecture. A VPC offers greater security than traditional multi-tenant public cloud offerings but still lets customers take advantage of the high availability, flexibility, and cost-effectiveness of the public cloud. In some cases, there may be different ways of how you scale a VPC and a public cloud account. For instance, additional storage volumes may only be available in blocks of a certain size for VPCs. Not all public cloud features are supported in all VPC offerings.

VPC FAQ
For answers to some of the most commonly asked questions about virtual private clouds, see "FAQs for VPC."

Pricing
The various cloud providers may offer different pricing models in their VPC offerings. It is common for individual VPC resources—such as load balancers, VSIs, or storage—to be priced separately. It is also common for data transfer charges to be applied based on volume, but there are some cloud providers do not charge for data transfers over private networks.

To find the VPC offering whose pricing model works best for your business needs, it is vital to consider the requirements of the applications you are planning to deploy. Are they compute-intensive? Will they require large amounts of memory and CPU? Or are they more balanced in terms of their CPU, storage, and memory requirements? Answering these questions accurately helps you to predict your usage needs, which in turn allows you to estimate the potential costs when comparing options.

VPC and IBM Cloud
IBM Cloud® Virtual Private Cloud (VPC) is among the latest IBM Cloud infrastructure offerings. Now available across several multi-zone regions, IBM Cloud VPC is designed from the ground up for cloud native workloads, with IBM experience in building and managing cloud architectures as its foundation.

IBM Cloud VPC features a new REST-based API to ease integration with your existing applications and toolsets, multiple connectivity options (including IBM Cloud Direct Link), and full integration with all core IBM Cloud platform capabilities
