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
  - [Define additional settings](#define-additional-settings)
  - [Configure virtual networks](#configure-virtual-networks)
  - [VPN gateways](#vpn-gateways)
  - [Policy-based VPNs](#policy-based-vpns)
  - [Route-based VPNs](#route-based-vpns)
  - [VPN gateway sizes](#vpn-gateway-sizes)
  - [Required Azure resources](#required-azure-resources)
  - [Required on-premises resources](#required-on-premises-resources)
  - [Active/standby](#activestandby)
  - [Active/active](#activeactive)
  - [ExpressRoute failover](#expressroute-failover)
  - [Zone-redundant gateways](#zone-redundant-gateways)
  - [Express Route](#express-route)
  - [Features and benefits of ExpressRoute](#features-and-benefits-of-expressroute)
  - [Layer 3 connectivity](#layer-3-connectivity)
  - [Built-in redundancy](#built-in-redundancy)
  - [Connectivity to Microsoft cloud services](#connectivity-to-microsoft-cloud-services)
  - [Dynamic routing](#dynamic-routing)
  - [ExpressRoute connectivity models](#expressroute-connectivity-models)
  - [Colocation at a cloud exchange](#colocation-at-a-cloud-exchange)
  - [Point-to-point Ethernet connection](#point-to-point-ethernet-connection)
  - [Any-to-any networks](#any-to-any-networks)
  - [Directly from ExpressRoute sites](#directly-from-expressroute-sites)
  - [Security considerations](#security-considerations)
  - [Disk storage fundamentals](#disk-storage-fundamentals)
  - [Azure Blob storage fundamentals](#azure-blob-storage-fundamentals)
  - [Azure Files fundamentals](#azure-files-fundamentals)
  - [Understand Blob access tiers](#understand-blob-access-tiers)
  - [Azure Cosmos DB](#azure-cosmos-db)
  - [Azure SQL Database](#azure-sql-database)
    - [Features](#features)
    - [Migration](#migration)
  - [Azure database for MySQL](#azure-database-for-mysql)
  - [Azure Database for PostgreSQL](#azure-database-for-postgresql)
    - [Single Server](#single-server)
    - [Hyperscale (Citus)](#hyperscale-citus)
  - [Azure SQL Managed Instance](#azure-sql-managed-instance)
    - [Features](#features-1)
    - [Migration](#migration-1)
  - [Azure Synapse Analytics](#azure-synapse-analytics)
  - [Azure HDInsight](#azure-hdinsight)
  - [Azure Databricks](#azure-databricks)
  - [Azure Data Lake Analytics](#azure-data-lake-analytics)
- [Part 3: Describe core solutions and management tools on Azure](#part-3-describe-core-solutions-and-management-tools-on-azure)
  - [Identify the product options](#identify-the-product-options)
  - [Azure IoT Hub](#azure-iot-hub)
  - [Azure IoT Central](#azure-iot-central)
  - [Azure Sphere](#azure-sphere)
  - [Analyze the decision criteria](#analyze-the-decision-criteria)
    - [Is it critical to ensure that the device is not compromised?](#is-it-critical-to-ensure-that-the-device-is-not-compromised)
    - [Do I need a dashboard for reporting and management?](#do-i-need-a-dashboard-for-reporting-and-management)
  - [Use IoT Hub](#use-iot-hub)
    - [Which service should you choose?](#which-service-should-you-choose)
    - [Why not use Azure IoT Central?](#why-not-use-azure-iot-central)
    - [Why not use Azure Sphere?](#why-not-use-azure-sphere)
  - [Azure product options](#azure-product-options)
    - [Azure Machine Learning](#azure-machine-learning)
  - [Azure Cognitive Services](#azure-cognitive-services)
  - [Azure Bot Service](#azure-bot-service)
  - [Are you building a virtual agent that interfaces with humans via natural language?](#are-you-building-a-virtual-agent-that-interfaces-with-humans-via-natural-language)
  - [Do you need a service that can understand the content and meaning of images, video, or audio, or that can translate text into a different language?](#do-you-need-a-service-that-can-understand-the-content-and-meaning-of-images-video-or-audio-or-that-can-translate-text-into-a-different-language)
  - [Do you need to predict user behavior or provide users with personalized recommendations in your app?](#do-you-need-to-predict-user-behavior-or-provide-users-with-personalized-recommendations-in-your-app)
  - [Will your app predict future outcomes based on private historical data?](#will-your-app-predict-future-outcomes-based-on-private-historical-data)
  - [Do you need to build a model by using your own data or perform a different task than those listed above?](#do-you-need-to-build-a-model-by-using-your-own-data-or-perform-a-different-task-than-those-listed-above)
    - [Do you need to perform an orchestration across well-known APIs?](#do-you-need-to-perform-an-orchestration-across-well-known-apis)
    - [Do you need to execute custom algorithms or perform specialized data parsing and data lookups?](#do-you-need-to-execute-custom-algorithms-or-perform-specialized-data-parsing-and-data-lookups)
    - [Do you have existing automated tasks written in an imperative programming language?](#do-you-have-existing-automated-tasks-written-in-an-imperative-programming-language)
    - [Do you prefer a visual (declarative) workflow or writing (imperative) code?](#do-you-prefer-a-visual-declarative-workflow-or-writing-imperative-code)
  - [Azure DevOps Services](#azure-devops-services)
  - [GitHub and GitHub Actions](#github-and-github-actions)
  - [Azure DevTest Labs](#azure-devtest-labs)
    - [Do you need to automate and manage test-lab creation?](#do-you-need-to-automate-and-manage-test-lab-creation)
    - [Are you building open-source software?](#are-you-building-open-source-software)
    - [Regarding source-code management and DevOps tools, what level of granularity do you need for permissions?](#regarding-source-code-management-and-devops-tools-what-level-of-granularity-do-you-need-for-permissions)
    - [Regarding source-code management and DevOps tools, how sophisticated does your project management and reporting need to be?](#regarding-source-code-management-and-devops-tools-how-sophisticated-does-your-project-management-and-reporting-need-to-be)
    - [Regarding source-code management and DevOps tools, how tightly do you need to integrate with third-party tools?](#regarding-source-code-management-and-devops-tools-how-tightly-do-you-need-to-integrate-with-third-party-tools)
  - [The Azure portal](#the-azure-portal)
  - [The Azure mobile app](#the-azure-mobile-app)
  - [Azure PowerShell](#azure-powershell)
  - [The Azure CLI](#the-azure-cli)
  - [ARM templates](#arm-templates)
    - [Do you need to perform one-off management, administrative, or reporting actions?](#do-you-need-to-perform-one-off-management-administrative-or-reporting-actions)
    - [Do you need a way to repeatedly set up one or more resources and ensure that all the dependencies are created in the proper order?](#do-you-need-a-way-to-repeatedly-set-up-one-or-more-resources-and-ensure-that-all-the-dependencies-are-created-in-the-proper-order)
    - [When you're scripting, do you come from a Windows administration or Linux administration background?](#when-youre-scripting-do-you-come-from-a-windows-administration-or-linux-administration-background)
  - [Identify your product options](#identify-your-product-options)
  - [Azure Advisor](#azure-advisor)
  - [Azure Monitor](#azure-monitor)
  - [Azure Service Health](#azure-service-health)
    - [Do you need to analyze how you're using Azure to reduce costs, improve resilience, or harden your security?](#do-you-need-to-analyze-how-youre-using-azure-to-reduce-costs-improve-resilience-or-harden-your-security)
    - [Do you want to monitor Azure services or your usage of Azure?](#do-you-want-to-monitor-azure-services-or-your-usage-of-azure)
    - [Do you want to measure custom events alongside other usage metrics?](#do-you-want-to-measure-custom-events-alongside-other-usage-metrics)
    - [Do you need to set up alerts for outages or when autoscaling is about to deploy new instances?](#do-you-need-to-set-up-alerts-for-outages-or-when-autoscaling-is-about-to-deploy-new-instances)
- [Part 4: Describe general security and network security features](#part-4-describe-general-security-and-network-security-features)
  - [What is Azure Security Center?](#what-is-azure-security-center)
  - [What is secure score?](#what-is-secure-score)

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

![create-virtual-network-286df13c](https://user-images.githubusercontent.com/87706066/162442998-041c05e4-0724-418e-b5b2-004b3bfdd70c.png)

![create-virtual-network-ip-address-286df13c](https://user-images.githubusercontent.com/87706066/162443021-6eb82c39-cae1-40a7-9445-9a610d62a854.png)

![create-virtual-network-security-286df13c](https://user-images.githubusercontent.com/87706066/162443356-f21c5cb9-5eac-4ee1-b921-4bb52b393b8c.png)

## Define additional settings

After you create a virtual network, you can then define further settings. These include:
- **Network security group** Network security groups have security rules that enable you to filter the type of network traffic that can flow in and out of virtual network subnets and network interfaces. You create the network security group separately. Then you associate it with each subnet in the virtual network.
- **Route table** Azure automatically creates a route table for each subnet within an Azure virtual network and adds system default routes to the table. You can add custom route tables to modify traffic between subnets and virtual networks.
- **Subnet Delegation** You can designate the subnet to be used by a dedicate service.

You can also amend the service endpoints and NAT gateway configuration.

![virtual-network-additional-settings-faff6cec](https://user-images.githubusercontent.com/87706066/162444328-a84a431b-dd2f-4116-9cbc-3c537482656c.png)

## Configure virtual networks
After you've created a virtual network, you can change any further settings on the Virtual network pane in the Azure portal. Alternatively, you can use PowerShell commands or commands in Cloud Shell to make changes.

![configure-virtual-network-9d0515c5](https://user-images.githubusercontent.com/87706066/162444372-aaae8a3a-693a-434b-9144-76a4d723f711.png)

---
## VPN gateways
A VPN gateway is a type of virtual network gateway. Azure VPN Gateway instances are deployed in a dedicated subnet of the virtual network and enable the following connectivity:
- Connect on-premises datacenters to virtual networks through a site-to-site connection.
- Connect individual devices to virtual networks through a point-to-site connection.
- Connect virtual networks to other virtual networks through a network-to-network connection.

## Policy-based VPNs
Policy-based VPN gateways specify statically the IP address of packets that should be encrypted through each tunnel. This type of device evaluates every data packet against those sets of IP addresses to choose the tunnel where that packet is going to be sent through.

Key features of policy-based VPN gateways in Azure include:
- Support for IKEv1 only.
- Use of static routing, where combinations of address prefixes from both networks control how traffic is encrypted and decrypted through the VPN tunnel. The source and destination of the tunneled networks are declared in the policy and don't need to be declared in routing tables.
- Policy-based VPNs must be used in specific scenarios that require them, such as for compatibility with legacy on-premises VPN devices.

## Route-based VPNs
If defining which IP addresses are behind each tunnel is too cumbersome, route-based gateways can be used. With route-based gateways, IPSec tunnels are modeled as a network interface or virtual tunnel interface. IP routing (either static routes or dynamic routing protocols) decides which one of these tunnel interfaces to use when sending each packet. Route-based VPNs are the preferred connection method for on-premises devices. They're more resilient to topology changes such as the creation of new subnets.

Use a route-based VPN gateway if you need any of the following types of connectivity:
- Connections between virtual networks
- Point-to-site connections
- Multisite connections
- Coexistence with an Azure ExpressRoute gateway

Key features of route-based VPN gateways in Azure include:
- Supports IKEv2
- Uses any-to-any (wildcard) traffic selectors
- Can use dynamic routing protocols, where routing/forwarding tables direct traffic to different IPSec tunnels In this case, the source and destination networks aren't statically defined as they are in policy-based VPNs or even in route-based VPNs with static routing. Instead, data packets are encrypted based on network routing tables that are created dynamically using routing protocols such as Border Gateway Protocol (BGP).

![PolicyBasedVPNRouteBasedVPN](https://user-images.githubusercontent.com/87706066/162446654-54ffa0a5-9fd3-48b7-bce2-d18972d226fc.png)

## VPN gateway sizes
![Screenshot 2022-04-08 143223](https://user-images.githubusercontent.com/87706066/162446503-a8feeb99-2733-473e-aa6b-279be64e7a03.png)


## Required Azure resources

The following diagram shows this combination of resources and their relationships to help you better understand what's required to deploy a VPN gateway.

## Required on-premises resources

To connect your datacenter to a VPN gateway, you'll need these on-premises resources:

- A VPN device that supports policy-based or route-based VPN gateways
- A public-facing (internet-routable) IPv4 address

## Active/standby
By default, VPN gateways are deployed as two instances in an active/standby configuration, even if you only see one VPN gateway resource in Azure. When planned maintenance or unplanned disruption affects the active instance, the standby instance automatically assumes responsibility for connections without any user intervention. Connections are interrupted during this failover, but they're typically restored within a few seconds for planned maintenance and within 90 seconds for unplanned disruptions.

![active-standby-c4a3c14d](https://user-images.githubusercontent.com/87706066/162449221-f4a33f2d-3490-4547-92e1-fada2d6d4feb.png)

## Active/active
With the introduction of support for the BGP routing protocol, you can also deploy VPN gateways in an active/active configuration. In this configuration, you assign a unique public IP address to each instance. You then create separate tunnels from the on-premises device to each IP address. You can extend the high availability by deploying an additional VPN device on-premises.

![dual-redundancy-d76100c9](https://user-images.githubusercontent.com/87706066/162449329-3dce70b1-f9af-46be-8a64-f526a9b75d52.png)

## ExpressRoute failover
Another high-availability option is to configure a VPN gateway as a secure failover path for ExpressRoute connections. But they aren't immune to physical problems that affect the cables delivering connectivity or outages that affect the complete ExpressRoute location. In this way, you can ensure there's always a connection to the virtual networks.

## Zone-redundant gateways
Deploying gateways in Azure availability zones physically and logically separates gateways within a region while protecting your on-premises network connectivity to Azure from zone-level failures. These gateways require different gateway SKUs and use Standard public IP addresses instead of Basic public IP addresses.

--- 

## Express Route
ExpressRoute lets you extend your on-premises networks into the Microsoft cloud over a private connection with the help of a connectivity provider. With ExpressRoute, you can establish connections to Microsoft cloud services, such as Microsoft Azure and Microsoft 365.

Connectivity can be from an any-to-any (IP VPN) network, a point-to-point Ethernet network, or a virtual cross-connection through a connectivity provider at a colocation facility. ExpressRoute connections don't go over the public Internet. This allows ExpressRoute connections to offer more reliability, faster speeds, consistent latencies, and higher security than typical connections over the Internet. For information on how to connect your network to Microsoft using ExpressRoute, see ExpressRoute connectivity models.

## Features and benefits of ExpressRoute
There are several benefits to using ExpressRoute as the connection service between Azure and on-premises networks.

- Layer 3 connectivity between your on-premises network and the Microsoft Cloud through a connectivity provider. Connectivity can be from an any-to-any (IPVPN) network, a point-to-point Ethernet connection, or through a virtual cross-connection via an Ethernet exchange.
- Connectivity to Microsoft cloud services across all regions in the geopolitical region.
- Global connectivity to Microsoft services across all regions with the ExpressRoute premium add-on.
- Dynamic routing between your network and Microsoft via BGP.
- Built-in redundancy in every peering location for higher reliability.
- Connection uptime SLA.
- QoS support for Skype for Business.

## Layer 3 connectivity
ExpressRoute provides Layer 3 (address-level) connectivity between your on-premises network and the Microsoft cloud through connectivity partners. These connections can be from a point-to-point or any-to-any network. They can also be virtual cross-connections through an exchange.

## Built-in redundancy
Each connectivity provider uses redundant devices to ensure that connections established with Microsoft are highly available. You can configure multiple circuits to complement this feature. All redundant connections are configured with Layer 3 connectivity to meet service-level agreements.

## Connectivity to Microsoft cloud services
ExpressRoute enables direct access to the following services in all regions:

- Microsoft Office 365
- Microsoft Dynamics 365
- Azure compute services, such as Azure Virtual Machines
- Azure cloud services, such as Azure Cosmos DB and Azure Storage
 
 Microsoft 365 was created to be accessed securely and reliably via the internet. For this reason, we recommend the use of ExpressRoute for specific scenarios. The "Learn more" section at the end of this module includes a link about using ExpressRoute to access Office 365.

 ## Dynamic routing
 ExpressRoute uses the Border Gateway Protocol (BGP) routing protocol. BGP is used to exchange routes between on-premises networks and resources running in Azure. This protocol enables dynamic routing between your on-premises network and services running in the Microsoft cloud.

 ## ExpressRoute connectivity models
 ExpressRoute supports three models that you can use to connect your on-premises network to the Microsoft cloud:

- CloudExchange colocation
- Point-to-point Ethernet connection
- Any-to-any connection
- Directly from ExpressRoute sites

![azure-connectivity-models-4deabab1](https://user-images.githubusercontent.com/87706066/162451246-0a0f2aac-e416-43d4-a4ca-6d82b7455efd.png)

## Colocation at a cloud exchange
Colocated providers can normally offer both Layer 2 and Layer 3 connections between your infrastructure, which might be located in the colocation facility, and the Microsoft cloud. For example, if your datacenter is colocated at a cloud exchange such as an ISP, you can request a virtual cross-connection to the Microsoft cloud.

## Point-to-point Ethernet connection
Point-to-point connections provide Layer 2 and Layer 3 connectivity between your on-premises site and Azure. You can connect your offices or datacenters to Azure by using the point-to-point links. For example, if you have an on-premises datacenter, you can use a point-to-point Ethernet link to connect to Microsoft.

## Any-to-any networks
With any-to-any connectivity, you can integrate your wide area network (WAN) with Azure by providing connections to your offices and datacenters. Azure integrates with your WAN connection to provide a connection like you would have between your datacenter and any branch offices.

With any-to-any connections, all WAN providers offer Layer 3 connectivity. For example, if you already use Multiprotocol Label Switching to connect to your branch offices or other sites in your organization, an ExpressRoute connection to Microsoft behaves like any other location on your private WAN.

## Directly from ExpressRoute sites
You can connect directly into the Microsoft's global network at a peering location strategically distributed across the world. ExpressRoute Direct provides dual 100 Gbps or 10-Gbps connectivity, which supports Active/Active connectivity at scale.

## Security considerations
With ExpressRoute, your data doesn't travel over the public internet, so it's not exposed to the potential risks associated with internet communications. ExpressRoute is a private connection from your on-premises infrastructure to your Azure infrastructure. Even if you have an ExpressRoute connection, DNS queries, certificate revocation list checking, and Azure Content Delivery Network requests are still sent over the public internet.

---

## Disk storage fundamentals
Disk Storage provides disks for Azure virtual machines. Disk Storage allows data to be persistently stored and accessed from an attached virtual hard disk.
You can use standard SSD and HDD disks for less critical workloads, premium SSD disks for mission-critical production applications, and ultra disks for data-intensive workloads such as SAP HANA, top tier databases, and transaction-heavy workloads.

The following illustration shows an Azure virtual machine that uses separate disks to store different data.


![azure-disks-7841e01e](https://user-images.githubusercontent.com/87706066/162454137-4063e8a2-b978-4dd3-bb3b-0c47ac8efe08.png)

## Azure Blob storage fundamentals
Azure Blob Storage is an object storage solution for the cloud. Azure Blob Storage is unstructured, meaning that there are no restrictions on the kinds of data it can hold. Blobs aren't limited to common file formats. A blob could contain gigabytes of binary data streamed from a scientific instrument, an encrypted message for another application, or data in a custom format for an app you're developing. 

Blob Storage is ideal for:
- Serving images or documents directly to a browser.
- Storing files for distributed access.
- Streaming video and audio.
- Storing data for backup and restore, disaster recovery, and archiving.
- Storing data for analysis by an on-premises or Azure-hosted service.
- Storing up to 8 TB of data for virtual machines.

You store blobs in containers, which helps you organize your blobs depending on your business needs.

The following diagram illustrates how you might use Azure accounts, containers, and blobs.

![account-container-blob-4da0ac47](https://user-images.githubusercontent.com/87706066/162454161-093ba263-73b9-4939-900c-31f9fdcc3286.png)

## Azure Files fundamentals
Azure Files offers fully managed file shares in the cloud that are accessible via the industry standard Server Message Block and Network File System protocols. Applications running in Azure virtual machines or cloud services can mount a file storage share to access file data, just as a desktop application would mount a typical SMB share. Typical usage scenarios would be to share files anywhere in the world, diagnostic data, or application data sharing.

Use Azure Files for the following situations:
- Many on-premises applications use file shares. Azure Files makes it easier to migrate those applications that share data to Azure. If you mount the Azure file share to the same drive letter that the on-premises application uses, the part of your application that accesses the file share should work with minimal changes, if any.
- Store configuration files on a file share and access them from multiple VMs. Tools and utilities used by multiple developers in a group can be stored on a file share, ensuring that everybody can find them, and that they use the same version.
- Write data to a file share, and process or analyze the data later. For example, you might want to do this with diagnostic logs, metrics, and crash dumps.

The following illustration shows Azure Files being used to share data between two geographical locations. Azure Files ensures the data is encrypted at rest, and the SMB protocol ensures the data is encrypted in transit.

![azure-files-5f942c3e](https://user-images.githubusercontent.com/87706066/162455177-2f434d64-8502-41df-94a1-9eb819e24ebd.png)


One thing that distinguishes Azure Files from files on a corporate file share is that you can access the files from anywhere in the world, by using a URL that points to the file. You can also use Shared Access Signature (SAS) tokens to allow access to a private asset for a specific amount of time.

Here's an example of a service SAS URI, showing the resource URI and the SAS token:
![sas-storage-uri-037308fa](https://user-images.githubusercontent.com/87706066/162455154-efc82184-21c7-4095-88e4-e69af21cb52b.png)

## Understand Blob access tiers

Azure Storage offers different access tiers for your blob storage, helping you store object data in the most cost-effective manner. The available access tiers include:

- **Hot access tier:** Optimized for storing data that is accessed frequently (for example, images for your website).
- **Cool access tier:** Optimized for data that is infrequently accessed and stored for at least 30 days (for example, invoices for your customers).
- **Archive access tier:** Appropriate for data that is rarely accessed and stored for at least 180 days, with flexible latency requirements (for example, long-term backups).

The following considerations apply to the different access tiers:

- Only the hot and cool access tiers can be set at the account level. The archive access tier isn't available at the account level.
- Hot, cool, and archive tiers can be set at the blob level, during upload or after upload.
- Data in the cool access tier can tolerate slightly lower availability, but still requires high durability, retrieval latency, and throughput characteristics similar to hot data. For cool data, a slightly lower availability service-level agreement (SLA) and higher access costs compared to hot data are acceptable trade-offs for lower storage costs.
- Archive storage stores data offline and offers the lowest storage costs, but also the highest costs to rehydrate and access data.

The following illustration demonstrates choosing between the hot and cool access tiers on a general purpose storage account.

![account-tier-42ec76d7](https://user-images.githubusercontent.com/87706066/162456217-4cf88be3-65ec-40ac-a220-c5c2ecce5c04.png)

---
## Azure Cosmos DB
A long-term plan might be to eventually move all disparate data to a common database service. You can take advantage of fast single-digit millisecond data access using one of many popular APIs. You can use this feature to store data updated and maintained by users around the world. Tailwind Traders developers maintain and update data.

The following illustration shows an example Azure Cosmos DB database used to store data for the Tailwind Traders Learning Portal website. 

![azure-cosmos-db-1c115364](https://user-images.githubusercontent.com/87706066/162703389-0cf40d41-ce83-4951-b070-afa4d7153392.png)


Azure Cosmos DB is flexible. At the lowest level, Azure Cosmos DB stores data in atom-record-sequence (ARS) format. The data is then abstracted and projected as an API, which you specify when you're creating your database. Your choices include SQL, MongoDB, Cassandra, Tables, and Gremlin. This level of flexibility means that as you migrate your company's databases to Azure Cosmos DB, your developers can stick with the API that they're the most comfortable with.

## Azure SQL Database
Azure SQL Database is a relational database based on the latest stable version of the Microsoft SQL Server database engine. SQL Database is a high-performance, reliable, fully managed, and secure database. You can use it to build data-driven applications and websites in the programming language of your choice, without needing to manage infrastructure.

### Features 
Azure SQL Database is a platform as a service database engine. It handles most of the database management functions, such as upgrades, patches, backups, and monitoring, without the need for user involvement. SQL Database is a fully managed service with high availability, backups and other routine maintenance operations built in. Microsoft handles all updates to SQL and operating system code. A SQL database can be the right choice for many modern cloud applications because it allows you to handle both relational and non-relational structured data, such as graphs, JSON, spatial and XML.
You can use advanced query processing features, such as high performance, in-memory technology, and intelligent query processing. 

### Migration
Tailwind Traders currently uses several on-premises servers running SQL Server, which provide data storage for your public-facing website . In addition, your on-premises servers running SQL Server also provide data storage for your internal-only training portal website. Tailwind Traders uses the website for new employee training materials .

![azure-sql-45a3584a](https://user-images.githubusercontent.com/87706066/162713025-51b1bf2c-e5e8-459c-8a2e-15bfff7d2dc7.png)

You can migrate your existing SQL Server databases with minimal downtime by using the Azure Database Migration Service. The Microsoft Data Migration Assistant can generate assessment reports that provide recommendations to help guide you through required changes prior to performing a migration. After you assess and resolve any remediation required, you're ready to begin the migration process. The Azure Database Migration Service performs all of the required steps. You just change the connection string in your apps.

## Azure database for MySQL

Azure Database for MySQL delivers:
- Built-in high availability with no additional cost.
- Predictable performance and inclusive, pay-as-you-go pricing.
- Scale as needed, within seconds.
- Ability to protect sensitive data at-rest and in-motion.
- Automatic backups.
- Enterprise-grade security and compliance.

Azure Database for MySQL offers several service tiers, and each tier provides different performance and capabilities to support lightweight to heavyweight database workloads. You can build your first app on a small database for a few dollars a month, and then adjust the scale to meet the needs of your solution. Dynamic scalability enables your database to transparently respond to rapidly changing resource requirements. You only pay for the resources you need, and only when you need them.

## Azure Database for PostgreSQL

Azure Database for PostgreSQL is a relational database service in the cloud. The server software is based on the community version of the open-source PostgreSQL database engine. Your familiarity with tools and expertise with PostgreSQL is applicable when you're using Azure Database for PostgreSQL.

Moreover, Azure Database for PostgreSQL delivers the following benefits:

- Built-in high availability compared to on-premises resources. There's no additional configuration, replication, or cost required to make sure your applications are always available.
- Simple and flexible pricing. You have predictable performance based on a selected pricing tier choice that includes software patching, automatic backups, monitoring, and security.
- Scale up or down as needed, within seconds. You can scale compute or storage independently as needed, to make sure you adapt your service to match usage.
- Adjustable automatic backups and point-in-time-restore for up to 35 days.
- Enterprise-grade security and compliance to protect sensitive data at-rest and in-motion. This security covers data encryption on disk and SSL encryption between client and server communication.

Azure Database for PostgreSQL is available in two deployment options: Single Server and Hyperscale (Citus).

### Single Server

The Single Server deployment option delivers:

- Built-in high availability with no additional cost (99.99 percent SLA).
- Predictable performance and inclusive, pay-as-you-go pricing.
- Vertical scale as needed, within seconds.
- Monitoring and alerting to assess your server.
- Enterprise-grade security and compliance.
- Ability to protect sensitive data at-rest and in-motion.
- Automatic backups and point-in-time-restore for up to 35 days.

You can build your first app on a small database for a few dollars a month, and then adjust the scale to meet the needs of your solution. Dynamic scalability enables your database to transparently respond to rapidly changing resource requirements.

### Hyperscale (Citus)
The Hyperscale (Citus) option horizontally scales queries across multiple machines by using sharding. Its query engine parallelizes incoming SQL queries across these servers for faster responses on large datasets. It serves applications that require greater scale and performance, generally workloads that are approaching, or already exceed, 100 GB of data.

The Hyperscale (Citus) deployment option supports multi-tenant applications, real-time operational analytics, and high throughput transactional workloads. Applications built for PostgreSQL can run distributed queries on Hyperscale (Citus) with standard connection libraries and minimal changes.

## Azure SQL Managed Instance

Azure SQL Managed Instance is a scalable cloud data service that provides the broadest SQL Server database engine compatibility with all the benefits of a fully managed platform as a service. Depending on your scenario, Azure SQL Managed Instance might offer more options for your database needs.

### Features
Like Azure SQL Database, Azure SQL Managed Instance is a platform as a service database engine, which means that your company will be able to take advantage of the best features of moving your data to the cloud in a fully-managed environment. In addition, you'll be able to rest assured that your data will always be there when you need it through built-in high availability features and a 99.99% uptime service level agreement . You'll also be able to protect your data with automated backups and a configurable backup retention period.

### Migration
Azure SQL Managed Instance makes it easy to migrate your on-premises data on SQL Server to the cloud using the Azure Database Migration Service (DMS) or native backup and restore. After you have discovered all of the features that your company uses, you need to assess which on-premises SQL Server instances you can migrate to Azure SQL Managed Instance to see if you have any blocking issues. Once you have resolved any issues, you can migrate your data, then cutover from your on-premises SQL Server to your Azure SQL Managed Instance by changing the connection string in your applications.

## Azure Synapse Analytics

Azure Synapse Analytics (formerly Azure SQL Data Warehouse) is a limitless analytics service that brings together enterprise data warehousing and big data analytics. You can query data on your terms by using either serverless or provisioned resources at scale. You have a unified experience to ingest, prepare, manage, and serve data for immediate business intelligence and machine learning needs.

## Azure HDInsight
Azure HDInsight is a fully managed, open-source analytics service for enterprises. It's a cloud service that makes it easier, faster, and more cost-effective to process massive amounts of data. You can run popular open-source frameworks and create cluster types such as Apache Spark, Apache Hadoop, Apache Kafka, Apache HBase, Apache Storm, and Machine Learning Services. HDInsight also supports a broad range of scenarios such as extraction, transformation, and loading (ETL), data warehousing, machine learning, and IoT.

## Azure Databricks
Azure Databricks helps you unlock insights from all your data and build artificial intelligence solutions. You can set up your Apache Spark environment in minutes, and then autoscale and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

## Azure Data Lake Analytics
Azure Data Lake Analytics is an on-demand analytics job service that simplifies big data. Instead of deploying, configuring, and tuning hardware, you write queries to transform your data and extract valuable insights. The analytics service can handle jobs of any scale instantly by setting the dial for how much power you need. You only pay for your job when it's running, making it more cost-effective.

---

# Part 3: Describe core solutions and management tools on Azure

## Identify the product options
IoT enables devices to gather and then relay information for data analysis. Smart devices are equipped with sensors that collect data. A few common sensors that measure attributes of the physical world include:

- Environmental sensors that capture temperature and humidity levels.
- Barcode, QR code, or optical character recognition (OCR) scanners.
- Geo-location and proximity sensors.
- Light, color, and infrared sensors.
- Sound and ultrasonic sensors.
- Motion and touch sensors.
- Accelerometer and tilt sensors.
- Smoke, gas, and alcohol sensors.
- Error sensors to detect when there's a problem with the device.
- Mechanical sensors that detect anomalies or deformations.
- Flow, level, and pressure sensors for measuring gasses and liquids.

By using Azure IoT services, devices that are equipped with these kinds of sensors and that can connect to the internet could send their sensor readings to a specific endpoint in Azure via a message. The message's data is then collected and aggregated, and it can be converted into reports and alerts. Alternately, all devices could be updated with new firmware to fix issues or add new functionality by sending software updates from Azure IoT services to each device.

## Azure IoT Hub
Azure IoT Hub is a managed service that's hosted in the cloud and that acts as a central message hub for bi-directional communication between your IoT application and the devices it manages. The IoT Hub service supports communications both from the device to the cloud and from the cloud to the device. From a cloud-to-device perspective, IoT Hub allows for command and control. That is, you can have either manual or automated remote control of connected devices, so you can instruct the device to open valves, set target temperatures, restart stuck devices, and so on.


## Azure IoT Central
Azure IoT Central builds on top of IoT Hub by adding a dashboard that allows you to connect, monitor, and manage your IoT devices. You can watch the overall performance across all devices in aggregate, and you can set up alerts that send notifications when a specific device needs maintenance. To help you get up and running quickly, IoT Central provides starter templates for common scenarios across various industries, such as retail, energy, healthcare, and government. You then customize the design starter templates directly in the UI by choosing from existing themes or creating your own custom theme, setting the logo, and so on.

## Azure Sphere
Azure Sphere creates an end-to-end, highly secure IoT solution for customers that encompasses everything from the hardware and operating system on the device to the secure method of sending messages from the device to the message hub. Azure Sphere has built-in communication and security features for internet-connected devices.

Azure Sphere comes in three parts:

- The first part is the Azure Sphere micro-controller unit (MCU), which is responsible for processing the operating system and signals from attached sensors. The following image displays the Seeed Azure Sphere MT3620 Development Kit MCU, one of several different starter kits that are available for prototyping and developing Azure Sphere applications.
- The second part is a customized Linux operating system (OS) that handles communication with the security service and can run the vendor's software.
- The third part is Azure Sphere Security Service, also known as AS3. Its job is to make sure that the device has not been maliciously compromised. When the device attempts to connect to Azure, it first must authenticate itself, per device, which it does by using certificate-based authentication. If it authenticates successfully, AS3 checks to ensure that the device hasn't been tampered with. After it has established a secure channel of communication, AS3 pushes any OS or approved customer-developed software updates to the device.

After the Azure Sphere system has validated the authenticity of the device and authenticated it, the device can interact with other Azure IoT services by sending telemetry and error information.

## Analyze the decision criteria

### Is it critical to ensure that the device is not compromised?

As we mentioned in the previous unit, Azure Sphere ensures a secure channel of communication between the device and Azure by controlling everything from the hardware to the operating system and the authentication process. This ensures that the integrity of the device is uncompromised. After a secure channel is established, messages can be received from the device securely, and messages or software updates can be sent to the device remotely.

### Do I need a dashboard for reporting and management?
Your next decision will be the level of services you require from your IoT solution. If you merely want to connect to your remote devices to receive telemetry and occasionally push updates, and you don't need any reporting capabilities, you might prefer to implement Azure IoT Hub by itself. However, if you want a pre-built customizable user interface with which you can view and control your devices remotely, you might prefer to start with IoT Central. The dashboard is based on starter templates for common industry and usage scenarios. You can use the dashboard that's generated by the starter template as is or customize it to suit your needs.


## Use IoT Hub
To build a strong brand reputation, devices send telemetry information to a centralized location where the data can be analyzed and maintenance can be scheduled. They will only submit their telemetry data for analysis and active maintenance. Since Tailwind Traders already has software to manage equipment maintenance requirements, the company wanted to integrate all functions into this existing system.

### Which service should you choose?
Let's apply the decision criteria from the previous unit. It might not warrant the extra expense or engineering resources that would be required to employ Azure Sphere. In this case, Azure IoT Central is not required. So, given the responses to the decision criteria, Azure IoT Hub is the best choice in this scenario.

### Why not use Azure IoT Central?
Azure IoT Central provides a dashboard that allows companies to manage IoT devices individually and an aggregate, view reports, and set up error notifications via a GUI. But, in this scenario, Tailwind Traders wants to integrate the telemetry it collects and other analysis functionality into an existing software application. Furthermore, the company's appliances will be collecting data via sensors only and don't need the ability to update settings or software remotely. Therefore, the company doesn't need Azure IoT Central.

### Why not use Azure Sphere?
Azure Sphere provides a complete solution for scenarios where security is critical. In this scenario, security is preferred but not critical. The appliances can't be updated with new software remotely. The sensors merely report usage data. As a result, Azure Sphere isn't necessary.

---

## Azure product options
At a high level, there are three primary product offerings from Microsoft, each of which is designed for a specific audience and use case. Each option provides a diverse set of tools, services, and programmatic APIs. In this module, we'll merely scratch the surface of the options' capabilities.

### Azure Machine Learning
Azure Machine Learning is a platform for making predictions. It consists of tools and services that allow you to connect to data to train and test models to find one that will most accurately predict a future result. After you've run experiments to test the model, you can deploy and use it in real time via a web API endpoint.

With Azure Machine Learning, you can:

- Create a process that defines how to obtain data, how to handle missing or bad data, how to split the data into either a training set or test set, and deliver the data to the training process.
- Train and evaluate predictive models by using tools and programming languages familiar to data scientists.
- Create pipelines that define where and when to run the compute-intensive experiments that are required to score the algorithms based on the training and test data.
- Deploy the best-performing algorithm as an API to an endpoint so it can be consumed in real time by other applications.

Choose Azure Machine Learning when your data scientists need complete control over the design and training of an algorithm using your own data. The following video discusses the basic steps required to set up a machine learning system.

## Azure Cognitive Services
Azure Cognitive Services provides prebuilt machine learning models that enable applications to see, hear, speak, understand, and even begin to reason. Use Azure Cognitive Services to solve general problems, such as analyzing text for emotional sentiment or analyzing images to recognize objects or faces. You don't need special machine learning or data science knowledge to use these services. Developers access Azure Cognitive Services via APIs and can easily include these features in just a few lines of code.

While Azure Machine Learning requires you to bring your own data and train models over that data, Azure Cognitive Services, for the most part, provides pretrained models so that you can bring in your live data to get predictions on.

Azure Cognitive Services can be divided into the following categories:

- Language services: Allow your apps to process natural language with prebuilt scripts, evaluate sentiment, and learn how to recognize what users want.
- Speech services: Convert speech into text and text into natural-sounding speech. Translate from one language to another and enable speaker verification and recognition.
- Vision services: Add recognition and identification capabilities when you're analyzing pictures, videos, and other visual content.
- Decision services: Add personalized recommendations for each user that automatically improve each time they're used, moderate content to monitor and remove offensive or risky content, and detect abnormalities in your time series data.

## Azure Bot Service
 Azure Bot Service is a bit different from Azure Machine Learning and Azure Cognitive Services in that it has a specific use case. Behind the scenes, the bot you build uses other Azure services, such as Azure Cognitive Services, to understand what their human counterparts are asking for. A bot interaction can be a quick question and answer, or it can be a sophisticated conversation that intelligently provides access to services.

## Are you building a virtual agent that interfaces with humans via natural language?

Use Azure Bot Service when you need to create a virtual agent to interact with humans by using natural language. Bot Service integrates knowledge sources, natural language processing, and form factors to allow interaction across different channels. Bot Service solutions usually rely on other AI services for such things as natural language understanding or even translation for localizing replies into a customer's preferred language.

## Do you need a service that can understand the content and meaning of images, video, or audio, or that can translate text into a different language?

Use Azure Cognitive Services when it comes to general purpose tasks, such as performing speech to text, integrating with search, or identifying the objects in an image. Azure Cognitive Services is general purpose, meaning that many different kinds of customers can benefit from the work that Microsoft has already done to train and test these models and offer them inexpensively at scale.

## Do you need to predict user behavior or provide users with personalized recommendations in your app?
The Azure Cognitive Services Personalizer service watches your users' actions within an application. You can use Personalizer to predict their behavior and provide relevant experiences as it identifies usage patterns. Here again, you could capture and store user behavior and create your own custom Azure Machine Learning solution to do these things, but this approach would require much effort and expense.

## Will your app predict future outcomes based on private historical data?

Choose Azure Machine Learning when you need to analyze data to predict future outcomes. For example, suppose you need to analyze years' worth of financial transactions to discover new patterns that could help you create new products and services for your company's clients and then offer those new services during routine customer service calls. When you're working with proprietary data, you'll likely need to build a more custom-tailored machine learning model.

## Do you need to build a model by using your own data or perform a different task than those listed above?

Use Azure Machine Learning for maximum flexibility. Data scientists and AI engineers can use the tools they're familiar with and the data you provide to develop deep learning and machine learning models that are tuned for your 
particular requirements.

---

### Do you need to perform an orchestration across well-known APIs?
As we noted previously, Azure Logic Apps was designed with orchestration in mind, from the web-based visual configurator to the pricing model. Logic Apps excels at connecting a large array of disparate services via their APIs to pass and process data through many steps in a workflow.
It's possible to create the same workflow by using Azure Functions, but it might take a considerable amount of time to research which APIs to call and how to call them.

### Do you need to execute custom algorithms or perform specialized data parsing and data lookups?
With Azure Functions, you can use the full expressiveness of a programming language in a compact form. This lets you concisely build complex algorithms, or data lookup and parsing operations. You would be responsible for maintaining the code, handling exceptions resiliently, and so on.

Although Azure Logic Apps can perform logic (loops, decisions, and so on), if you have a logic-intensive orchestration that requires a complex algorithm, implementing that algorithm might be more verbose and visually overwhelming.

### Do you have existing automated tasks written in an imperative programming language?

If you already have your orchestration or business logic expressed in C#, Java, Python, or another popular programming language, it might be easier to port your code into the body of an Azure Functions function app than to re-create it by using Azure Logic Apps.

### Do you prefer a visual (declarative) workflow or writing (imperative) code?

Ultimately, your choice comes down to whether you prefer to work in a declarative environment or an imperative environment. Developers who have expertise in an imperative programming language might prefer to think about automation and orchestration from an imperative mindset. IT professionals and business analysts might prefer to work in a more visual low-code/no-code (declarative) environment.

---
## Azure DevOps Services
Azure DevOps Services is a suite of services that address every stage of the software development lifecycle.

- Azure Repos is a centralized source-code repository where software development, DevOps engineering, and documentation professionals can publish their code for review and collaboration.
- Azure Boards is an agile project management suite that includes Kanban boards, reporting, and tracking ideas and work from high-level epics to work items and issues.
- Azure Pipelines is a CI/CD pipeline automation tool.
- Azure Artifacts is a repository for hosting artifacts, such as compiled source code, which can be fed into testing or deployment pipeline steps.
- Azure Test Plans is an automated test tool that can be used in a CI/CD pipeline to ensure quality before a software release.

## GitHub and GitHub Actions
GitHub is arguably the world's most popular code repository for open-source software. Git is a decentralized source-code management tool, and GitHub is a hosted version of Git that serves as the primary remote. GitHub builds on top of Git to provide related services for coordinating work, reporting and discussing issues, providing documentation, and more. It offers the following functionality:

- It's a shared source-code repository, including tools that enable developers to perform code reviews by adding comments and questions in a web view of the source code before it can be merged into the main code base.
- It facilitates project management, including Kanban boards.
- It supports issue reporting, discussion, and tracking.
- It features CI/CD pipeline automation tooling.
- It includes a wiki for collaborative documentation.
- It can be run from the cloud or on-premises

With such similarity between many GitHub and Azure DevOps features, you might wonder which product to choose for your organization. Although both Azure DevOps and GitHub allow public and private code repositories, GitHub has a long history with public repositories and is trusted by tens of thousands of open-source project owners. GitHub is a lighter-weight tool than Azure DevOps, with a focus on individual developers contributing to the open-source code. Azure DevOps, on the other hand, is more focused on enterprise development, with heavier project-management and planning tools, and finer-grained access control.

## Azure DevTest Labs
Azure DevTest Labs provides an automated means of managing the process of building, setting up, and tearing down virtual machines that contain builds of your software projects. Anything you can deploy in Azure via an ARM template can be provisioned through DevTest Labs. Provisioning pre-created lab environments with their required configurations and tools already installed is a huge time saver for quality assurance professionals and developers.
Azure DevTest Labs can set up everything automatically upon request. After the testing is complete, DevTest Labs can shut down and deprovision the VM, which saves money when it's not in use.

### Do you need to automate and manage test-lab creation?
If your aim is to automate the creation and management of a test lab environment, consider choosing Azure DevTest Labs. Among the three tools and services we've described, it's the only one that offers this functionality.

However, you can automate the provisioning of new labs as part of a toolchain by using Azure Pipelines or GitHub Actions.

### Are you building open-source software?
Although Azure DevOps can publish public code repositories, GitHub has long been the preferred host for open-source software. If you're building open-source software, you would likely choose GitHub if for no other reasons than its visibility and general acceptance by the open-source development community.

The remaining decision criteria are specific to choosing between either Azure DevOps or GitHub.

### Regarding source-code management and DevOps tools, what level of granularity do you need for permissions?

GitHub works on a simple model of read/write permissions to every feature. Meanwhile, Azure DevOps has a much more granular set of permissions that allow organizations to refine who is able to perform most operations across the entire toolset.

### Regarding source-code management and DevOps tools, how sophisticated does your project management and reporting need to be?

Although GitHub has work items, issues, and a Kanban board, project management and reporting is the area where Azure DevOps excels. Azure DevOps is highly customizable, which allows an administrator to add custom fields to capture metadata and other information alongside each work item. By contrast, the GitHub Issues feature uses tags as its primary means of helping a team categorize issues.

### Regarding source-code management and DevOps tools, how tightly do you need to integrate with third-party tools?

lthough we make no specific recommendations about third-party tools, it's important for you to understand your organization's existing investments in tools and services and to evaluate how these dependencies might affect your choice. It's likely that most vendors that create DevOps tools create hooks or APIs that can be used by both Azure Pipelines and GitHub Actions. Even so, it's probably worth the effort to validate that assumption.

--- 

## The Azure portal 
By using the Azure portal, a web-based user interface, you can access virtually every feature of Azure. The Azure portal provides a friendly, graphical UI to view all the services you're using, create new services, configure your services, and view reports. The Azure portal is how most users first experience Azure. But, as your Azure usage grows, you'll likely choose a more repeatable code-centric approach to managing your Azure resources.

## The Azure mobile app

The Azure mobile app provides iOS and Android access to your Azure resources when you're away from your computer. With it, you can:

- Monitor the health and status of your Azure resources.
- Check for alerts, quickly diagnose and fix issues, and restart a web app or virtual machine (VM).
- Run the Azure CLI or Azure PowerShell commands to manage your Azure resources.

## Azure PowerShell
Azure PowerShell is a shell with which developers and DevOps and IT professionals can execute commands called cmdlets (pronounced command-lets). These commands call the Azure Rest API to perform every possible management task in Azure. Cmdlets can be executed independently or combined into a script file and executed together to orchestrate:

- The routine setup, teardown, and maintenance of a single resource or multiple connected resources.
- The deployment of an entire infrastructure, which might contain dozens or hundreds of resources, from imperative code.

Capturing the commands in a script makes the process repeatable and automatable.

Azure PowerShell is available for Windows, Linux, and Mac, and you can access it in a web browser via Azure Cloud Shell.

Windows PowerShell has helped Windows-centric IT organizations automate many of their on-premises operations for years, and these organizations have built up a large catalog of custom scripts and cmdlets, as well as expertise.

## The Azure CLI
The Azure CLI command-line interface is an executable program with which a developer, DevOps professional, or IT professional can execute commands in Bash. The commands call the Azure Rest API to perform every possible management task in Azure. You can run the commands independently or combined into a script and executed together for the routine setup, teardown, and maintenance of a single resource or an entire environment.

In many respects, the Azure CLI is almost identical to Azure PowerShell in what you can do with it. Both run on Windows, Linux, and Mac, and can be accessed in a web browser via Cloud Shell. The primary difference is the syntax you use. If you're already proficient in PowerShell or Bash, you can use the tool you prefer.

## ARM templates
Although it's possible to write imperative code in Azure PowerShell or the Azure CLI to set up and tear down one Azure resource or orchestrate an infrastructure comprising hundreds of resources, there's a better way to implement this functionality.

By using Azure Resource Manager templates (ARM templates), you can describe the resources you want to use in a declarative JSON format. The benefit is that the entire ARM template is verified before any code is executed to ensure that the resources will be created and connected correctly. The template then orchestrates the creation of those resources in parallel. That is, if you need 50 instances of the same resource, all 50 instances are created at the same time.

Ultimately, the developer, DevOps professional, or IT professional needs only to define the desired state and configuration of each resource in the ARM template, and the template does the rest. Templates can even execute PowerShell and Bash scripts before or after the resource has been set up.

### Do you need to perform one-off management, administrative, or reporting actions?

By contrast to the Azure CLI and PowerShell, Azure Resource Manager templates define the infrastructure requirements in your application for repeatable deployments. Keep in mind that ARM templates can include both PowerShell and/or Azure CLI scripts, which will give you the ability to utilize scripts for tasks that may not be possible with the ARM template itself. The ability to combine Azure management tools gives flexibility in choosing the right tool for your particular need. The Azure portal can perform most, if not all, management and administrative actions.

If you're just learning Azure and/or need to set up and manage resources infrequently , it makes sense to take advantage of the visual presentation that the Azure portal offers. To quickly find the settings and information you want to work with, the Azure CLI or PowerShell will give you the most flexibility for repeatable tasks. The last management tool to discuss is the Azure mobile app, which you can access via an iOS or Android phone or tablet.

### Do you need a way to repeatedly set up one or more resources and ensure that all the dependencies are created in the proper order?

ARM templates define your application's infrastructure requirements for a repeatable deployment that is done in a consistent manner. A validation step ensures that all resources can be created in the proper order based on dependencies, in parallel, and idempotent.

By contrast, it's entirely possible to use either PowerShell or the Azure CLI to set up all the resources for a deployment. However, there's no validation step in these tools. If a script encounters an error, the dependency resources can't be rolled back easily, deployments happen serially, and only some operations are idempotent.

### When you're scripting, do you come from a Windows administration or Linux administration background?
If you or your cloud administrators come from a Windows administration background, it's likely you'll prefer PowerShell. If you or your cloud administrators come from a Linux administration background, it's likely you'll prefer the Azure CLI. In practice, either tool can be used to perform most one-off administration tasks.

---
## Identify your product options
Several basic questions or concerns face all companies that use the cloud.

- Are we using the cloud correctly? Can we squeeze more performance out of our cloud spend?
- Are we spending more than we need to?
- Do we have our systems properly secured?
- How resilient are our resources? If we experience a regional outage, could we fail over to another region?
- How can we diagnose and fix issues that occur intermittently?
- How can we quickly determine the cause of an outage?
- How can we learn about planned downtime?

Fortunately, by using a combination of monitoring solutions on Azure, you can:

- Gain answers, insights, and alerts to help ensure that you've optimized your cloud usage.
- Ascertain the root cause of unplanned issues.
- Prepare ahead of time for planned outages.

## Azure Advisor
Azure Advisor evaluates your Azure resources and makes recommendations to help improve reliability, security, and performance, achieve operational excellence, and reduce costs. Advisor is designed to help you save time on cloud optimization. The recommendation service includes suggested actions you can take right away, postpone, or dismiss.

The recommendations are available via the Azure portal and the API, and you can set up notifications to alert you to new recommendations.

When you're in the Azure portal, the Advisor dashboard displays personalized recommendations for all your subscriptions, and you can use filters to select recommendations for specific subscriptions, resource groups, or services. The recommendations are divided into five categories:

- Reliability: Used to ensure and improve the continuity of your business-critical applications.
- Security: Used to detect threats and vulnerabilities that might lead to security breaches.
- Performance: Used to improve the speed of your applications.
- Cost: Used to optimize and reduce your overall Azure spending.
- Operational Excellence: Used to help you achieve process and workflow efficiency, resource manageability, and deployment best practices.

## Azure Monitor
Azure Monitor is a platform for collecting, analyzing, visualizing, and potentially taking action based on the metric and logging data from your entire Azure and on-premises environment.

The following diagram illustrates just how comprehensive Azure Monitor is.

![2-identify-product-options-01](https://user-images.githubusercontent.com/87706066/162779811-21f9f3ed-eb1b-41df-9733-c22f33622892.png)

- On the left is a list of the sources of logging and metric data that can be collected at every layer in your application architecture, from application to operating system and network.

- In the center, you can see how the logging and metric data is stored in central repositories.

- On the right, the data is used in a number of ways. You can view real-time and historical performance across each layer of your architecture, or aggregated and detailed information. The data is displayed at different levels for different audiences. You can view high-level reports on the Azure Monitor Dashboard or create custom views by using Power BI and Kusto queries.

## Azure Service Health

Azure Service Health provides a personalized view of the health of the Azure services, regions, and resources you rely on. The status.azure.com website, which displays only major issues that broadly affect Azure customers, doesn't provide the full picture. But Azure Service Health displays both major and smaller, localized issues that affect you. Service issues are rare, but it's important to be prepared for the unexpected. You can set up alerts that help you triage outages and planned maintenance. After an outage, Service Health provides official incident reports, called root cause analyses (RCAs), which you can share with stakeholders.

Service Health helps you keep an eye on several event types:

- Service issues are problems in Azure, such as outages, that affect you right now. You can drill down to the affected services, regions, updates from your engineering teams, and find ways to share and track the latest information.

- Planned maintenance events can affect your availability. You can drill down to the affected services, regions, and details to show how an event will affect you and what you need to do. Most of these events occur without any impact to you and aren't shown here. In the rare case that a reboot is required, Service Health allows you to choose when to perform the maintenance to minimize the downtime.

- Health advisories are issues that require you to act to avoid service interruption, including service retirements and breaking changes. Health advisories are announced far in advance to allow you to plan.

### Do you need to analyze how you're using Azure to reduce costs, improve resilience, or harden your security?

Choose Azure Advisor when you're looking for an analysis of your deployed resources. Azure Advisor analyzes the configuration and usage of your resources and provides suggestions on how to optimize for reliability, security, performance, costs, and operations based on experts' best 
practices.

### Do you want to monitor Azure services or your usage of Azure?

If you want to keep tabs on Azure itself, especially the services and regions you depend on, you want to choose Azure Service Health. You can view the current status of the Azure services you rely on, upcoming planned outages, and services that will be sunset. You can set up alerts that help you stay on top of incidents and upcoming downtime without having to visit the dashboard regularly.

However, if you want to keep track of the performance or issues related to your specific VM or container instances, databases, your applications, and so on, you want to visit Azure Monitor and create reports and notifications to help you understand how your services are performing or diagnose issues related to your Azure usage.

### Do you want to measure custom events alongside other usage metrics?
Choose Azure Monitor when you want to measure custom events alongside other collected telemetry data. Custom events, such as those added in the source code of your software applications, could help identify and diagnose why your application is behaving a certain way.

### Do you need to set up alerts for outages or when autoscaling is about to deploy new instances?
Here again, you would use Azure Monitor to set up alerts for key events that are related to your specific resources.

--- 

# Part 4: Describe general security and network security features

## What is Azure Security Center?

Azure Security Center is a monitoring service that provides visibility of your security posture across all of your services, both on Azure and on-premises. The term security posture refers to cybersecurity policies and controls, as well as how well you can predict, prevent, and respond to security threats.

Security Center can:

- Monitor security settings across on-premises and cloud workloads.
- Automatically apply required security settings to new resources as they come online.
- Provide security recommendations that are based on your current configurations, resources, and networks.
- Continuously monitor your resources and perform automatic security assessments to identify potential vulnerabilities before those vulnerabilities can be exploited.
- Use machine learning to detect and block malware from being installed on your virtual machines (VMs) and other resources. You can also use adaptive application controls to define rules that list allowed applications to ensure that only applications you allow can run.
- Detect and analyze potential inbound attacks and investigate threats and any post-breach activity that might have occurred.
- Provide just-in-time access control for network ports. Doing so reduces your attack surface by ensuring that the network only allows traffic that you require at the time that you need it to.

## What is secure score?
Secure score is a measurement of an organization's security posture.

Secure score is based on security controls, or groups of related security recommendations. Your score is based on the percentage of security controls that you satisfy. The more security controls you satisfy, the higher the score you receive. Your score improves when you remediate all of the recommendations for a single resource within a control.

Here's an example from the Azure portal showing a score of 57 percent, or 34 out of 60 points

![2-single-secure-score-via-ui-602159ab](https://user-images.githubusercontent.com/87706066/163159251-2128d617-83a2-4b5e-9367-3db7f8c3551d.png)

Following the secure score recommendations can help protect your organization from threats. From a centralized dashboard in Azure Security Center, organizations can monitor and work on the security of their Azure resources like identities, data, apps, devices, and infrastructure.

Secure score helps you:

Report on the current state of your organization's security posture.
Improve your security posture by providing discoverability, visibility, guidance, and control.
Compare with benchmarks and establish key performance indicators (KPIs).
