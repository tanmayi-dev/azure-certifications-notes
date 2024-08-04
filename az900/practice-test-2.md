# Practice Test 2

### 1 . In which of the following scenarios, would an IaaS deployment make the most sense?

- [ ] For finance and expense tracking
- [x] For a lift-and-shift migration
- [ ] For analytics or business intelligence
- [ ] For setting a development framework


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  From the official docs:
                  <strong>Infrastructure as a service (IaaS)</strong> is the
                  most flexible category of cloud services, as it provides you
                  the maximum amount of control for your cloud resources. In an
                  IaaS model, the cloud provider is responsible for maintaining
                  the hardware, network connectivity (to the internet), and
                  physical security. You’re responsible for everything else:
                  operating system installation, configuration, and maintenance;
                  network configuration; database and storage configuration; and
                  so on. With IaaS, you’re essentially renting the hardware in a
                  cloud datacenter, but what you do with that hardware is up to
                  you.
                </p>
                <p>
                  Some common scenarios where IaaS might make sense include:
                </p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      Lift-and-shift migration: You’re standing up cloud
                      resources similar to your on-prem datacenter, and then
                      simply moving the things running on-prem to running on the
                      IaaS infrastructure.
                    </p>
                  </li>
                  <li>
                    <p>
                      Testing and development: You have established
                      configurations for development and test environments that
                      you need to rapidly replicate. You can stand up or shut
                      down the different environments rapidly with an IaaS
                      structure, while maintaining complete control.
                    </p>
                  </li>
                </ul>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-cloud-service-types/2-describe-infrastructure-service"
                    >https://learn.microsoft.com/en-us/training/modules/describe-cloud-service-types/2-describe-infrastructure-service</a
                  >
                </p>
              </div>
</details>

---

### 2 . Your manager has asked you to recommend an Azure Service that can be used to securely manage and store certificates for your teams services. Which of the following would you recommend?

- [ ] Azure Bastion
- [x] Azure Key Vault
- [ ] Azure Active Directory
- [ ] Azure Confidential Ledger


<details>
  <summary>Explanation</summary>
  <br/>
                <div>
                <p>
                  <strong>Secure key management</strong> is essential to protect
                  data in the cloud . <strong>Azure Key Vault </strong>encrypts
                  keys and small secrets like passwords that use keys stored in
                  hardware security modules (HSMs).
                </p>
                <p>
                  For more assurance, it is possible to import or generate keys
                  in HSMs, and Microsoft processes your keys in FIPS 140-2 Level
                  2 validated HSMs (hardware and firmware). With Key Vault,
                  <strong>Microsoft doesn’t see or extract your keys</strong>.
                </p>
                <p>
                  You can monitor and audit your key use with Azure logging—pipe
                  logs into Azure HDInsight or your security information and
                  event management (SIEM) solution for more analysis and threat
                  detection.
                </p>
                <p><br /></p>
                <p>
                  <strong
                    >All of the control, none of the work - the motto</strong
                  >
                </p>
                <p>
                  By using Key Vault, you don’t need to provision, configure,
                  patch, and maintain HSMs and key management software.
                  Provision new vaults and keys (or import keys from your own
                  HSMs) in minutes and centrally manage keys, secrets, and
                  policies. You keep control over your keys—simply grant
                  permission for your own and partner applications to use them
                  as needed. Applications never have direct access to keys.
                  Developers manage keys used for Dev/Test and seamlessly
                  migrate to production the keys that are managed by security
                  operations.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference :&nbsp;</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/services/key-vault/"
                    >https://azure.microsoft.com/en-us/services/key-vault/</a
                  >
                </p>
              </div>
</details>

---

### 3 . The Azure ________ service allows you to create and manage private networks in the cloud and connect them to on-premises networks using a VPN gateway.

- [x] Azure Virtual Network
- [ ] Azure DNS
- [ ] Azure Traffic Manager
- [ ] Azure Security Center


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  The correct answer is <strong>Azure Virtual Network</strong>.
                  The Azure Virtual Network service allows you to create and
                  manage private networks in the cloud and connect them to
                  on-premises networks using a VPN gateway.
                </p>
                <p>
                  Azure Virtual Network is a networking service that allows you
                  to create and manage virtual networks in the cloud, and
                  connect them securely to your on-premises infrastructure. With
                  Azure Virtual Network, you can create subnets, assign IP
                  addresses, and control traffic flow between virtual machines
                  and other resources.
                </p>
                <p>
                  The VPN gateway in Azure Virtual Network provides a secure,
                  encrypted connection between your virtual network in Azure and
                  your on-premises network. This allows you to extend your
                  on-premises infrastructure to the cloud, and access resources
                  in Azure as if they were located on your local network.
                </p>
                <p><br /></p>
                <p><strong>Other Options - </strong></p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Azure DNS: </strong>While Azure DNS provides a
                      scalable and reliable domain name system (DNS) service
                      that can be used to resolve domain names to IP addresses,
                      it is not directly related to creating and managing
                      private networks or connecting them to on-premises
                      networks using a VPN gateway.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Azure Traffic Manager:</strong> While Azure
                      Traffic Manager is a global DNS-based traffic load
                      balancer that can be used to distribute traffic across
                      multiple endpoints, it is not directly related to creating
                      and managing private networks or connecting them to
                      on-premises networks using a VPN gateway.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Azure Security Center: </strong>While Azure
                      Security Center is a unified security management and
                      monitoring service that provides threat protection for
                      cloud workloads, it is not directly related to creating
                      and managing private networks or connecting them to
                      on-premises networks using a VPN gateway. Azure Security
                      Center is focused on securing cloud resources and
                      workloads, rather than on networking and connectivity.
                    </p>
                    <p><br /></p>
                  </li>
                </ul>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview"
                    >https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview</a
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
</details>

---

### 4 . Yes or No: In the case of Resource groups, the most restrictive lock in the inheritance takes precedence.
- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
              <label>Overall explanation</label
              >
              <div>
                <p><strong>From the official Azure docs:</strong></p>
                <p>
                  When you apply a lock at a parent scope, all resources within
                  that scope inherit the same lock. Even resources you add later
                  inherit the same parent lock. The most restrictive lock in the
                  inheritance takes precedence.
                </p>
                <p>
                  If you have a <strong>Delete</strong> lock on a resource and
                  attempt to delete its resource group, the feature blocks the
                  whole delete operation. Even if the resource group or other
                  resources in the resource group are unlocked, the deletion
                  doesn't happen. You never have a partial deletion.
                </p>
                <p><br /></p>
                <p>
                  <strong>References:</strong>
                  <a
                    href="https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json"
                    >https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json</a
                  >
                </p>
              </div>
</details>

---

### An organization is planning to migrate large amounts of data from their On-Prem storage to Azure. However, they are worried of incurring huge costs for this transfer and have halted their plans for now. 

### 5 . Is this assumption valid?

- [ ] Yes
- [x] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong
                    >Data ingress&nbsp;(incoming) to Azure data centers is free, so the organizations assumptions are invalid.</strong
                  >
                </p>
                <p><br /></p>
                <p>
                     <img
                    src="https://github.com/user-attachments/assets/7b7ba32b-273f-4364-bc99-91d3e116639c"/><span
                    />
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/pricing/details/bandwidth/"
                  >
                    https://azure.microsoft.com/en-us/pricing/details/bandwidth/</a
                  >
                </p>
              </div>
</details>

---

### 6 .  A startup is planning to run a few simulations and needs to deploy pre-configured Virtual Machines in a lab-like environment using ARM&nbsp;templates. These VMs will be used to test app versions and scale up load testing by creating multiple test agents and environments.

### As the principal consultant, which of the following services would you recommend?

- [x] Azure DevTest Labs
- [ ] Azure Virtual Machine Scale Sets
- [ ] Azure Reserved Virtual Machine (VM) Instances
- [ ] Microsoft Managed Desktop


<details>
  <summary>Explanation</summary>
  <br/>
<div>
                <p><strong>From the official documentation :</strong></p>
                <p>
                  <a href="https://azure.microsoft.com/services/devtest-lab"
                    >Azure DevTest Labs</a
                  >
                  is a service for easily creating, using, and managing
                  infrastructure-as-a-service (IaaS) virtual machines (VMs) and
                  platform-as-a-service (PaaS) environments in labs. Labs offer
                  preconfigured bases and artifacts for creating VMs, and Azure
                  Resource Manager (ARM) templates for creating environments
                  like Azure Web Apps or SharePoint farms.
                </p>
                <p>
                  Lab owners can create preconfigured VMs that have tools and
                  software lab users need. Lab users can claim preconfigured
                  VMs, or create and configure their own VMs and environments.
                  Lab policies and other methods track and control lab usage and
                  costs.
                </p>
                <p><br /></p>
                    <img
                      src="https://github.com/user-attachments/assets/58066193-0111-4d23-bad7-a92c733b7df5"
                    />
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://docs.microsoft.com/en-us/azure/lab-services/devtest-lab-overview"
                    >https://docs.microsoft.com/en-us/azure/lab-services/devtest-lab-overview</a
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
</details>

---

### 7 . A startup has deployed a set of Virtual Machines which are critical for their day-to-day operations. They need to ensure their availability even if a single data center goes down.

### One of their interns has suggested that deploying the VMs through a Scale Set would solve the problem. Do you agree? 

- [x] No
- [ ] Yes


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  This answer does not specify that the scale set will be
                  configured across multiple data centers so this solution does
                  not meet the goal.
                </p>
                <p><br /></p>
                <p>
                  Azure virtual machine scale sets let you create and manage a
                  group of load balanced VMs. The number of VM instances can
                  automatically increase or decrease in response to demand or a
                  defined schedule. Scale sets provide high availability to your
                  applications, and allow you to centrally manage, configure,
                  and update many VMs.
                </p>
                <p><br /></p>
                <p>
                  Virtual machines in a scale set can be deployed across
                  multiple update domains and fault domains to maximize
                  availability and resilience to outages due to data center
                  outages, and planned or unplanned maintenance events.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/availability"
                    >https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/availability</a
                  >
                </p>
              </div>
</details>

---

### 8 . Which of the following is NOT&nbsp;a cost saving solution?

- [x] Load balance your virtual machines to manage incoming traffic
- [ ] Use Azure Reserved Virtual Machine instances
- [ ] Choosing an appropriate instance type for a VM
- [ ] Using a Pay as you go Subscription


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  Load balancing is used for
                  <strong>PERFORMANCE</strong
                  >&nbsp;<strong>OPTIMISATION</strong>&nbsp;and not cost saving.
                </p>
                <p>
                  <strong>Load balancing</strong> refers to evenly distributing
                  load (incoming network traffic) across a group of backend
                  resources or servers.
                </p>
                <p>
                  Azure Load Balancer operates at layer 4 of the Open Systems
                  Interconnection (OSI) model. It's the single point of contact
                  for clients. Load balancer distributes inbound flows that
                  arrive at the load balancer's front end to backend pool
                  instances. These flows are according to configured
                  load-balancing rules and health probes. The backend pool
                  instances can be Azure Virtual Machines or instances in a
                  virtual machine scale set.
                </p>
                <p>
                  A
                  <a
                    href="https://docs.microsoft.com/en-us/azure/load-balancer/components#frontend-ip-configurations"
                    ><strong>public load balancer</strong></a
                  >
                  can provide outbound connections for virtual machines (VMs)
                  inside your virtual network. These connections are
                  accomplished by translating their private IP addresses to
                  public IP addresses. Public Load Balancers are used to load
                  balance internet traffic to your VMs.
                </p>
                <p>
                  An
                  <a
                    href="https://docs.microsoft.com/en-us/azure/load-balancer/components#frontend-ip-configurations"
                    ><strong>internal (or private) load balancer</strong></a
                  >
                  is used where private IPs are needed at the frontend only.
                  Internal load balancers are used to load balance traffic
                  inside a virtual network. A load balancer frontend can be
                  accessed from an on-premises network in a hybrid scenario.
                </p>
                <p>
                  <strong>Reference:&nbsp;</strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview"
                    >https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview</a
                  >
                </p>
              </div>
</details>

---

### 9 . As a consultant, which of the following Locks would you recommend to an organization to prevent deletion or modification of mission-critical resources?

- [ ] CanNotChange
- [ ] isCritical
- [x] ReadOnly
- [ ] CanNotModify


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the official documentation:</strong></p>
                <p>
                  As an administrator, you can lock an Azure subscription,
                  resource group, or resource to protect them from accidental
                  user deletions and modifications. The lock overrides any user
                  permissions.
                </p>
                <p>
                  You can set locks that prevent either deletions or
                  modifications. In the portal, these locks are called
                  <strong>Delete</strong> and <strong>Read-only</strong>. In the
                  command line, these locks are called
                  <strong>CanNotDelete</strong> and <strong>ReadOnly</strong>.
                  In the left navigation panel, the subscription lock feature's
                  name is <strong>Resource locks</strong>, while the resource
                  group lock feature's name is <strong>Locks</strong>.
                </p>
                <ul>
                  <li>
                    <p>
                      <strong>CanNotDelete</strong> means authorized users can
                      read and modify a resource, but they can't delete it.
                    </p>
                  </li>
                  <li>
                    <p>
                      <strong>ReadOnly</strong> means authorized users can read
                      a resource, but they can't delete or update it. Applying
                      this lock is similar to restricting all authorized users
                      to the permissions that the <strong>Reader</strong> role
                      provides.
                    </p>
                    <p><br /></p>
                  </li>
                </ul>
                <p>
                  <strong>Reference :&nbsp;</strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources"
                    >https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources</a
                  >
                </p>
              </div>
</details>

---

### 10 . Which of the following services can help you decouple components and asynchronous message storage, for communication between application components, whether they are running in the cloud, on the desktop, on-premise, or on mobile devices?

- [ ] Azure Data Box
- [ ] Azure File Sync
- [ ] Azure Asynchronous Communicator
- [x] Azure Queue Storage


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the official Azure documentation:</strong></p>
                <p>
                  You can use <strong>Azure Queue Storage</strong> to build
                  flexible applications and separate functions for better
                  durability across large workloads. When you design
                  applications for scale, application components can be
                  decoupled, so that they can scale independently. Queue storage
                  gives you asynchronous message queueing for communication
                  between application components, whether they are running in
                  the cloud, on the desktop, on-premises, or on mobile devices.
                </p>
                <p>
                  A single queue message can be up to <strong>64 KB</strong> in
                  size, and a queue can contain <strong>millions</strong> of
                  messages, up to the total capacity limit of a storage account.
                  Queue storage is often used to create a backlog of work to
                  process asynchronously.
                </p>
                <p>
                  <strong>Reference :&nbsp;</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/services/storage/queues/#overview"
                    >https://azure.microsoft.com/en-us/services/storage/queues/#overview</a
                  >
                </p>
              </div>
</details>

---

### 11 . Which of the following can you use to filter traffic to and from an Azure Virtual Network?

- [ ] Azure Firewall
- [ ] Azure Advanced Threat Protection (ATP)
- [x] Azure Network Security Group
- [ ] Azure DDoS Protection


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  You can use <strong>Azure network security group</strong> to
                  filter network traffic to and from Azure resources in an Azure
                  virtual network. A network security group contains
                  <a
                    href="https://docs.microsoft.com/en-us/azure/virtual-network/security-overview#security-rules"
                    >security rules</a
                  >
                  that allow or deny inbound network traffic to, or outbound
                  network traffic from, several types of Azure resources.
                </p>
                <p>
                  For each rule, you can specify
                  <strong>source and destination, port, and protocol</strong>.
                  <a
                    href="https://docs.microsoft.com/en-us/azure/virtual-network/security-overview"
                    >This</a
                  >
                  article describes properties of a network security group rule,
                  the
                  <a
                    href="https://docs.microsoft.com/en-us/azure/virtual-network/security-overview#default-security-rules"
                    >default security rules</a
                  >
                  that are applied, and the rule properties that you can modify
                  to create an
                  <a
                    href="https://docs.microsoft.com/en-us/azure/virtual-network/security-overview#augmented-security-rules"
                    >augmented security rule</a
                  >.
                </p>
                <p><br /></p>
                <img
                  src="https://github.com/user-attachments/assets/ba85681a-dbbd-466a-8c3a-047b699023f2"
                  style="display: none"
                />
                <p><br /></p>
                <p>
                  <strong>Reference :</strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/virtual-network/security-overview"
                  >
                    https://docs.microsoft.com/en-us/azure/virtual-network/security-overview</a
                  >
                </p>
              </div>
</details>

---

### 12 . In which scenario is geo-redundant storage (GRS) recommended for Azure Storage?

- [ ] When cost optimization is the top priority.
- [ ] When read access to the secondary region is essential.
- [ ] When data needs to be replicated asynchronously across availability zones
- [x] When protection from regional disasters is required.


<details>
  <summary>Explanation</summary>
  <br/>
<div>
                <p>
                  Geo-redundant storage (GRS) copies data synchronously within a
                  single region and then asynchronously to a
                  <strong>secondary</strong> region, providing durability and
                  protection against regional disasters.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy"
                    >https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy</a
                  >
                </p>
              </div>
</details>

---

### 13 . Is there a default spending limit for the Azure Free account?

- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p>
                  A credit of <strong>$200</strong> is assigned to the Free
                  account and is valid for 30 days from the
                </p>
                <p>date of activation.</p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/361eddde-e5e1-45ac-abac-860435db8f93"/>
                </p>
                <p>
                  <strong>Reference:</strong>
                  <a href="https://azure.microsoft.com/en-in/free/"
                    >https://azure.microsoft.com/en-in/free/</a
                  >
                </p>
              </div>
</details>

---

### 14 . Yes or No: When a subscription expires, the trusted instance of the Azure AD service remains, but the security principals still maintain access to Azure resources.

- [x] No
- [ ] Yes


<details>
  <summary>Explanation</summary>
  <br/>
                <div>
                <p><strong>From the official Azure docs:</strong></p>
                <p><br /></p>
                <p>
                  An Azure subscription has a trust relationship with Azure
                  Active Directory (Azure AD). A subscription trusts Azure AD to
                  authenticate users, services, and devices.
                </p>
                <p>
                  <strong>Multiple</strong> subscriptions can trust the same
                  Azure AD directory. Each subscription can only trust a single
                  directory.
                </p>
                <p>
                  One or more Azure subscriptions can establish a trust
                  relationship with an instance of Azure Active Directory (Azure
                  AD) in order to authenticate and authorize security principals
                  and devices against Azure services.
                  <strong
                    >When a subscription expires, the trusted instance of the
                    Azure AD service remains, but the security principals LOSE
                    access to Azure resources.</strong
                  >
                </p>
                <p><br /></p>
                <p>
                  <strong>References:</strong>
                  <a
                    href="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory"
                    >https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory</a
                  >
                </p>
              </div>
</details>

---

### 15 . What information can you input into the TCO calculator to estimate the cost difference between your current datacenter and Azure? (Select all that apply)

- [x] IT labor costs
- [x] Current infrastructure configuration
- [x] Power costs
- [ ] Subscription type


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <ul>
                  <li>
                    <p>
                      <strong>Current infrastructure configuration -</strong>
                      Correct, the TCO calculator allows you to input your
                      current infrastructure configuration, including servers,
                      databases, storage, and outbound network traffic.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Power costs -</strong> Correct, the TCO calculator
                      lets you add assumptions about power costs in your current
                      environment to estimate the cost difference between
                      on-premises and Azure.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>IT labor costs -</strong> Correct, the TCO
                      calculator allows you to include assumptions about IT
                      labor costs to help estimate the cost difference between
                      your current environment and Azure.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Subscription type -</strong> Incorrect, the TCO
                      calculator focuses on comparing on-premises infrastructure
                      costs with Azure Cloud infrastructure costs. Subscription
                      type is not part of the input for the TCO calculator.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators"
                    >https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators</a
                  >
                </p>
              </div>
</details>

---

### 16 . Is it possible to run a PowerShell module directly from a Windows computer with Azure PowerShell installed?

- [ ] No
- [x] Yes


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  A Powershell script can create Azure resources, and since the
                  Powershell module is installed on the Windows computer, this
                  is easily doable.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/ise/how-to-write-and-run-scripts-in-the-windows-powershell-ise?view=powershell-7.1&amp;viewFallbackFrom=powershell-6"
                    >https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/ise/how-to-write-and-run-scripts-in-the-windows-powershell-ise?view=powershell-7.1&amp;viewFallbackFrom=powershell-6</a
                  >
                </p>
              </div>
</details>

---

### 17 . If you want to raise the limit or quota above the default limit, _____________________

- [ ] define a blueprint in Azure Blueprint to implement this change
- [ ] Upgrade your support plan
- [x] open an online customer support request at no charge
- [ ] create an Azure policy defining this increase but it will be charged.


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  If you want to raise the limit or quota above the default
                  limit, you can open an online customer support request at no
                  charge.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits"
                    >https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits
                  </a>
                </p>
              </div>
</details>

---

### 18 . Which of the following would you use if you want to keep track of the performance or issues related to your specific VM or container instances, databases, your applications?

- [ ] Azure Sentinel
- [ ] Azure Advisor
- [ ] Azure Service Health
- [x] Azure Monitor


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the Official Azure Documentation: </strong></p>
                <p><br /></p>
                <p>
                  If you want to keep track of the performance or issues related
                  to your specific VM or container instances, databases, your
                  applications, and so on, you want to visit Azure Monitor and
                  create reports and notifications to help you understand how
                  your services are performing or diagnose issues related to
                  your Azure usage.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/3-analyze-decision-criteria"
                    >https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/3-analyze-decision-criteria</a
                  >
                </p>
              </div>
</details>

---

### 19 . Yes or No: A resource can connect to resources in other resource groups.

- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the official documentation :</strong></p>
                <p><br /></p>
                <p>
                  A resource can connect to resources in other resource groups.
                  This scenario is common when the two resources are related but
                  don't share the same lifecycle. For example, you can have a
                  web app that connects to a database in a different resource
                  group.
                </p>
                <p><strong>More about resource groups:</strong></p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/5c6ec685-75fc-4523-b66d-3050a38b7a28"/>
                </p>
                <p>
                  <strong>Reference :</strong>&nbsp;<a
                    href="https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview#resource-groups"
                    >https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview#resource-groups</a
                  >
                </p>
              </div>
</details>

---

### 20 . Your company is considering migrating its on-premises infrastructure to Azure. The management team wants to compare the costs of running the existing infrastructure in-house to the projected costs in Azure. Which tool should you use to provide this comparison?

- [ ] Pricing calculator
- [x] Total Cost of Ownership calculator
- [ ] Billing calculator
- [ ] Resource cost calculator


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong>The Total Cost of Ownership (TCO) calculator</strong>
                  is designed to help you compare the costs for running an
                  on-premises infrastructure compared to an Azure Cloud
                  infrastructure. It takes into account your current
                  infrastructure configuration, power costs, IT labor costs, and
                  other factors to provide an estimate of the cost difference
                  between the two environments.
                </p>
                <p><strong>Other options - </strong></p>
                <ul>
                  <li>
                    <p>
                      <strong>Pricing calculator -</strong> This tool is
                      designed to estimate the cost of provisioning resources in
                      Azure but does not provide a comparison between
                      on-premises infrastructure costs and Azure Cloud
                      infrastructure costs.
                    </p>
                  </li>
                  <li>
                    <p>
                      <strong>Resource cost calculator - </strong>This option is
                      incorrect because there is no specific "Resource cost
                      calculator" in Azure. The Pricing calculator and TCO
                      calculator are the main tools used to estimate costs in
                      Azure.
                    </p>
                  </li>
                  <li>
                    <p>
                      <strong>Billing calculator -</strong> This option is
                      incorrect because there is no specific "Billing
                      calculator" in Azure. The Pricing calculator estimates
                      costs for provisioning resources in Azure, while the TCO
                      calculator compares on-premises infrastructure costs to
                      Azure Cloud infrastructure costs.
                    </p>
                  </li>
                </ul>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators"
                    >https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators</a
                  >
                </p>
              </div>
</details>

---

### 21 . Your organization is using Azure for disaster recovery purposes. You have set up replication of virtual machines to an Azure region different from the primary region. Which of the following factors could affect the cost of this setup?

- [x] The number of virtual machines being replicated
- [x] The network bandwidth between the primary and secondary regions
- [x] The types of virtual machines being replicated.
- [x] The amount of data being replicated


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  All of the options could potentially affect the cost of this
                  setup.
                </p>
                <ul>
                  <li>
                    <p>
                      <strong
                        >The number of virtual machines being replicated
                        -</strong
                      >
                      The more virtual machines being replicated, the higher the
                      cost will be, as each VM will require resources to be
                      replicated to the secondary region.
                    </p>
                  </li>
                </ul>
                <ul>
                  <li>
                    <p>
                      <strong>The amount of data being replicated </strong>- The
                      amount of data being replicated can have a significant
                      impact on the cost, as data transfer between regions
                      incurs charges.
                    </p>
                  </li>
                </ul>
                <ul>
                  <li>
                    <p>
                      <strong
                        >The network bandwidth between the primary and secondary
                        regions -</strong
                      >
                      The network bandwidth between the primary and secondary
                      regions can also impact the cost, as higher bandwidth
                      requirements will result in higher charges.
                    </p>
                  </li>
                </ul>
                <ul>
                  <li>
                    <p>
                      <strong
                        >The types of virtual machines being replicated
                        -</strong
                      >
                      The types of virtual machines being replicated could also
                      impact the cost, as certain VM sizes are more expensive
                      than others.
                    </p>
                  </li>
                </ul>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-overview"
                    >https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-overview</a
                  >
                </p>
              </div>
</details>

---

### 22 . Which of these is NOT a valid Azure resource group constraint?

- [ ] A Resource group can be used to apply consistent policies to resources using another service.
- [ ] A Resource group can contain resources that belong to different subscriptions
- [x] A Resource group must be in the same region as its resources
- [ ] A Resource group can contain resources located in different regions


<details>
  <summary>Explanation</summary>
  <br/>
 <div>
                <p>
                  The option
                  <strong
                    >"Resource group must be in the same region as its
                    resources"</strong
                  >
                  is NOT&nbsp;a valid constraint for Resource Groups.
                </p>
                <p><br /></p>
                <p>
                  While it's recommended that resources in a resource group be
                  located in the same region for optimal performance, it's not a
                  strict requirement. Resources in a resource group can span
                  different regions, and this can be useful for achieving high
                  availability and disaster recovery scenarios, as well as for
                  optimizing data access for users in different geographic
                  locations.
                </p>
                <p><br /></p>
                <p>Other options:</p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong
                        >Resource group can contain resources located in
                        different regions:</strong
                      >&nbsp;This is a valid Azure resource group constraint. As
                      mentioned above, resources in a resource group can span
                      different regions.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong
                        >Resource group can contain resources that belong to
                        different subscriptions:</strong
                      >&nbsp;This is also a valid Azure resource group
                      constraint. A single resource group can contain resources
                      that belong to different subscriptions, which is useful
                      for managing resources across multiple subscriptions.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong
                        >Resource group can be used to apply consistent policies
                        to resources:</strong
                      >&nbsp;This is also a valid Azure resource group
                      constraint. Azure Policy can be used to apply governance
                      policies to all resources in a resource group, ensuring
                      consistent compliance across resources.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview"
                    >https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview</a
                  >
                </p>
              </div>
</details>

---

### 23 . Which of the following would you need to set up alerts for outages or when autoscaling is about to deploy new instances?

- [ ] Azure Service Health
- [ ] Azure Advisor
- [x] Azure Monitor
- [ ] Azure Bastion


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  You can use Azure Monitor to set up alerts for key events that
                  are related to your specific resources.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference : </strong
                  ><a
                    href="https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/3-analyze-decision-criteria"
                    >https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/3-analyze-decision-criteria</a
                  >
                </p>
              </div>
</details>

---

### 24 . You plan to provision Infrastructure as a Service (IaaS) resources in Azure.
### Which of the following is an example of IaaS in Azure?

- [ ] Azure HDInsight
- [ ] Azure Machine Learning
- [x] Azure Virtual Machine
- [ ] Azure Event Hubs


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  An Azure virtual machine is an example of Infrastructure as a
                  Service (<strong>IaaS</strong>).
                </p>
                <p><br /></p>
                <p>
                  Azure Machine Learning, Azure Event Hubs, Azure HDInsight are
                  all examples of
                  <strong>Platform as a Service </strong>(<strong>Paas</strong>)
                </p>
                <p><br /></p>
                <p><br /></p>
                <p><strong>References:</strong></p>
                <p><br /></p>
                <p>
                  <a
                    href="https://azure.microsoft.com/en-gb/overview/what-is-iaas/"
                    >https://azure.microsoft.com/en-gb/overview/what-is-iaas/</a
                  >
                </p>
                <p>
                  <a
                    href="https://azure.microsoft.com/en-gb/overview/what-is-paas/"
                    >https://azure.microsoft.com/en-gb/overview/what-is-paas/</a
                  >
                </p>
                <p>
                  <a
                    href="https://techcommunity.microsoft.com/t5/educator-developer-blog/getting-started-with-windows-azure-series-1-overview/ba-p/378385"
                    >https://techcommunity.microsoft.com/t5/educator-developer-blog/getting-started-with-windows-azure-series-1-overview/ba-p/378385</a
                  >
                </p>
              </div>
</details>

---

### 25. Yes or No: In order to move a VM&nbsp;from one region to another, one must be prepared for a brief downtime.

- [ ] No
- [x] Yes


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the official documentation:</strong></p>
                <p><br /></p>
                <p>
                  Virtual Machines are resources and can be moved to a new
                  region.&nbsp;
                </p>
                <p><br /></p>
                <p>
                  For VMs, <strong>replica</strong> VMs are created in the
                  target region. The source VM is shut down, and some downtime
                  occurs (usually minutes).
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/azure/resource-mover/tutorial-move-region-virtual-machines"
                    >https://learn.microsoft.com/en-us/azure/resource-mover/tutorial-move-region-virtual-machines</a
                  >
                </p>
              </div>
</details>

---

### 26 . Yes or No: The composite SLA&nbsp;for an application replying on multiple services would be higher than the individual SLAs&nbsp;of the particular services.

- [ ] Yes
- [x] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p><strong>From the official Azure documentation:</strong></p>
                <p><br /></p>
                <p><br /></p>
                <p>
                  <code><strong>Composite SLAs</strong></code> involve multiple
                  services supporting an application, each with differing levels
                  of availability.
                </p>
                <p><br /></p>
                <p>
                  For example, consider an App Service web app that writes to
                  Azure SQL Database. At the time of this writing, these Azure
                  services have the following SLAs:
                </p>
                <p><strong>App Service web apps</strong> = 99.95%</p>
                <p><strong>SQL Database</strong> = 99.99%</p>
                <p>
                  What is the maximum downtime you would expect for this
                  application? If either service fails, the whole application
                  fails. The probability of each service failing is independent,
                  so the composite SLA for this application is
                  <strong>99.95% × 99.99% = 99.94%</strong>. That's
                  <strong>LOWER</strong> than the individual SLAs, which isn't
                  surprising because an application that relies on multiple
                  services has more potential failure points.
                </p>
                <p>
                  You can improve the composite SLA by creating independent
                  fallback paths. For example, if SQL Database is unavailable,
                  put transactions into a queue to be processed later.
                </p>
                <p><br /></p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/29d77ca9-9746-4850-899c-dcb1381e6723"/> 
                </p>
                <p><br /></p>
                <p>
                  With this design, the application is still available even if
                  it can't connect to the database. However, it fails if the
                  database and the queue both fail at the same time. The
                  expected percentage of time for a simultaneous failure is
                  0.0001 × 0.001, so the composite SLA for this combined path
                  is:
                </p>
                <p>
                  <strong>Database <em>or</em> queue</strong> = 1.0 − (0.0001 ×
                  0.001) = 99.99999%
                </p>
                <p>The <strong>total</strong> composite SLA is:</p>
                <p>
                  <strong
                    >Web app <em>and</em> (database <em>or</em> queue) = 99.95%
                    × 99.99999% = ~99.95%</strong
                  >
                </p>
                <p>
                  There are tradeoffs to this approach. The application logic is
                  more complex, you are paying for the queue, and you need to
                  consider data consistency issues.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference :&nbsp;</strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/business-metrics"
                    >https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/business-metrics</a
                  >
                </p>
              </div>
</details>

---

### 27 . If you setup a free Azure account, then does the Standard&nbsp;support plan come along with this free account?

- [x] No
- [ ] Yes


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  The <strong>BASIC</strong> Support plan is associated with all
                  accounts but a <strong>STANDARD</strong>&nbsp;plan needs to be
                  purchased and costs $100/month.
                </p>
                <p><br /></p>
                <img
                  src="https://github.com/user-attachments/assets/84f3bc43-3bc4-427f-a175-926067551277"/>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a href="https://azure.microsoft.com/en-in/support/plans/"
                    >https://azure.microsoft.com/en-in/support/plans/</a
                  >
                </p>
              </div>
</details>

---

### 28 . Which of the following services is an Apache Spark-based analytics platform optimized for the Microsoft Azure cloud services platform?

- [ ] Azure Machine Learning Studio
- [ ] Azure Bot Services
- [x] Azure Databricks
- [ ] Azure Cognitive Services


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong
                    >Please read this answer carefully. 'Optimised' is the
                    keyword in the question.</strong
                  >
                </p>
                <p><br /></p>
                <p>
                  Lot of people get confused between Azure Databricks and Azure
                  HDInsight.
                </p>
                <p><br /></p>
                <p>
                  Azure HDInsight is primarily a managed Apache Hadoop service
                  that lets you run Apache Spark, Apache Hive, Apache Kafka,
                  Apache HBase, and more in the cloud.
                </p>
                <p><br /></p>
                <p>
                  Azure Databricks is a
                  <strong>premium Spark offering</strong> that is ideal for
                  customers who want their data scientists to collaborate easily
                  and run their <strong>Spark</strong> based workloads
                  efficiently and at industry leading performance.
                </p>
                <p>
                  It is essentially an Apache Spark-based analytics platform
                  optimized for the Microsoft Azure cloud services platform.
                </p>
                <p><br /></p>
                <p><strong>References:</strong></p>
                <p>
                  <a
                    href="https://docs.microsoft.com/en-us/answers/questions/26097/can-anyone-please-post-the-differences-between-azu.html"
                    >https://docs.microsoft.com/en-us/answers/questions/26097/can-anyone-please-post-the-differences-between-azu.html</a
                  >
                </p>
                <p>
                  <a href="https://docs.microsoft.com/en-us/azure/databricks/"
                    >https://docs.microsoft.com/en-us/azure/databricks/</a
                  >
                </p>
                <p>
                  <a href="https://docs.microsoft.com/en-us/azure/hdinsight/"
                    >https://docs.microsoft.com/en-us/azure/hdinsight/</a
                  >
                </p>
              </div>
</details>

---


### 29 . You want to set up a VPN connection between two Azure virtual networks that are in different regions. Which of the following VPN connection types would be best suited for this scenario?

- [x] Site-to-Site (IPsec)
- [ ] VNet-to-VNet (IPsec)
- [ ] Point-to-Site (VPN over SSL)
- [ ] ExpressRoute


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>The correct answer <strong>Site-to-Site (IPsec).</strong></p>
                <p><br /></p>
                <p>
                  Site-to-Site (IPsec) VPN connection type is used to connect
                  two or more virtual networks that are in different regions,
                  data centers, or even different cloud providers. It allows you
                  to connect an on-premises network or a branch office network
                  to an Azure virtual network, or to connect two Azure virtual
                  networks that are in different regions. Site-to-Site VPN
                  connections use a VPN gateway to provide a secure connection
                  over the Internet. IPsec is the protocol used to secure the
                  VPN connection.
                </p>
                <p><br /></p>
                <p><strong>Other options:</strong></p>
                <p><br /></p>
                <p>
                  <strong>VNet-to-VNet (IPsec):&nbsp;</strong>This is not the
                  best choice for this scenario because it is designed to
                  connect two virtual networks within the same region. It
                  creates an IPsec tunnel between the two virtual networks,
                  allowing resources to communicate securely and privately over
                  the Microsoft backbone network. Since the two virtual networks
                  in this scenario are in different regions, VNet-to-VNet
                  (IPsec) would not be the most efficient or cost-effective
                  option.
                </p>
                <p><br /></p>
                <p>
                  <strong>Point-to-Site (VPN over SSL)</strong>: This is used to
                  connect individual devices to an Azure virtual network over a
                  VPN connection. It is not suitable for connecting virtual
                  networks in different regions.
                </p>
                <p><br /></p>
                <p>
                  <strong>ExpressRoute:</strong>&nbsp;This is a private
                  connection between an on-premises infrastructure and an Azure
                  data center. It provides dedicated, high-speed connectivity
                  between your network and Azure, but it is not suitable for
                  connecting virtual networks in different regions.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal"
                    >https://learn.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal</a
                  >
                </p>
              </div>
</details>

---

### 30 . A company has approached you to help them plan an architecture, that would be capable of capturing data from millions of connected devices and securely storing them for analysis. Which of the following two services would you include in the project proposal?

- [x] Azure Data Lake
- [ ] Azure Notification Hubs
- [ ] Azure ExpressRoute
- [x] Azure IoT Hubs


<details>
  <summary>Explanation</summary>
  <br/>
  <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p><strong>From the official Azure documentation:</strong></p>
                <p><br /></p>
                <p>
                  Azure IoT Hub is a managed service hosted in the cloud that
                  acts as a central message hub for communication between an IoT
                  application and its attached devices. You can connect millions
                  of devices and their backend solutions reliably and securely.
                  Almost any device can be connected to an IoT hub.
                </p>
                <p>
                  Several messaging patterns are supported, including
                  device-to-cloud telemetry, uploading files from devices, and
                  request-reply methods to control your devices from the cloud.
                  IoT Hub also supports monitoring to help you track device
                  creation, device connections, and device failures.
                </p>
                <p>
                  IoT Hub scales to millions of simultaneously connected devices
                  and millions of events per second to support your IoT
                  workloads. For more information about scaling your IoT Hub,
                  see
                  <a
                    href="https://docs.microsoft.com/en-in/azure/iot-hub/iot-hub-scaling"
                    >IoT Hub scaling</a
                  >. To learn more about the tiers of service offered by IoT
                  Hub, check out the
                  <a href="https://azure.microsoft.com/pricing/details/iot-hub/"
                    >pricing page</a
                  >.
                </p>
                <p><br /></p>
                <p>
                  IoT Hub can further route messages to
                  <strong>Azure Data Lake Storage.</strong>
                </p>
                <p><br /></p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/a71253f4-1789-4064-9553-2e4078e39ae2"
                  />
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference 1 (IoT Hub) -</strong>
                  <a href="https://azure.microsoft.com/en-in/services/iot-hub/"
                    >https://azure.microsoft.com/en-in/services/iot-hub/</a
                  >
                </p>
                <p>
                  <strong>Reference 2 (Data Lake) - </strong
                  ><a
                    href="https://azure.microsoft.com/en-in/solutions/data-lake/"
                    >https://azure.microsoft.com/en-in/solutions/data-lake/</a
                  >
                </p>
              </div>
</details>

---

### 31 . Yes or No: Azure HDInsight can be used to run popular open-source frameworks including Apache Hadoop, Spark, Hive, Kafka, and more for open-source big data analytics.

- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p>
                  Yes! Azure HDInsight is an enterprise-ready, managed cluster
                  service for open-source analytics.
                </p>
                <p><br /></p>
                <p>
                  You can run popular open-source frameworks—including
                  <code>Apache Hadoop, Spark, Hive, Kafka, </code>
                </p>
                <p>
                  <code>and more</code>—using Azure HDInsight, a customizable,
                  enterprise-grade service for open-source analytics. You can
                  also effortlessly process massive amounts of data and get all
                  the benefits of the broad open-source project ecosystem with
                  the global scale of Azure. Easily migrate your big data
                  workloads and processing to the cloud.
                </p>
                <p><br /></p>
              <img
                  src="https://github.com/user-attachments/assets/d440f845-09a2-44bf-a785-04aa0540f18b"
                />
                 <img
                  src="https://github.com/user-attachments/assets/e13162f9-67b7-4d28-9677-157a3019fa62"
                />
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://azure.microsoft.com/en-gb/services/hdinsight/#documentation"
                    >https://azure.microsoft.com/en-gb/services/hdinsight/#documentation</a
                  >
                </p>
              </div>
</details>

---

### 32 . What is the key advantage of using zone-redundant storage (ZRS) in the primary region?

- [x] It allows data to be accessible even if a zone becomes unavailable.
- [ ] It provides read access to replicated data in the secondary region.
- [ ] It guarantees data replication to a secondary region.
- [ ] It offers the highest level of durability compared to other options.


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p><strong>From the official documentation: </strong></p>
                <p><br /></p>
                <p>
                  For Availability Zone-enabled Regions, zone-redundant storage
                  (ZRS) replicates your Azure Storage data synchronously across
                  three Azure availability zones in the primary region. ZRS
                  offers durability for Azure Storage data objects of at least
                  12 nines (99.9999999999%) over a given year.
                </p>
                <p><br /></p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/17990b4b-e9e7-4799-8ca2-e484d7d2869f"
                    />
                </p>
                <p><br /></p>
                <p>
                  With ZRS, your data is still accessible for both read and
                  write operations even if a zone becomes unavailable.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy"
                    >https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy</a
                  >
                </p>
              </div>
</details>

---

### 33 . You have managed an App that you developed and deployed On-Prem for a long time, but would now like to move it to Azure and be relieved of all the manual administration and maintenance. Which of the following buckets would be most suitable for your use case?

- [x] Platform as a service (Paas)
- [ ] Infrastructure as a Service (Iaas)
- [ ] Software as a service (Saas)
- [ ] Database as a Service (Daas)


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong>Platform as a service (PaaS)</strong> is a complete
                  development and deployment environment in the cloud, with
                  resources that enable you to deliver everything from simple
                  cloud-based apps to sophisticated, cloud-enabled enterprise
                  applications. You purchase the resources you need from a cloud
                  service provider on a pay-as-you-go basis and access them over
                  a secure Internet connection.
                </p>
                <p><br /></p>
                <p>
                  Like IaaS, PaaS includes infrastructure—servers, storage, and
                  networking—but also middleware, development tools, business
                  intelligence (BI) services, database management systems, and
                  more. PaaS is designed to support the
                  <strong>complete</strong> web application lifecycle: building,
                  testing, deploying, managing, and updating.
                </p>
                <p><br /></p>
                <p>
                  PaaS allows you to <strong>avoid</strong> the expense and
                  complexity of buying and managing software licenses, the
                  underlying application infrastructure and middleware,
                  container orchestrators such as Kubernetes, or the development
                  tools and other resources. You manage the applications and
                  services you develop, and the cloud service provider typically
                  manages everything else.
                </p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/41850579-bdb2-4a2d-9375-4b621bf81f11"
                  />
                </p>
                <p><br /></p>
                <p>
                  <strong
                    >Since we need to reduce the overhead effort of managing
                    everything, and create our
                  </strong>
                </p>
                <p><strong>own solution, PaaS is the best option!</strong></p>
                <p><br /></p>
                <p>
                  <strong>References :</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/overview/what-is-paas/"
                    >&nbsp;https://azure.microsoft.com/en-us/overview/what-is-paas/</a
                  >
                </p>
              </div>
</details>

---

### 34 . Yes or No: Azure Advisor has the ability to provide recommendations for Azure ExpressRoute.

- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p>
                  <strong>From the official&nbsp;Azure documentation:</strong>
                </p>
                <p><br /></p>
                <p>
                  Advisor is a personalized cloud consultant that helps you
                  follow best practices to optimize your Azure deployments. It
                  analyzes your resource configuration and usage telemetry and
                  then recommends solutions that can help you improve the cost
                  effectiveness, performance, Reliability (formerly called High
                  availability), and security of your Azure resources.
                </p>
                <p><br /></p>
                <p>
                  <img
                    src="https://github.com/user-attachments/assets/f71d2a2c-02ec-4f57-863f-2bcaa7ebd1a3"
                    style="display: none"
                  />
                </p>
                <p><br /></p>
                <p>
                  <strong>Advisor provides recommendations for</strong>
                  Application Gateway, App Services, availability sets, Azure
                  Cache, Azure Data Factory, Azure Database for MySQL, Azure
                  Database for PostgreSQL, Azure Database for MariaDB, Azure
                  ExpressRoute, Azure Cosmos DB, Azure public IP addresses,
                  Azure Synapse Analytics, SQL servers, storage accounts,
                  Traffic Manager profiles, and virtual machines.
                </p>
                <p>
                  Azure Advisor also includes your recommendations from
                  <a
                    href="https://docs.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction"
                    >Microsoft Defender for Cloud</a
                  >
                  which may include recommendations for additional resource
                  types.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference :</strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/advisor/advisor-overview"
                    >https://docs.microsoft.com/en-us/azure/advisor/advisor-overview</a
                  >
                </p>
              </div>
</details>

---

### 35 . Yes or No: Azure HDInsight an example of a Software as a Service (SaaS) offering.

- [ ] Yes
- [x] No


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>No, Azure HDInsight is a PaaS&nbsp;offering.</p>
                <p><br /></p>
                <p><strong>From the official Azure documentation: </strong></p>
                <p><br /></p>
                <p>
                  Run popular open-source frameworks—including Apache Hadoop,
                  Spark, Hive, Kafka, and more—using Azure HDInsight, a
                  customizable, enterprise-grade service for open-source
                  analytics. Effortlessly process massive amounts of data and
                  get all the benefits of the broad open-source project
                  ecosystem with the global scale of Azure. Easily migrate your
                  big data workloads and processing to the cloud.
                </p>
                <p><br /></p>
                <p>
                  <strong>References:</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/services/hdinsight/#features"
                    >https://azure.microsoft.com/en-us/services/hdinsight/#features</a
                  >
                </p>
              </div>
</details>

---

### 36 . Which of the following services would you use to embed the ability to see, hear, speak, search, understand, and accelerate decision-making into your apps without having any machine-learning expertise?

- [ ] Azure App Service
- [ ] Azure Events Hub
- [ ] Azure Machine Learning Studio
- [x] Azure Cognitive Services


<details>
  <summary>Explanation</summary>
  <br/>
 <div
                data-purpose="safely-set-inner-html:rich-text-viewer:html"
                class="ud-text-md rt-scaffolding"
                id="overall-explanation"
              >
                <p>
                  Cognitive Services bring AI within reach of every
                  developer—without requiring machine-learning expertise. All it
                  takes is an API call to embed the ability to
                  <strong
                    >see, hear, speak, search, understand, and accelerate
                    decision-making into your apps.</strong
                  >
                </p>
                <p><br /></p>
                <p>
                  <img src="https://github.com/user-attachments/assets/2cdc2cef-988d-4497-ae01-4337ce8c6128" />
                </p>
                <p><br /></p>
               <img src="https://github.com/user-attachments/assets/6d0f4cff-3ca5-43f8-a479-2fb0b0c4067e" />
                <p><br /></p>
                <p><br /></p>
                <p>
                  <strong>Reference :</strong
                  ><a
                    href="https://azure.microsoft.com/en-us/services/cognitive-services/#features"
                    >&nbsp;https://azure.microsoft.com/en-us/services/cognitive-services/#features</a
                  >
                </p>
              </div>
</details>

---

### 37 . What is the main purpose of the Azure Pricing Calculator?

- [ ] To manage the billing of your Azure account
- [ ] To provision resources in Azure
- [x] To estimate the cost of provisioning resources in Azure
- [ ] To compare the costs of running on-premises and Azure Cloud infrastructure


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong
                    >To estimate the cost of provisioning resources in Azure
                    -</strong
                  >
                  This is the correct answer because the Azure Pricing
                  Calculator is specifically designed to help users estimate the
                  cost of provisioning resources in Azure.
                </p>
                <p><br /></p>
                <p>
                  <strong
                    >To compare the costs of running on-premises and Azure Cloud
                    infrastructure -</strong
                  >
                  This option is incorrect because this function is performed by
                  the Total Cost of Ownership (TCO) Calculator, not the Pricing
                  Calculator.
                </p>
                <p><br /></p>
                <p>
                  <strong>To provision resources in Azure - </strong>This option
                  is incorrect because the Pricing Calculator does not provision
                  resources; it only provides cost estimates for resources. To
                  provision resources, you would use the Azure Portal or other
                  management tools.
                </p>
                <p><br /></p>
                <p>
                  <strong>To manage the billing of your Azure account -</strong>
                  This option is incorrect because the Pricing Calculator does
                  not manage billing. It only provides cost estimates for
                  resources. To manage billing, you would use the Azure Cost
                  Management and Billing tools.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators"
                    >https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/3-compare-pricing-total-cost-of-ownership-calculators</a
                  >
                </p>
              </div>
</details>

---

### 38 . You have configured a VPN connection between an on-premises network and an Azure virtual network using Site-to-Site VPN (IPsec). However, you are experiencing connectivity issues and suspect that there is an issue with the VPN gateway. Which Azure service can you use to diagnose connectivity issues for your VPN gateway?

- [ ] Azure Application Gateway
- [ ] Azure ExpressRoute
- [x] Azure Network Watcher
- [ ] Azure Traffic Manager


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>The correct answer is Azure Network Watcher.</p>
                <p><br /></p>
                <p>
                  <strong>Azure Network Watcher</strong> is a monitoring and
                  diagnostic service that provides tools to diagnose network
                  issues in Azure. It includes a VPN diagnostics tool that can
                  be used to diagnose connectivity issues with VPN gateways,
                  including Site-to-Site VPN (IPsec) gateways. The tool can help
                  identify configuration issues, routing issues, and other
                  common problems that can cause connectivity issues.
                </p>
                <p><br /></p>
                <p>Other Options:</p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Azure Traffic Manager</strong>: This is a global
                      DNS load balancer that can be used to distribute incoming
                      traffic across multiple Azure regions. It is not designed
                      for diagnosing network connectivity issues.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Azure Application Gateway:&nbsp;</strong>This is a
                      web traffic load balancer that can be used to manage and
                      route HTTP and HTTPS traffic. It is not designed for
                      diagnosing network connectivity issues.
                    </p>
                    <p><br /></p>
                  </li>
                  <li>
                    <p>
                      <strong>Azure ExpressRoute:</strong>&nbsp;This is a
                      dedicated, private connection between an on-premises
                      datacenter and Azure. It is not used for Site-to-Site VPN
                      (IPsec) connections, and is not designed for diagnosing
                      connectivity issues with VPN gateways.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/azure/network-watcher/network-watcher-monitoring-overview"
                    >https://learn.microsoft.com/en-us/azure/network-watcher/network-watcher-monitoring-overview</a
                  >
                </p>
              </div>
</details>

---

### 39 . You are designing a solution to improve the resiliency of your application in Azure. Which of the following would you choose to ensure your application remains available during planned maintenance events?

- [ ] Azure Container Registry
- [ ] Scale Sets
- [ ] Availability Sets
- [x] Availability Zones


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  <strong>Availability Zones</strong> are a high-availability
                  offering from Microsoft Azure that provide a fault-tolerant
                  architecture for applications. Availability Zones are
                  physically separate data centers within an Azure region, each
                  with their own power, cooling, and networking infrastructure.
                </p>
                <p>
                  By deploying virtual machines and other resources across
                  multiple Availability Zones, you can ensure that your
                  application remains available even in the event of a data
                  center outage or other disruption. Availability Zones provide
                  redundancy and isolation, which helps protect your application
                  from both planned and unplanned downtime.
                </p>
                <p><br /></p>
                <p>Other options -</p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Availability Sets </strong>are a feature of
                      Microsoft Azure that help ensure that virtual machines are
                      distributed across multiple fault domains and update
                      domains within a single data center or region. This helps
                      protect against hardware failures and other disruptions by
                      ensuring that virtual machines are not all located in the
                      same physical rack or power source. However, Availability
                      Sets do not provide any inherent protection against data
                      center-wide outages, which can occur due to issues such as
                      network outages, power failures, or natural disasters. In
                      such cases, all virtual machines in the affected data
                      center or region may become unavailable.
                    </p>
                    <p><br /></p>
                  </li>
                </ul>
                <ul>
                  <li>
                    <p>
                      <strong>Scale Sets</strong> is not necessarily the best
                      choice for ensuring availability during planned
                      maintenance events because it only provides horizontal
                      scalability by adding or removing virtual machines based
                      on demand, but does not inherently provide any
                      availability benefits beyond what is provided by the
                      underlying infrastructure.
                    </p>
                    <p>
                      Scale Sets are a feature of Microsoft Azure that provide
                      automatic scaling of a set of virtual machines based on
                      demand. This helps ensure that the application can handle
                      varying levels of traffic and usage, but does not
                      necessarily provide inherent resiliency against planned
                      maintenance events or other types of disruptions.
                    </p>
                    <p><br /></p>
                  </li>
                </ul>
                <ul>
                  <li>
                    <p>
                      <strong>Azure Container Registry </strong>is a managed
                      private Docker registry service that enables you to store
                      and manage container images in Azure. While it provides
                      benefits such as secure storage, authentication, and
                      geo-replication of container images, it is not directly
                      related to ensuring availability during planned
                      maintenance events.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview"
                    >https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview</a
                  >
                </p>
              </div>
</details>

---

### 40 . What is the primary purpose of redundancy in Azure Storage?

- [x] To provide high availability and durability in the face of failures.
- [ ] To increase the storage capacity of Azure resources.
- [ ] To protect against data corruption and unauthorized access.
- [ ] To improve data processing speed for applications.

<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  From the official documentation: Azure Storage always stores
                  multiple copies of your data so that it's protected from
                  planned and unplanned events such as transient hardware
                  failures, network or power outages, and natural disasters.
                  Redundancy ensures that your storage account meets its
                  availability and durability targets even in the face of
                  failures. Redundancy in Azure Storage ensures that data is
                  <strong>protected</strong> from planned and unplanned events,
                  providing high availability and durability even in the event
                  of hardware failures, outages, or disasters.
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference:</strong>
                  <a
                    href="https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy"
                    >https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/3-redundancy</a
                  >
                </p>
              </div>
</details>

---

### 41 . Select the option that is FALSE&nbsp;for Resource Groups

- [ ] A resource can only belong to one resource group
- [ ] Resources may be moved from one resource group to another
- [ ] You can add or remove a resource to a resource group at any time.
- [ ] The resources in a resource group can be located in different regions than the resource group.
- [ ] You can deploy up to 800 instances of a resource type in each resource group.
- [x] Resource groups can be nested


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  Resource groups can't be <strong>nested</strong>, i.e, a
                  resource group <code>cannot</code> exist inside another
                  resource group. It is however possible is to link resources
                  from other resource groups within a resource group.
                </p>
                <p><br /></p>
                <p>
                  <strong
                    >From the official documentation (amazing summary, please do
                    read) -
                  </strong>
                </p>
                <p><br /></p>
                  <img
                    src="https://github.com/user-attachments/assets/e6f69748-b2bb-4db6-afc1-bc71e89691e6" />
                </p>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal"
                    >https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal</a
                  >
                </p>
              </div>
</details>

---

### 42 . The Azure ________ is a fully managed Platform as a Service (PaaS) that provides a runtime environment for hosting, deploying, and scaling applications

- [ ] Azure Logic Apps
- [ ] Azure Advisor
- [ ] Azure Front Door
- [x] Azure App Service


<details>
  <summary>Explanation</summary>
  <br/>
  <div>
                <p>
                  The <strong>Azure App Service</strong> is the correct answer
                  and is a fully managed Platform as a Service (PaaS) that
                  provides a runtime environment for hosting, deploying, and
                  scaling applications.
                </p>
                <p>
                  Azure App Service supports a variety of programming languages,
                  including .NET, Java, Node.js, Python, and PHP, among others.
                  It also provides built-in support for popular content
                  management systems like WordPress and Drupal, and integrates
                  with Azure DevOps for streamlined deployment and continuous
                  integration/continuous deployment (CI/CD).
                </p>
                <p><br /></p>
                <p>Other Options:</p>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Azure Logic Apps</strong> is designed more for
                      workflow automation and integration, and does not provide
                      a runtime environment for hosting and deploying
                      applications. While it is possible to use Azure Logic Apps
                      to trigger actions in response to events in Azure App
                      Service (for example, deploying a new version of an
                      application), it is not a direct replacement for Azure App
                      Service.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Azure Advisor</strong> is a valuable tool for
                      optimizing Azure resources, it is not a fully managed
                      Platform as a Service (PaaS) like Azure App Service. Azure
                      Advisor does not provide a runtime environment for
                      hosting, deploying, and scaling applications, and it does
                      not support a variety of programming languages.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <ul>
                  <li>
                    <p>
                      <strong>Azure Front Door</strong> is a useful service for
                      load balancing and routing traffic, it is not a fully
                      managed Platform as a Service (PaaS) like Azure App
                      Service. Azure Front Door does not provide a runtime
                      environment for hosting, deploying, and scaling
                      applications, and it does not support a variety of
                      programming languages.
                    </p>
                  </li>
                </ul>
                <p><br /></p>
                <p>
                  <strong>Reference: </strong
                  ><a
                    href="https://learn.microsoft.com/en-us/azure/app-service/overview"
                    >https://learn.microsoft.com/en-us/azure/app-service/overview</a
                  >
                </p>
              </div>
</details>

---

### 43 . _______ is capable of sending encrypted traffic between an Azure virtual network and an on-premises location over the public Internet.

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---


### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

### question

- [ ] option 1
- [ ] option 2
- [ ] option 3
- [ ] option 4


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
            </td>
        </tr>
    </table>
</details>

---

