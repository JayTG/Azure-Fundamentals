- [Part 1: Describe core Azure concepts](#part-1-describe-core-azure-concepts)
  - [What is cloud computing?](#what-is-cloud-computing)
  - [Why is cloud computing typically cheaper to use?](#why-is-cloud-computing-typically-cheaper-to-use)
  - [Why should I move to the cloud?](#why-should-i-move-to-the-cloud)
  - [What is Azure?](#what-is-azure)
  - [What does Azure offer?](#what-does-azure-offer)
  - [What can I do with Azure?](#what-can-i-do-with-azure)
  - [How does Azure work?](#how-does-azure-work)
  - [What is the Azure portal?](#what-is-the-azure-portal)
  - [What is Azure Marketplace?](#what-is-azure-marketplace)
  - [Azure services](#azure-services)
  - [Cloud model comparison](#cloud-model-comparison)
    - [Public cloud](#public-cloud)
    - [Private cloud](#private-cloud)
    - [Hybrid cloud](#hybrid-cloud)
  - [What are some cloud computing advantages?](#what-are-some-cloud-computing-advantages)
  - [Capital expenses vs. operating expenses](#capital-expenses-vs-operating-expenses)
  - [Cloud computing is a consumption-based model](#cloud-computing-is-a-consumption-based-model)
    - [What are cloud service models?](#what-are-cloud-service-models)
    - [IaaS](#iaas)
    - [PaaS](#paas)
    - [SaaS](#saas)
  - [What is serverless computing?](#what-is-serverless-computing)
  - [Azure Archcitecture](#azure-archcitecture)
  - [Azure Reigions](#azure-reigions)
  - [Why are regions important?](#why-are-regions-important)
  - [Special Azure regions](#special-azure-regions)
  - [Azure availability zones](#azure-availability-zones)
  - [What is an availability zone?](#what-is-an-availability-zone)
  - [Azure region pairs](#azure-region-pairs)
  - [What is a region pair?](#what-is-a-region-pair)
  - [Azure Resource Manager](#azure-resource-manager)
  - [The benefits of using Resource Manager](#the-benefits-of-using-resource-manager)
  - [Azure subscriptions](#azure-subscriptions)
  - [Azure management groups](#azure-management-groups)
  - [Hierarchy of management groups and subscriptions](#hierarchy-of-management-groups-and-subscriptions)
  - [Important facts about management groups](#important-facts-about-management-groups)
- [Part 2 Describe core Azure services](#part-2-describe-core-azure-services)
  - [Overview of Azure compute services](#overview-of-azure-compute-services)
  - [Examples of when to use VMs](#examples-of-when-to-use-vms)
  - [Scale VMs in Azure](#scale-vms-in-azure)
  - [What are virtual machine scale sets?](#what-are-virtual-machine-scale-sets)
  - [What is Azure Batch?](#what-is-azure-batch)
  - [Types of app services](#types-of-app-services)
    - [Web apps](#web-apps)
    - [API apps](#api-apps)
    - [WebJobs](#webjobs)
    - [Mobile apps](#mobile-apps)
  - [What are containers?](#what-are-containers)
  - [Manage containers](#manage-containers)
    - [Azure Container Instances](#azure-container-instances)
    - [Azure Kubernetes Service](#azure-kubernetes-service)
  - [Use containers in your solutions](#use-containers-in-your-solutions)
  - [Serverless computing](#serverless-computing)
  - [Serverless computing in Azure](#serverless-computing-in-azure)
  - [Azure Functions](#azure-functions)
  - [Azure Logic Apps](#azure-logic-apps)
  - [Functions vs. Logic Apps](#functions-vs-logic-apps)
  - [What is Azure Virtual Desktop?](#what-is-azure-virtual-desktop)
    - [Provide the best user experience](#provide-the-best-user-experience)
    - [Enhance security](#enhance-security)
  - [What are some key features of Azure Virtual Desktop?](#what-are-some-key-features-of-azure-virtual-desktop)
    - [Simplified management](#simplified-management)
    - [Performance management](#performance-management)
    - [Multi-session Windows 10 deployment](#multi-session-windows-10-deployment)
  - [How can you reduce costs with Azure Virtual Desktop?](#how-can-you-reduce-costs-with-azure-virtual-desktop)
    - [Bring your own licenses](#bring-your-own-licenses)
    - [Save on compute costs](#save-on-compute-costs)
  - [What is Azure virtual networking?](#what-is-azure-virtual-networking)
  - [Isolation and segmentation](#isolation-and-segmentation)
  - [Internet communications](#internet-communications)
  - [Communicate between Azure resources](#communicate-between-azure-resources)
  - [Communicate with on-premises resources](#communicate-with-on-premises-resources)
  - [Route network traffic](#route-network-traffic)
  - [Filter network traffic](#filter-network-traffic)
  - [Connect virtual networks](#connect-virtual-networks)
  - [Creating a virtual network example](#creating-a-virtual-network-example)

# Part 1: Describe core Azure concepts
  

## What is cloud computing?
It's the delivery of computing services over the internet, which is otherwise known as the cloud. These services include servers, storage, databases, networking, software, analytics, and intelligence. Cloud computing offers faster innovation, flexible resources, and economies of scale.

![38-3](https://user-images.githubusercontent.com/87706066/162168457-4450c033-8ae5-4774-b87a-a09e2af114c8.png)

## Why is cloud computing typically cheaper to use?
Cloud computing is the delivery of computing services over the internet by using a pay-as-you-go pricing model. You typically pay only for the cloud services you use, which helps you:

- Lower your operating costs.
- Run your infrastructure more efficiently.
- Scale as your business needs change.

To put it another way, cloud computing may be a way to lease compute power and capacity from somebody else's datacenter. You'll treat cloud assets like you'd assets in your own datacenter. When you're done utilizing them, you donate them back. You're charged as it were for what you use. Instead of keeping up CPUs and capacity in your datacenter, you lease them for the time that you simply require them.

The cloud supplier takes care of keeping up the fundamental framework for you. The cloud empowers you to rapidly unravel your hardest commerce challenges, and bring cutting-edge arrangements to your clients.#

## Why should I move to the cloud?
The cloud helps you move faster and innovate in ways that were once nearly impossible.

In our ever-changing digital world, two trends emerge:

- Teams deliver new features to their users at record speeds.
- Users expect an increasingly rich and immersive experience with their devices and with software.

To power your services and deliver innovative and novel user experiences more quickly, the cloud provides on-demand access to:

- A nearly limitless pool of raw compute, storage, and networking components
- Speech recognition and other cognitive services that help make your application stand out from the crowd.
- Analytics services that deliver telemetry data from your software and devices.

## What is Azure?
Azure is a continually expanding set of cloud services that help your organization meet your current and future business challenges. Azure gives you the freedom to build, manage, and deploy applications on a massive global network using your favorite tools and frameworks.

![10-reasons-why-choose-azure-for-your-enterprise](https://user-images.githubusercontent.com/87706066/162172047-9300ba7f-9318-4237-910d-9c34d21860f0.png)

## What does Azure offer?

- **Be ready for the future:** Continuous innovation from Microsoft supports your development today and your product visions for tomorrow.
- **Build on your terms:** You have choices. With a commitment to open source, and support for all languages and frameworks, you can build how you want and deploy where you want to.
- **Operate hybrid seamlessly:** On-premises, in the cloud, and at the edge--we'll meet you where you are. Integrate and manage your environments with tools and services designed for a hybrid cloud solution.
- **Trust your cloud:** Get security from the ground up, backed by a team of experts, and proactive compliance trusted by enterprises, governments, and startups.

## What can I do with Azure?
Azure provides more than 100 services that enable you to do everything from running your existing applications on virtual machines, to exploring new software paradigms, such as intelligent bots and mixed reality.  Many teams start exploring the cloud by moving their existing applications to virtual machines that run in Azure. 

## How does Azure work?
Azure is a public and private platform that helps users to build, deploy and manage their applications. A technology known as virtualization which seprates the coupling between a computer's hardware and operating system using a abstraction layer called a hypervisor. The hypervisor emulates all the functions of a computer in a virtual machine. It can run multiple virtual machines at the same time and they can run any compatiable OS such as Windows and Linux. Each server contains and hypervisor. A network switch provides connectivity to all those servers

## What is the Azure portal?

The Azure portal is a web-based, unified console that provides an alternative to command-line tools. With the Azure portal, you can manage your Azure subscription by using a graphical user interface. You can:

- Build, manage, and monitor everything from simple web apps to complex cloud deployments.
- Create custom dashboards for an organized view of resources.
- Configure accessibility options for an optimal experience.

The Azure portal is designed for resiliency and continuous availability. It maintains a presence in every Azure datacenter. This configuration makes the Azure portal resilient to individual datacenter failures and avoids network slowdowns by being close to users. The Azure portal updates continuously and requires no downtime for maintenance activities.

The Azure portal is designed for resiliency and continuous availability. It maintains a presence in every Azure datacenter. This configuration makes the Azure portal resilient to individual datacenter failures and avoids network slowdowns by being close to users. The Azure portal updates continuously and requires no downtime for maintenance activities.

## What is Azure Marketplace?
Azure Marketplace helps connect users with Microsoft partners, independent software vendors, and startups that are offering their solutions and services, which are optimized to run on Azure. Azure Marketplace customers can find, try, purchase, and provision applications and services from hundreds of leading service providers. All solutions and services are certified to run on Azure.

## Azure services
Here's a big-picture view of the available services and features in Azure.

![azure-services-6c41a736](https://user-images.githubusercontent.com/87706066/162206237-aca4aa9d-b71e-47f6-b89c-46f3ae81c3c3.png)

There are many different categories

- Compute
> Compute services are often one of the primary reasons why companies move to the Azure platform. Azure provides a range of options for hosting applications and services. Here are some examples of compute services in Azure.
- Networking
> Linking compute resources and providing access to applications is the key function of Azure networking. Networking functionality in Azure includes a range of options to connect the outside world to services and features in the global Azure datacenters.
- Storage
> Azure provides four main types of storage services. Azure Blob storage, Azure File storage, Azure Queue storage and Azure Table storage
- Mobile
> With Azure, developers can create mobile back-end services for iOS, Android, and Windows apps quickly and easily. Features that used to take time and increase project risks, such as adding corporate sign-in and then connecting to on-premises resources such as SAP, Oracle, SQL Server, and SharePoint, are now simple to include.
- Databases
> Azure provides multiple database services to store a wide variety of data types and volumes. And with global connectivity, this data is available to users instantly.
- Web
> Having a great web experience is critical in today's business world. Azure includes first-class support to build and host web apps and HTTP-based web services. The following Azure services are focused on web hosting.
- IoT
> People are able to access more information than ever before. Personal digital assistants led to smartphones, and now there are smart watches, smart thermostats, and even smart refrigerators. Personal computers used to be the norm. Now the internet allows any item that's online-capable to access valuable information. This ability for devices to garner and then relay information for data analysis is referred to as IoT.
- Big data
> Data comes in all formats and sizes. When we talk about big data, we're referring to large volumes of data. Data from weather systems, communications systems, genomic research, imaging platforms, and many other scenarios generate hundreds of gigabytes of data. This amount of data makes it hard to analyze and make decisions. It's often so large that traditional forms of processing and analysis are no longer appropriate.
- AI
> AI, in the context of cloud computing, is based around a broad range of services, the core of which is machine learning. Machine learning is a data science technique that allows computers to use existing data to forecast future behaviors, outcomes, and trends. Using machine learning, computers learn without being explicitly programmed.
- DevOps
> DevOps brings together people, processes, and technology by automating software delivery to provide continuous value to your users. With Azure DevOps, you can create build and release pipelines that provide continuous integration, delivery, and deployment for your applications. You can integrate repositories and application tests, perform application monitoring, and work with build artifacts. You can also work with and backlog items for tracking, automate infrastructure deployment, and integrate a range of third-party tools and services such as Jenkins and Chef. All of these functions and many more are closely integrated with Azure to allow for consistent, repeatable deployments for your applications to provide streamlined build and release processes.

--- 
## Cloud model comparison

### Public cloud
- No capital expenditures to scale up.
- Applications can be quickly provisioned and deprovisioned.
- Organizations pay only for what they use.

### Private cloud
- Hardware must be purchased for start-up and maintenance.
- Organizations have complete control over resources and security.
- Organizations are responsible for hardware maintenance and updates.

### Hybrid cloud
- Provides the most flexibility.
- Organizations determine where to run their applications.
- Organizations control security, compliance, or legal requirements.

## What are some cloud computing advantages?
- **High availability:** Depending on the service-level agreement (SLA) that you choose, your cloud-based apps can provide a continuous user experience with no apparent downtime, even when things go wrong.
- **Scalability:** Apps in the cloud can scale vertically and horizontally:  
> - Scale vertically to increase compute capacity by adding RAM or CPUs to a virtual machine. 
> - Scaling horizontally increases compute capacity by adding instances of resources, such as adding VMs to the configuration.
- **Elasticity:** You can configure cloud-based apps to take advantage of autoscaling, so your apps always have the resources they need.
- **Agility:** Deploy and configure cloud-based resources quickly as your app requirements change.

- **Geo-distribution:** You can deploy apps and data to regional datacenters around the globe, thereby ensuring that your customers always have the best performance in their region.
- **Disaster recovery:** By taking advantage of cloud-based backup services, data replication, and geo-distribution, you can deploy your apps with the confidence that comes from knowing that your data is safe in the event of disaster.

## Capital expenses vs. operating expenses
There are two different types of expenses that you should consider:

- **Capital Expenditure (CapEx)** is the up-front spending of money on physical infrastructure, and then deducting that up-front expense over time. The up-front cost from CapEx has a value that reduces over time.
- **Operational Expenditure (OpEx)** is spending money on services or products now, and being billed for them now. You can deduct this expense in the same year you spend it. There is no up-front cost, as you pay for a service or product as you use it.

## Cloud computing is a consumption-based model
Cloud service providers operate on a consumption-based model, which means that end users only pay for the resources that they use. Whatever they use is what they pay for.

A consumption-based model has many benefits, including:

- No upfront costs.
- No need to purchase and manage costly infrastructure that users might not use to its fullest.
- The ability to pay for additional resources when they are needed.
- The ability to stop paying for resources that are no longer needed.

### What are cloud service models?
If you've been around cloud computing for a while, you've probably seen the PaaS, IaaS, and SaaS acronyms for the different cloud service models. These models define the different levels of shared responsibility that a cloud provider and cloud tenant are responsible for.

The following illustration demonstrates the services that might run in each of the cloud service models.

![iaas-paas-saas-575a09e9](https://user-images.githubusercontent.com/87706066/162212397-4fd8a434-8502-4715-a327-726486ccf7e7.png)

### IaaS
IaaS is the most flexible category of cloud services. It aims to give you complete control over the hardware that runs your application. Instead of buying hardware, with IaaS, you rent it.
> Advantages: No CapEx, Agility, Consumption-based model, low skill requirement, Cloud benefits, Flexibility

### PaaS
PaaS provides the same benefits and considerations as IaaS, but there are some additional benefits to be aware of.
> Advantages: No CapEx, Agility, Consumption-based model, low skill requirement, Cloud benefits, Productivity
>
> Disadvantage:  Platform limitations

### SaaS
SaaS is software that's centrally hosted and managed for you and your users or customers. Usually one version of the application is used for all customers, and it's licensed through a monthly or annual subscription.

SaaS provides the same benefits as IaaS, but again there are some additional benefits to be aware of too.
> Advantages: No CapEx, Agility, Consumption-based model, low skill requirement, Cloud benefits, Flexibility
> 
> Disadvantage:  Software limitations

The following chart illustrates the various levels of responsibility between a cloud provider and a cloud tenant

![shared-responsibility-76efbc1e](https://user-images.githubusercontent.com/87706066/162212329-640b373a-eff2-4ec9-ad78-7bc98136ccd5.png)

## What is serverless computing?

Like PaaS, serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure. With serverless applications, the cloud service provider automatically provisions, scales, and manages the infrastructure required to run the code. Serverless architectures are highly scalable and event-driven, only using resources when a specific function or trigger occurs.

---
## Azure Archcitecture 

The following image shows the top-down hierarchy of organization for these levels.

![hierarchy-372fef74](https://user-images.githubusercontent.com/87706066/162213451-02caee3f-6253-443d-9367-394a0ddbf3f3.png)

- **Resources:** Resources are instances of services that you create, like virtual machines, storage, or SQL databases.
- **Resource groups:** Resources are combined into resource groups, which act as a logical container into which Azure resources like web apps, databases, and storage accounts are deployed and managed.
- **Subscriptions:** A subscription groups together user accounts and the resources that have been created by those user accounts. For each subscription, there are limits or quotas on the amount of resources that you can create and use. Organizations can use subscriptions to manage costs and the resources that are created by users, teams, or projects.
- **Management groups:** These groups help you manage access, policy, and compliance for multiple subscriptions. All subscriptions in a management group automatically inherit the conditions applied to the management group.

## Azure Reigions
A region is a geographical area on the planet that contains at least one but potentially multiple datacenters that are nearby and networked together with a low-latency network. Azure intelligently assigns and controls the resources within each region to ensure workloads are appropriately balanced.

When you deploy a resource in Azure, you'll often need to choose the region where you want your resource deployed.

## Why are regions important?

Azure has more global regions than any other cloud provider. These regions give you the flexibility to bring applications closer to your users no matter where they are. Global regions provide better scalability and redundancy. They also preserve data residency for your services.

## Special Azure regions

Azure has specialized regions that you might want to use when you build out your applications for compliance or legal purposes. A few examples include:

- **US DoD Central, US Gov Virginia, US Gov Iowa and more:** These regions are physical and logical network-isolated instances of Azure for U.S. government agencies and partners. These datacenters are operated by screened U.S. personnel and include additional compliance certifications.
- **China East, China North, and more:** These regions are available through a unique partnership between Microsoft and 21Vianet, whereby Microsoft doesn't directly maintain the datacenters.

Regions are what you use to identify the location for your resources. There are two other terms you should also be aware of: geographies and availability zones.

## Azure availability zones

You want to ensure your services and data are redundant so you can protect your information in case of failure. When you host your infrastructure, setting up your own redundancy requires that you create duplicate hardware environments. Azure can help make your app highly available through availability zones.

## What is an availability zone?
Availability zones are physically separate datacenters within an Azure region. Each availability zone is made up of one or more datacenters equipped with independent power, cooling, and networking. An availability zone is set up to be an isolation boundary. If one zone goes down, the other continues working. Availability zones are connected through high-speed, private fiber-optic networks.

## Azure region pairs
Availability zones are created by using one or more datacenters. There's a minimum of three zones within a single region. It's possible that a large disaster could cause an outage big enough to affect even two datacenters. That's why Azure also creates region pairs.

## What is a region pair?

Each Azure region is always paired with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away. This approach allows for the replication of resources (such as VM storage) across a geography that helps reduce the likelihood of interruptions because of events such as natural disasters, civil unrest, power outages, or physical network outages that affect both regions at once. If a region in a pair was affected by a natural disaster, for instance, services would automatically failover to the other region in its region pair.

Additional advantages of region pairs:
- If an extensive Azure outage occurs, one region out of every pair is prioritized to make sure at least one is restored as quickly as possible for applications hosted in that region pair.
- Planned Azure updates are rolled out to paired regions one region at a time to minimize downtime and risk of application outage.
- Data continues to reside within the same geography as its pair (except for Brazil South) for tax- and law-enforcement jurisdiction purposes.

## Azure Resource Manager
Azure Resource Manager is the deployment and management service for Azure. It provides a management layer that enables you to create, update, and delete resources in your Azure account. You use management features like access control, locks, and tags to secure and organize your resources after deployment.

When a user sends a request from any of the Azure tools, APIs, or SDKs, Resource Manager receives the request. It authenticates and authorizes the request. Resource Manager sends the request to the Azure service, which takes the requested action. Because all requests are handled through the same API, you see consistent results and capabilities in all the different tools.

## The benefits of using Resource Manager

With Resource Manager, you can:
- Manage your infrastructure through declarative templates rather than scripts. A Resource Manager template is a JSON file that defines what you want to deploy to Azure.
- Deploy, manage, and monitor all the resources for your solution as a group, rather than handling these resources individually.
- Redeploy your solution throughout the development life cycle and have confidence your resources are deployed in a consistent state.
- Define the dependencies between resources so they're deployed in the correct order.
- Apply access control to all services because RBAC is natively integrated into the management platform.
- Apply tags to resources to logically organize all the resources in your subscription.
- Clarify your organization's billing by viewing costs for a group of resources that share the same tag.

## Azure subscriptions
Using Azure requires an Azure subscription. A subscription provides you with authenticated and authorized access to Azure products and services. It also allows you to provision resources. An Azure subscription is a logical unit of Azure services that links to an Azure account, which is an identity in Azure Active Directory (Azure AD) or in a directory that Azure AD trusts.

An account can have one subscription or multiple subscriptions that have different billing models and to which you apply different access-management policies. You can use Azure subscriptions to define boundaries around Azure products, services, and resources. There are two types of subscription boundaries that you can use:
- **Billing boundary:** This subscription type determines how an Azure account is billed for using Azure. You can create multiple subscriptions for different types of billing requirements. Azure generates separate billing reports and invoices for each subscription so that you can organize and manage costs.
- **Access control boundary:** Azure applies access-management policies at the subscription level, and you can create separate subscriptions to reflect different organizational structures. An example is that within a business, you have different departments to which you apply distinct Azure subscription policies. This billing model allows you to manage and control access to the resources that users provision with specific subscriptions.

## Azure management groups
f your organization has many subscriptions, you might need a way to efficiently manage access, policies, and compliance for those subscriptions. Azure management groups provide a level of scope above subscriptions. You organize subscriptions into containers called management groups and apply your governance conditions to the management groups. All subscriptions within a management group automatically inherit the conditions applied to the management group. Management groups give you enterprise-grade management at a large scale no matter what type of subscriptions you might have. All subscriptions within a single management group must trust the same Azure AD tenant.

For example, you can apply policies to a management group that limits the regions available for VM creation. This policy would be applied to all management groups, subscriptions, and resources under that management group by only allowing VMs to be created in that region.

## Hierarchy of management groups and subscriptions
You can build a flexible structure of management groups and subscriptions to organize your resources into a hierarchy for unified policy and access management. The following diagram shows an example of creating a hierarchy for governance by using management groups.

![management-groups-and-subscriptions-bba71896](https://user-images.githubusercontent.com/87706066/162216232-b5ef568b-0fc0-4160-b374-047750f1ca8c.png)

## Important facts about management groups
- 10,000 management groups can be supported in a single directory.
- A management group tree can support up to six levels of depth. This limit doesn't include the root level or the subscription level.
- Each management group and subscription can support only one parent.
- Each management group can have many children.
- All subscriptions and management groups are within a single hierarchy in each directory.

---
# Part 2 Describe core Azure services

## Overview of Azure compute services
Azure supports a wide range of computing solutions for development and testing, running applications, and extending your datacenter. The service supports Linux, Windows Server, SQL Server, Oracle, IBM, and SAP. Azure also has many services that can run virtual machines (VMs). Each service provides different options depending on your requirements. Some of the most prominent services are:

- Azure Virtual Machines
- Azure Container Instances
- Azure App Service
- Azure Functions (or serverless computing)

## Examples of when to use VMs
- **During testing and development.** VMs provide a quick and easy way to create different OS and application configurations. Test and development personnel can then easily delete the VMs when they no longer need them.
- **When running applications in the cloud.** The ability to run certain applications in the public cloud as opposed to creating a traditional infrastructure to run them can provide substantial economic benefits. For example, an application might need to handle fluctuations in demand. Shutting down VMs when you don't need them or quickly starting them up to meet a sudden increase in demand means you pay only for the resources you use.
- **When extending your datacenter to the cloud.** An organization can extend the capabilities of its own on-premises network by creating a virtual network in Azure and adding VMs to that virtual network. Applications like SharePoint can then run on an Azure VM instead of running locally. This arrangement makes it easier or less expensive to deploy than in an on-premises environment.
- **During disaster recovery.** As with running certain types of applications in the cloud and extending an on-premises network to the cloud, you can get significant cost savings by using an IaaS-based approach to disaster recovery. If a primary datacenter fails, you can create VMs running on Azure to run your critical applications and then shut them down when the primary datacenter becomes operational again.

## Scale VMs in Azure
You can run single VMs for testing, development, or minor tasks. Or you can group VMs together to provide high availability, scalability, and redundancy. No matter what your uptime requirements are, Azure has several features that can meet them. These features include:

- Virtual machine scale sets
- Azure Batch

## What are virtual machine scale sets?
Virtual machine scale sets let you create and manage a group of identical, load-balanced VMs. Imagine you're running a website that enables scientists to upload astronomy images that need to be processed. If you duplicated the VM, you'd normally need to configure an additional service to route requests between multiple instances of the website. Virtual machine scale sets could do that work for you.

Scale sets allow you to centrally manage, configure, and update a large number of VMs in minutes to provide highly available applications. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule. With virtual machine scale sets, you can build large-scale services for areas such as compute, big data, and container workloads.

## What is Azure Batch?

Azure Batch enables large-scale parallel and high-performance computing (HPC) batch jobs with the ability to scale to tens, hundreds, or thousands of VMs.

When you're ready to run a job, Batch does the following:

- Starts a pool of compute VMs for you.
- Installs applications and staging data.
- Runs jobs with as many tasks as you have.
- Identifies failures.
- Requeues work.
- Scales down the pool as work completes.

## Types of app services
With App Service, you can host most common app service styles like:

- Web apps
- API apps
- WebJobs
- Mobile apps

App Service handles most of the infrastructure decisions you deal with in hosting web-accessible apps:

- Deployment and management are integrated into the platform.
- Endpoints can be secured.
- Sites can be scaled quickly to handle high traffic loads.
- The built-in load balancing and traffic manager provide high availability.

All of these app styles are hosted in the same infrastructure and share these benefits. This flexibility makes App Service the ideal choice to host web-oriented applications.

### Web apps
App Service includes full support for hosting web apps by using ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP, or Python. You can choose either Windows or Linux as the host operating system.

### API apps
Much like hosting a website, you can build REST-based web APIs by using your choice of language and framework. You get full Swagger support and the ability to package and publish your API in Azure Marketplace. The produced apps can be consumed from any HTTP- or HTTPS-based client.

### WebJobs
You can use the WebJobs feature to run a program (.exe, Java, PHP, Python, or Node.js) or script (.cmd, .bat, PowerShell, or Bash) in the same context as a web app, API app, or mobile app. They can be scheduled or run by a trigger. WebJobs are often used to run background tasks as part of your application logic.

### Mobile apps
Use the Mobile Apps feature of App Service to quickly build a back end for iOS and Android apps. With just a few clicks in the Azure portal, you can:

- Store mobile app data in a cloud-based SQL database.
- Authenticate customers against common social providers, such as MSA, Google, Twitter, and Facebook.
- Send push notifications.
- Execute custom back-end logic in C# or Node.js.

## What are containers?
Containers are a virtualization environment. Much like running multiple virtual machines on a single physical host, you can run multiple containers on a single physical or virtual host. Unlike virtual machines, you don't manage the operating system for a container. Virtual machines appear to be an instance of an operating system that you can connect to and manage, but containers are lightweight and designed to be created, scaled out, and stopped dynamically. While it's possible to create and deploy virtual machines as application demand increases, containers are designed to allow you to respond to changes on demand. With containers, you can quickly restart in case of a crash or hardware interruption. One of the most popular container engines is Docker, which is supported by Azure.

## Manage containers
Containers are managed through a container orchestrator, which can start, stop, and scale out application instances as needed. There are two ways to manage both Docker and Microsoft-based containers in Azure: Azure Container Instances and Azure Kubernetes Service (AKS).

### Azure Container Instances
Azure Container Instances offers the fastest and simplest way to run a container in Azure without having to manage any virtual machines or adopt any additional services. It's a platform as a service (PaaS) offering that allows you to upload your containers, which it runs for you.

### Azure Kubernetes Service
The task of automating, managing, and interacting with a large number of containers is known as orchestration. Azure Kubernetes Service is a complete orchestration service for containers with distributed architectures and large volumes of containers.

## Use containers in your solutions
Containers are often used to create solutions by using a microservice architecture. This architecture is where you break solutions into smaller, independent pieces. For example, you might split a website into a container hosting your front end, another hosting your back end, and a third for storage. This split allows you to separate portions of your app into logical sections that can be maintained, scaled, or updated independently.

Imagine your website back-end has reached capacity but the front end and storage aren't being stressed. You could:

- Scale the back end separately to improve performance.
- Decide to use a different storage service.
- Replace the storage container without affecting the rest of the application.

## Serverless computing 
Serverless computing is the abstraction of servers, infrastructure, and operating systems. With serverless computing, Azure takes care of managing the server infrastructure and the allocation and deallocation of resources based on demand. Infrastructure isn't your responsibility. Scaling and performance are handled automatically. You're billed only for the exact resources you use. There's no need to even reserve capacity.

Serverless computing includes the abstraction of servers, an event-driven scale, and micro-billing:

- **Abstraction of servers:** Serverless computing abstracts the servers you run on. You never explicitly reserve server instances. The platform manages that for you. Each function execution can run on a different compute instance. This execution context is transparent to the code. With serverless architecture, you deploy your code, which then runs with high availability.
- **Event-driven scale:** Serverless computing is an excellent fit for workloads that respond to incoming events. Events include triggers by:
   - Timers, for example, if a function needs to run every day at 10:00 AM UTC.
   - HTTP, for example, API and webhook scenarios.
   - Queues, for example, with order processing.

Instead of writing an entire application, the developer authors a function, which contains both code and metadata about its triggers and bindings. The platform automatically schedules the function to run and scales the number of compute instances based on the rate of incoming events. Triggers define how a function is invoked. Bindings provide a declarative way to connect to services from within the code.

- **Micro-billing:** Traditional computing bills for a block of time like paying a monthly or annual rate for website hosting. This method of billing is convenient but isn't always cost effective. Even if a customer's website gets only one hit a day, they still pay for a full day's worth of availability. With serverless computing, they pay only for the time their code runs. If no active function executions occur, they're not charged. For example, if the code runs once a day for two minutes, they're charged for one execution and two minutes of computing time.

## Serverless computing in Azure
Azure has two implementations of serverless compute:
- **Azure Functions:** Functions can execute code in almost any modern language.
- **Azure Logic Apps:** Logic apps are designed in a web-based designer and can execute logic triggered by Azure services without writing any code.

## Azure Functions
Using Azure Functions is ideal when you're only concerned with the code that runs your service, not the underlying platform or infrastructure. Functions are commonly used when you need to do work in response to an event, timer, or message from another Azure service, and that job can be completed quickly in a few seconds or less. Functions automatically scale with demand, so it's a solid choice when demand is volatile. With functions, Azure runs your code when triggered and automatically releases resources when the function is finished.

Functions can be stateless or stateful. Functions are an essential component of serverless computing. This flexibility allows you to manage scaling, run in virtual networks, and even completely isolate functions.

## Azure Logic Apps
Logic applications are similar to functions. Both allow you to trigger logic based on an event. Where functions execute code, logic apps execute workflows built from predefined logic blocks designed to automate business scenarios. Every Azure logic app workflow starts with a trigger that fires when a certain event occurs or when newly available data meets certain criteria.

Each time the trigger is triggered, the Logic Apps engine creates a logic app instance that runs the actions in the workflow. You create logic app workflows using a visual designer in the Azure portal or in Visual Studio. Workflows are persisted as a JSON file with a known workflow diagram. You pass the data through the workflow to do custom processing, most of the time without writing any code.

## Functions vs. Logic Apps
Functions and Logic Apps can both create complex orchestrations. An orchestration is a collection of functions or steps that are executed to accomplish a complex task.

- With Functions, you write code to complete each step.
- With Logic Apps, you use a GUI to define the actions and how they relate to one another.

![Screenshot 2022-04-08 110018](https://user-images.githubusercontent.com/87706066/162414583-a79d2338-ba36-41eb-88e4-14c467d02386.png)

## What is Azure Virtual Desktop?
Azure Virtual Desktop is a desktop and application virtualization service that runs on the cloud. It enables your users to use a cloud-hosted version of Windows from any location. Azure Virtual Desktop works across devices like Windows, Mac, iOS, Android, and Linux. It works with apps that you can use to access remote desktops and apps. You can also use most modern browsers to access Azure Virtual Desktop-hosted experiences.

### Provide the best user experience
Users have the freedom to connect to Azure Virtual Desktop with any device over the internet. They use an Azure Virtual Desktop client to connect to published Windows desktops and applications. This client can be a native application on the device or an Azure Virtual Desktop HTML5 web client. User sign-in to Azure Virtual Desktop is fast because user profiles are containerized using FSLogix.

During login, the user profile container is dynamically added to the computing environment. The user profile is immediately available and looks exactly like a local user profile in the system.

### Enhance security
Azure Virtual Desktop provides centralized security management for users' desktops with Azure Active Directory. With Azure Virtual Desktop, data and applications are isolated from the local hardware. Azure Virtual Desktop instead of running them on a remote server. The risk of confidential data being saved on personal devices is minimized.

This type of connection is more secure than the Remote Desktop Protocol.

## What are some key features of Azure Virtual Desktop?

### Simplified management
Azure Virtual Desktop is an Azure service, so it will be familiar to Azure administrators. You use Azure AD and RBACs to manage access to resources. With Azure, you also get tools to automate VM deployments, manage VM updates, and provide disaster recovery. As with other Azure services, Azure Virtual Desktop uses Azure Monitor for monitoring and alerts. This standardization lets admins identify issues through a single interface.

### Performance management
Azure Virtual Desktop gives you options to load balance users on your VM host pools. Host pools are collections of VMs with the same configuration assigned to multiple users. For the best performance, you can configure load balancing to occur as users sign in (breadth mode). With breadth mode, users are sequentially allocated across the host pool for your workload. To save costs, you can configure your VMs for depth mode load balancing where users are fully allocated on one VM before moving to the next. Azure Virtual Desktop provides tools to automatically provision additional VMs when incoming demand exceeds a specified threshold.

### Multi-session Windows 10 deployment
Azure Virtual Desktop lets you use Windows 10 Enterprise multi-session, the only Windows client-based operating system that enables multiple concurrent users on a single VM. Azure Virtual Desktop also provides a more consistent experience with broader application support compared to Windows Server-based operating systems.

## How can you reduce costs with Azure Virtual Desktop?

### Bring your own licenses
Azure Virtual Desktop is available to you at no additional cost if you have an eligible Microsoft 365 license. Just pay for the Azure resources used by Azure Virtual Desktop.

- Bring your eligible Windows or Microsoft 365 license to get Windows 10 Enterprise and Windows 7 Enterprise desktops and apps at no additional cost.
- If you're an eligible Microsoft Remote Desktop Services Client Access License customer, Windows Server Remote Desktop Services desktops and apps are available at no additional cost.

### Save on compute costs
Buy one-year or three-year Azure Reserved Virtual Machine Instances to save you up to 72 percent versus pay-as-you-go pricing. You can pay for a reservation up front or monthly. Reservations provide a billing discount and don't affect the runtime state of your resources.

---

## What is Azure virtual networking?
Azure virtual networks enable Azure resources, such as VMs, web apps, and databases, to communicate with each other, with users on the internet, and with your on-premises client computers. You can think of an Azure network as an extension of your on-premises network with resources that links other Azure resources.

Azure virtual networks provide the following key networking capabilities:
- Isolation and segmentation
- Internet communications
- Communicate between Azure resources
- Communicate with on-premises resources
- Route network traffic
- Filter network traffic
- Connect virtual networks

## Isolation and segmentation
Azure virtual network allows you to create multiple isolated virtual networks. When you set up a virtual network, you define a private IP address space by using either public or private IP address ranges. The public IP range only exists within the virtual network and isn't internet routable. You can divide that IP address space into subnets and allocate part of the defined address space to each named subnet.

For name resolution, you can use the name resolution service that's built in to Azure. You can also configure the virtual network to use an internal or an external DNS server.

## Internet communications
A VM in Azure can connect to the internet by default. You can enable incoming connections from the internet by assigning a public IP address to the VM or by putting the VM behind a public load balancer. For VM management, you can connect via the Azure CLI, Remote Desktop Protocol, or Secure Shell.

## Communicate between Azure resources
You'll want to enable Azure resources to communicate securely with each other. You can do that in one of two ways:
- **Virtual networks** Virtual networks can connect not only VMs but other Azure resources, such as the App Service Environment for Power Apps, Azure Kubernetes Service, and Azure virtual machine scale sets.
- **Service endpoints** You can use service endpoints to connect to other Azure resource types, such as Azure SQL databases and storage accounts. This approach enables you to link multiple Azure resources to virtual networks to improve security and provide optimal routing between resources.

## Communicate with on-premises resources
Azure virtual networks enable you to link resources together in your on-premises environment and within your Azure subscription. In effect, you can create a network that spans both your local and cloud environments. There are three mechanisms for you to achieve this connectivity:
- ** Point-to-site virtual private networks** The typical approach to a virtual private network (VPN) connection is from a computer outside your organization, back into your corporate network. In this case, the client computer initiates an encrypted VPN connection to connect that computer to the Azure virtual network.
- **Site-to-site virtual private networks** A site-to-site VPN links your on-premises VPN device or gateway to the Azure VPN gateway in a virtual network. In effect, the devices in Azure can appear as being on the local network. The connection is encrypted and works over the internet.
- **Azure ExpressRoute** For environments where you need greater bandwidth and even higher levels of security, Azure ExpressRoute is the best approach. ExpressRoute provides a dedicated private connectivity to Azure that doesn't travel over the internet. (You'll learn more about ExpressRoute in a separate unit later in this module.)

## Route network traffic
By default, Azure routes traffic between subnets on any connected virtual networks, on-premises networks, and the internet. You can also control routing and override those settings, as follows:
- **Route tables** A route table allows you to define rules about how traffic should be directed. You can create custom route tables that control how packets are routed between subnets.
- **Border Gateway Protocol** Border Gateway Protocol (BGP) works with Azure VPN gateways, Azure Route Server, or ExpressRoute to propagate on-premises BGP routes to Azure virtual networks.

## Filter network traffic
Azure virtual networks enable you to filter traffic between subnets by using the following approaches:
- **Network security groups** A network security group is an Azure resource that can contain multiple inbound and outbound security rules. You can define these rules to allow or block traffic, based on factors such as source and destination IP address, port, and protocol.
- **Network virtual appliances** A network virtual appliance is a specialized VM that can be compared to a hardened network appliance. A network virtual appliance carries out a particular network function, such as running a firewall or performing wide area network (WAN) optimization.

## Connect virtual networks
You can link virtual networks together by using virtual network peering. Peering enables resources in each virtual network to communicate with each other. These virtual networks can be in separate regions, which allows you to create a global interconnected network through Azure.

User-defined routes (UDR) are a significant update to Azure’s Virtual Networks that allows for greater control over network traffic flow. This method allows network administrators to control the routing tables between subnets within a VNet, as well as between VNets.

![local-or-remote-gateway-in-peered-virual-network-21106a38](https://user-images.githubusercontent.com/87706066/162442104-d74abb76-1233-42c2-9aa1-1704dc9a1bd3.png)

--- 
## Creating a virtual network example

