# Practice Questions

## Domain : Describe Azure Architecture and Services

### Which of the following is an accurate description of Azure ExpressRoute?

- [ ] A service that provides backup and disaster recovery solutions for Azure resources.
- [ ] A service that enables you to manage and monitor Azure resources from a single, unified dashboard.
- [ ] A service that allows you to connect your on-premises infrastructure to Azure over the public internet.
- [x] A service that provides dedicated, private network connectivity between your on-premises infrastructure and Azure datacenters.

<details>
<summary>Explanation</summary>
  <br/>
    <a href="https://learn.microsoft.com/en-us/azure/expressroute/expressroute-introduction">Reference Link</a>
  <br/>
  <br/>
    <table>
        <tr>
            <th>A service that provides backup and disaster recovery solutions for Azure resources.</th>
        </tr>
        <tr>
            <td>Backup and disaster recovery solutions for Azure resources are typically provided by services like Azure Backup and Azure Site Recovery, not Azure ExpressRoute. Azure ExpressRoute is focused on network connectivity rather than data protection.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>A service that enables you to manage and monitor Azure resources from a single, unified dashboard.</th>
        </tr>
        <tr>
            <td>Managing and monitoring Azure resources from a single, unified dashboard is a function of Azure Monitor and Azure Management Portal, not Azure ExpressRoute. Azure ExpressRoute is specifically designed for establishing private network connections between on-premises infrastructure and Azure.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>A service that allows you to connect your on-premises infrastructure to Azure over the public internet.</th>
        </tr>
        <tr>
            <td>Connecting your on-premises infrastructure to Azure over the public internet is typically done through VPN gateways, not Azure ExpressRoute. Azure ExpressRoute provides a dedicated, private network connection for more secure and reliable connectivity.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>A service that provides dedicated, private network connectivity between your on-premises infrastructure and Azure datacenters.</p>
            </th>
        </tr>
        <tr>
            <td>Azure ExpressRoute is a service that offers dedicated, private network connectivity between your on-premises infrastructure and Azure datacenters. This allows for a more secure and reliable connection compared to using the public internet.</td>
        </tr>
    </table>
      <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><b>Azure ExpressRoute</b> is a service that provides dedicated, private network connectivity between your on-premises infrastructure and Azure datacenters. This allows you to extend your on-premises network into Azure, providing a more secure and reliable connection than the public internet.</p>
              <li><b>A service that allows you to connect your on-premises infrastructure to Azure over the public internet:</b>This is incorrect because Azure ExpressRoute does not use the public internet for connectivity. Instead, it provides a private, dedicated connection.</li>
              <li><b>A service that provides backup and disaster recovery solutions for Azure resources:</b>This is incorrect because Azure ExpressRoute is not specifically designed for backup and disaster recovery. While it can be used in conjunction with these solutions, it is primarily used for private connectivity.</li>
              <li><b>A service that enables you to manage and monitor Azure resources from a single, unified dashboard:</b>This is incorrect because Azure ExpressRoute is not a management or monitoring tool for Azure resources. It is a connectivity service that enables you to extend your on-premises network into Azure.</li>
            </td>
        </tr>
    </table>
</details>

---

### How does Defender for Cloud contribute to the security of Azure-native services?

- [ ] By enforcing access controls on physical hardware.
- [ ] By automatically deploying Log Analytics agents to Azure machines.
- [ ] By focusing solely on Azure App Service protection.
- [x] By natively integrating with Azure services to provide monitoring and protection.

<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/9-describe-microsoft-defender-for-cloud">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>By enforcing access controls on physical hardware.</th>
        </tr>
        <tr>
            <td>Defender for Cloud does not enforce access controls on physical hardware. Instead, it focuses on securing Azure-native services and resources within the Azure cloud environment.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>By automatically deploying Log Analytics agents to Azure machines.</th>
        </tr>
        <tr>
            <td>Defender for Cloud does not automatically deploy Log Analytics agents to Azure machines. While Log Analytics may be used for monitoring and analysis, Defender for Cloud itself natively integrates with Azure services to provide security monitoring and protection.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>By focusing solely on Azure App Service protection.</th>
        </tr>
        <tr>
            <td>Defender for Cloud does not solely focus on Azure App Service protection. It provides security monitoring and protection for a wide range of Azure services beyond just Azure App Service.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p><b>By natively integrating with Azure services to provide monitoring and protection.</b></p>
              </th>
        </tr>
        <tr>
            <td>This choice is correct because Defender for Cloud natively integrates with Azure services to provide monitoring and protection. It leverages Azure's capabilities to secure Azure-native services and resources, offering comprehensive security features within the Azure environment.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              Defender for Cloud, being an Azure-native service, natively integrates with Azure services, monitoring and protecting them without requiring additional deployment. This integration enhances the security posture of Azure resources.
            </td>
        </tr>
    </table>
</details>


---

### Is an internet connection necessary for using cloud computing?

- [ ] Yes
- [x] No


<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://learn.microsoft.com/en-us/azure-stack/operator/azure-stack-overview?view=azs-2206">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Yes</th>
        </tr>
        <tr>
            <td>This choice is incorrect because an internet connection is not always necessary for using cloud computing. While an internet connection is typically required to access cloud services and resources, some cloud computing models, such as private cloud or hybrid cloud, can be used within a closed network environment without internet connectivity.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>No</p>
            </th>
        </tr>
        <tr>
            <td>This choice is correct because an internet connection is not a strict requirement for using cloud computing. While many cloud services and resources are accessed over the internet, there are scenarios where cloud computing can be utilized in offline or restricted network environments, making an internet connection not necessary for all cloud computing use cases.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>The answer is no. Cloud computing services can be used over the internet, but they can also be used through private networks or dedicated connections, such as Azure ExpressRoute, which provides a dedicated, private network connection between on-premises infrastructure and Azure data centers. Some cloud services can also be accessed offline or through local networks.</p>
              <p>For example, Azure Stack is a hybrid cloud solution that allows you to use Azure services on-premises, without an internet connection. This can be useful for organizations that have limited or unreliable internet connectivity but still want to take advantage of the benefits of cloud computing.</p>
              <p>Similarly, some cloud providers offer edge computing solutions that allow you to run cloud workloads on devices located at the edge of the network, such as in a factory or remote location, without needing a constant internet connection.</p>
              <p>In general, however, most cloud services do require an internet connection to access and use them. This is because the underlying infrastructure and resources that support these services are typically hosted in data centers that are connected to the internet.</p>
            </td>
        </tr>
    </table>
</details>

---

### What is the significance of implementing security controls at the "data" layer in the defense-in-depth model?

- [x] It protects sensitive data and ensures confidentiality, integrity, and availability.
- [ ] It ensures the physical security of data storage.
- [ ] It prevents network-based attacks against resources.
- [ ] It reduces the impact of denial of service (DoS) attacks.


<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/8-describe-defense-depth">Reference</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>It protects sensitive data and ensures confidentiality, integrity, and availability.</p>
            </th>
        </tr>
        <tr>
            <td>The significance of implementing security controls at the "data" layer in the defense-in-depth model is to protect sensitive data and ensure confidentiality, integrity, and availability. These controls help safeguard data from unauthorized access, modification, or disclosure, thereby maintaining the overall security of the organization's data assets.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>It ensures the physical security of data storage.</th>
        </tr>
        <tr>
            <td>Implementing security controls at the "data" layer focuses on protecting the data itself rather than the physical security of data storage. Physical security measures, such as access controls and surveillance, are more relevant to the physical security of data storage locations.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>It prevents network-based attacks against resources.</th>
        </tr>
        <tr>
            <td>Implementing security controls at the "data" layer does not directly prevent network-based attacks against resources. Network-based attacks are typically mitigated at the network layer through measures such as firewalls, intrusion detection systems, and network segmentation.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>It reduces the impact of denial of service (DoS) attacks.</th>
        </tr>
        <tr>
            <td>While implementing security controls at the "data" layer may indirectly reduce the impact of denial of service (DoS) attacks by ensuring data availability, the primary purpose of these controls is to protect sensitive data and maintain its confidentiality, integrity, and availability.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>The "data" layer in the defense-in-depth model is responsible for controlling access to business and customer data. It ensures that sensitive data is properly secured and complies with regulatory requirements, ensuring its confidentiality, integrity, and availability.</p>
              <p><b>Reference : </b><a href="https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/8-describe-defense-depth">https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/8-describe-defense-depth</a></p>
            </td>
        </tr>
    </table>
</details>

---

### Which of the following Azure storage solutions meets ALL the following requirements:

1) The ability to handle unstructured data (document, graph, key-value)

2) Automatically index all data, regardless of the data model.

3) Multi-region writes and data distribution to any Azure region.

- [ ] Azure Files
- [ ] Azure Cache for Redis
- [ ] Azure SQL Databases
- [ ] Azure SQL Edge
- [x] Azure Cosmos DB
- [ ] Azure Database for MariaDB


<details>
  <summary>Explanation</summary>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Azure Files</th>
        </tr>
        <tr>
            <td>Azure Files do not meet all the specified requirements. While they can handle unstructured data, they do not automatically index all data regardless of the data model. They also do not offer multi-region writes and data distribution to any Azure region, making them an incorrect choice for the given requirements.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Cache for Redis</th>
        </tr>
        <tr>
            <td>Azure Cache for Redis does not meet all the specified requirements. While it can handle unstructured data, it does not automatically index all data regardless of the data model. It also does not offer multi-region writes and data distribution to any Azure region, making it an incorrect choice for the given requirements.
</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure SQL Databases</th>
        </tr>
        <tr>
            <td>Azure SQL Databases do not meet all the specified requirements. While they can handle unstructured data, they do not automatically index all data regardless of the data model. They also do not offer multi-region writes and data distribution to any Azure region, making them an incorrect choice for the given requirements.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure SQL Edge</th>
        </tr>
        <tr>
            <td>Azure SQL Edge does not meet all the specified requirements. While it can handle unstructured data, it does not automatically index all data regardless of the data model. It also does not offer multi-region writes and data distribution to any Azure region, making it an incorrect choice for the given requirements.</td>
        </tr>
    </table>
      <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Azure Cosmos DB</p>
            </th>
        </tr>
        <tr>
            <td>Azure Cosmos DB is the correct choice as it meets all the specified requirements. It can handle unstructured data such as documents, graphs, and key-value pairs. It automatically indexes all data regardless of the data model. Additionally, it offers multi-region writes and data distribution to any Azure region, making it a suitable choice for the given requirements.</td>
        </tr>
    </table>
      <table>
        <tr>
            <th>Azure Database for MariaDB</th>
        </tr>
        <tr>
            <td>Azure Database for MariaDB does not meet all the specified requirements. While it can handle unstructured data, it does not automatically index all data regardless of the data model. It also does not offer multi-region writes and data distribution to any Azure region, making it an incorrect choice for the given requirements.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>Today's applications are required to be highly responsive and always online. To achieve low latency and high availability, instances of these applications need to be deployed in datacenters that are close to their users. Applications need to respond in real time to large changes in usage at peak hours, store ever increasing volumes of data, and make this data available to users in milliseconds.</p>
              <p><b>Azure Cosmos DB </b>is Microsoft's globally distributed, multi-model database service. With the click of a button, Cosmos DB enables you to elastically and independently scale throughput and storage across any number of Azure regions worldwide. You can elastically scale throughput and storage, and take advantage of fast, single-digit-millisecond data access using your favorite API including: SQL, MongoDB, Cassandra, Tables, or Gremlin. Cosmos DB provides comprehensive <a href="https://azure.microsoft.com/support/legal/sla/cosmos-db/v1_3/">service level agreements</a> (SLAs) for throughput, latency, availability, and consistency guarantees, something no other database service offers.</p>
              <p>Azure Cosmos DB is a great way to store unstructured and JSON data. Combined with Azure Functions, Cosmos DB makes storing data quick and easy with much less code than required for storing data in a relational database.</p>
              <img src="https://github.com/user-attachments/assets/46ff3f40-a67e-4fe8-859e-e0492b5d6af3" />
              <br/>
              <br/>
              <p><b>References : </b></p>
              <a href="https://docs.microsoft.com/en-us/azure/cosmos-db/introduction">https://docs.microsoft.com/en-us/azure/cosmos-db/introduction</a>
              <a href="https://docs.microsoft.com/en-us/azure/azure-functions/functions-integrate-store-unstructured-data-cosmosdb?tabs=csharp">https://docs.microsoft.com/en-us/azure/azure-functions/functions-integrate-store-unstructured-data-cosmosdb?tabs=csharp</a>
            </td>
        </tr>
    </table>
</details>

---

### ________________  is the mission-critical cloud, delivering breakthrough innovation to US government customers and their partners. Only US federal, state, local, and tribal governments and their partners have access to this dedicated instance, with operations controlled by screened US citizens.

- [x] Azure Government
- [ ] Azure United States
- [ ] Azure US
- [ ] Azure Nation


<details>
  <summary>Explanation</summary>
  <br/>
  <p><b>Reference : </b><a href="https:///en-us/global-infrastructure/government/get-started/">https:///en-us/global-infrastructure/government/get-started/</a></p>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <b>Azure Government</b> - It is the mission-critical cloud, delivering breakthrough innovation to US <b>government</b> customers and their partners. Only US federal, state, local, and tribal <b>governments</b> and their partners have access to this dedicated instance, with operations controlled by screened US citizens.
            </td>
        </tr>
    </table>
</details>

---

### How does the defense-in-depth model enhance cybersecurity compared to relying solely on perimeter security?

- [ ] It reduces the need for user authentication.
- [ ] It eliminates the need for regular security updates.
- [x] It provides protection against both external and internal threats.
- [ ] It isolates the network from the internet entirely.

<details>
  <summary>Explanation</summary>
  <br/>
  <p><b>Reference:</b><a href="https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/">https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/</a></p>
  <br/>
  <br/>
  <table>
        <tr>
            <th>It reduces the need for user authentication.</th>
        </tr>
        <tr>
            <td>The defense-in-depth model does not reduce the need for user authentication; in fact, it emphasizes the importance of multi-factor authentication and other security measures to protect against unauthorized access.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>It eliminates the need for regular security updates.</th>
        </tr>
        <tr>
            <td>The defense-in-depth model does not eliminate the need for regular security updates. In fact, it emphasizes the importance of keeping systems and software up to date with the latest security patches to address vulnerabilities and protect against emerging threats. Regular security updates are a critical component of a comprehensive cybersecurity strategy.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>It provides protection against both external and internal threats.</p>
            </th>
        </tr>
        <tr>
            <td>The defense-in-depth model provides protection against both external threats, such as cyberattacks from outside the organization, and internal threats, such as insider threats or accidental data breaches. By implementing multiple layers of security controls, organizations can better defend against a wide range of cybersecurity risks.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>It isolates the network from the internet entirely.</th>
        </tr>
        <tr>
            <td>While the defense-in-depth model may include network segmentation to isolate critical assets, it does not completely isolate the network from the internet. It focuses on creating multiple layers of security controls to protect against various types of threats.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>The defense-in-depth model focuses on multiple layers of security, including internal defenses. This strategy provides safeguards against both external threats (outside attackers) and internal threats (compromised insiders).</p>
              <p>The remaining options don't make any sense and rather <b>reduce</b> the security configuration.</p>
              <p><b>Reference:</b><a href="https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/">https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/</a></p>
            </td>
        </tr>
    </table>
</details>

---


## Domain : Describe Azure management and governance

### Which of the following services provides information about Azure service incidents, planned maintenance and can notify you of issues via Email, SMS and push notifications?

- [ ] Azure Monitor
- [ ] Azure Initiatives
- [ ] Azure Trust Portal
- [x] Azure Service Health
      
<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://azure.microsoft.com/en-us/features/service-health/#features">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Azure Monitor</th>
        </tr>
        <tr>
            <td>Azure Monitor is a service that provides monitoring and analytics for applications and resources in Azure. While it can help track performance and diagnose issues, it does not specifically provide information about service incidents, planned maintenance, or notifications for issues via Email, SMS, and push notifications.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Initiatives</th>
        </tr>
        <tr>
            <td>Azure Initiatives are sets of policies, initiatives, and definitions that help manage and enforce compliance in Azure. They are not related to providing information about service incidents, planned maintenance, or notifications for issues via Email, SMS, and push notifications.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Trust Portal</th>
        </tr>
        <tr>
            <td>Azure Trust Portal is a portal that provides information about compliance, privacy, and security in Azure. It does not provide information about service incidents, planned maintenance, or notifications for issues via Email, SMS, and push notifications.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Azure Service Health</p>
            </th>
        </tr>
        <tr>
            <td>Azure Service Health is the correct choice as it specifically provides information about Azure service incidents, planned maintenance, and can notify users of issues via Email, SMS, and push notifications. It helps users stay informed about the status of Azure services they are using.
            </td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <b>Azure Service Health</b> notifies you about Azure service incidents and planned maintenance so you can take action to mitigate downtime. We can configure customizable cloud alerts and use your personalized dashboard to analyze health issues, monitor the impact to your cloud resources, get guidance and support, and share details and updates.
              <br/>
              <br/>
              <img src="https://github.com/user-attachments/assets/0612386b-4aa5-4f6c-bce7-186267716cb4" />
            </td>
        </tr>
    </table>
</details>


---

### A resource group can contain resources from multiple Azure regions.

- [x] Yes
- [ ] No


<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Yes</th>
        </tr>
        <tr>
            <td>Yes, a resource group in Azure can contain resources from multiple Azure regions. Resource groups are logical containers that hold related resources for an Azure solution. They help manage and organize resources and do not limit the resources to a specific region. This allows for flexibility in organizing resources across different regions within the same resource group.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>No</th>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><b>From the official documentation:</b></p>
              <p>Resources from multiple different regions can be placed in a resource group. The resource group only contains metadata about the resources it contains.</p>
            </td>
          <img src="https://github.com/user-attachments/assets/a6809396-af10-4220-8031-a3d4e8706077" />
        </tr>
    </table>
</details>

---

### Which of the following actions can help you reduce your Azure costs?

- [ ] Keeping all virtual machines running 24/7
- [ ] Increasing the number of virtual machines deployed
- [x] Reducing the amount of data transferred between Azure regions
- [ ] Enabling automatic scaling for all virtual machines


<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://learn.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Keeping all virtual machines running 24/7</th>
        </tr>
        <tr>
            <td>Keeping all virtual machines running 24/7 will result in higher costs as you will be paying for the compute resources continuously. It is recommended to utilize cost-saving measures such as scheduling virtual machines to shut down during off-peak hours or using auto-scaling to adjust resources based on demand.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Increasing the number of virtual machines deployed</th>
        </tr>
        <tr>
            <td>Increasing the number of virtual machines deployed will actually lead to higher Azure costs as you will be paying for more resources. It is important to right-size your resources and only deploy the necessary number of virtual machines to avoid unnecessary expenses.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Reducing the amount of data transferred between Azure regions</p>
            </th>
        </tr>
        <tr>
            <td>Reducing the amount of data transferred between Azure regions can help lower costs as data transfer fees can add up quickly. By optimizing your data transfer patterns and minimizing unnecessary data movement, you can effectively reduce your Azure costs.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Enabling automatic scaling for all virtual machines</th>
        </tr>
        <tr>
            <td>Enabling automatic scaling for all virtual machines can help optimize costs by automatically adjusting the number of virtual machines based on demand. This ensures that you are only paying for the resources you need at any given time, reducing costs associated with over-provisioning.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>Reducing the amount of data transferred between Azure regions can help reduce costs by minimizing data egress charges.</p>
              <ul>
                Other options:
                <li><b>Deploying more virtual machines:</b> This can actually increase costs if they are not utilized efficiently.</li>
                <li><b>Enabling automatic scaling:</b> This can help optimize resource usage and reduce costs, but it depends on the specific workload and usage patterns.</li>
                <li><b>Keeping virtual machines running 24/7:</b> This can result in unnecessary costs, especially if they are not utilized all the time. It is recommended to use automation to start and stop VMs based on usage patterns.</li>
              </ul>
            </td>
        </tr>
    </table>
</details>

---

### Which of the following factors influence the cost of Azure resources? (Select all that apply)

- [x] Resource type
- [x] Consumption
- [ ] Maintenance
- [x] Geography


<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/2-describe-factors-affect-costs-azure">Reference Link</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Resource Type</p>
            </th>
        </tr>
        <tr>
            <td>The type of Azure resource being used directly impacts its cost. Different resource types have varying pricing structures and cost models, so choosing the right resource type is essential for managing costs effectively.
            </td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Consumption</p>
            </th>
        </tr>
        <tr>
            <td>Consumption refers to the amount of usage or resources consumed within Azure. The more resources you use or the higher the usage, the higher the cost will be. Monitoring and optimizing consumption can help control costs.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Maintenance</th>
        </tr>
        <tr>
            <td>Maintenance costs are not directly related to the cost of Azure resources. While maintenance activities may incur additional costs, they are not a factor that directly influences the cost of using Azure resources.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Geography</p>
            </th>
        </tr>
        <tr>
            <td>The geographic location where Azure resources are deployed can impact their cost. Different regions may have different pricing for resources, and data transfer costs can vary based on the distance between regions. Choosing the right geography for resource deployment can help optimize costs.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              The correct answers are - <b>Resource type, Consumption, and Geography.</b> These factors influence the cost of Azure resources. Maintenance, on the other hand, is an important aspect of managing resources to control costs but does not directly influence the cost of the resources themselves.
            </td>
        </tr>
    </table>
</details>

---

### How can you determine the estimated monthly cost of an Azure service or resource?

- [ ] By checking the current Azure Marketplace pricing
- [ ] By contacting Microsoft customer support
- [x] By using the Azure Pricing Calculator
- [ ] By analyzing the usage data of the resource


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>By checking the current Azure Marketplace pricing</th>
        </tr>
        <tr>
            <td>Checking the current Azure Marketplace pricing can give you an idea of the pricing for different services and resources available, but it may not provide an accurate estimate of the monthly cost for a specific service or resource based on your usage requirements. The Azure Pricing Calculator is a more suitable tool for this purpose.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>By contacting Microsoft customer support</th>
        </tr>
        <tr>
            <td>Contacting Microsoft customer support is not the appropriate method to determine the estimated monthly cost of an Azure service or resource. Customer support may assist with other inquiries or issues, but they do not provide cost estimates for Azure services.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>By using the Azure Pricing Calculator</p>
            </th>
        </tr>
        <tr>
            <td>Using the Azure Pricing Calculator is the correct way to determine the estimated monthly cost of an Azure service or resource. The calculator allows you to input the details of the service or resource you plan to use, such as region, type, and quantity, and provides an estimate of the monthly cost based on the current pricing information.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>By analyzing the usage data of the resource</th>
        </tr>
        <tr>
            <td>Analyzing the usage data of the resource may give insights into the actual usage patterns and costs incurred, but it does not provide an estimated monthly cost for an Azure service or resource. The estimated cost is based on the pricing information provided by Azure.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><b>The Azure Pricing Calculator </b>is a free tool that can be used to estimate the monthly cost of Azure services and resources based on factors such as region, usage, and quantity. It allows users to select specific Azure services and configurations and provides an estimated monthly cost based on the chosen parameters.</p>
              <p>Other options:</p>
              <p><b>By contacting Microsoft customer support :</b> This is incorrect because contacting Microsoft customer support is not a reliable method to determine the estimated monthly cost of an Azure service or resource.</p>
              <p><b>By analyzing the usage data of the resource:</b> This is incorrect because analyzing the usage data of a resource can help in optimizing costs but it does not provide an estimated monthly cost.</p>
              <p><b>By checking the current Azure Marketplace pricing:</b> This is incorrect because checking the current Azure Marketplace pricing does not necessarily provide the estimated monthly cost of a particular service or resource.</p>
              <p><b>Reference:</b><a href="https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/plan-manage-costs">https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/plan-manage-costs</a></p>
            </td>
        </tr>
    </table>
</details>

---

### What Azure service provides recommendations to optimize your cloud spending based on your usage patterns?

- [ ] Azure Policy
- [ ] Azure Advisor
- [ ] Azure Monitor
- [x] Azure Cost Management and Billing


<details>
  <summary>Explanation</summary>
  <br/>
  <p><b>Reference : </b><a href="https://learn.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview">https://learn.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview</a></p>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Azure Policy</th>
        </tr>
        <tr>
            <td>Azure Policy is a service that helps you enforce organizational standards and compliance controls on your Azure resources. While it is important for governance and compliance, it does not provide recommendations for optimizing cloud spending based on usage patterns.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Advisor</th>
        </tr>
        <tr>
            <td>Azure Advisor provides recommendations for improving the security, performance, and reliability of your Azure resources. While it offers valuable insights, it does not specifically focus on optimizing cloud spending based on usage patterns.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Monitor</th>
        </tr>
        <tr>
            <td>Azure Monitor is a service that provides insights into the performance and health of your Azure resources. While it helps you monitor and analyze your Azure environment, it does not specifically focus on providing recommendations to optimize cloud spending based on usage patterns.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Azure Cost Management and Billing</p>
            </th>
        </tr>
        <tr>
            <td>Azure Cost Management and Billing is the correct choice as it provides recommendations to optimize your cloud spending based on your usage patterns. It offers cost analysis, budgeting tools, and cost optimization recommendations to help you manage and optimize your Azure spending effectively.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><b>Azure Cost Management and Billing </b>is the correct answer & provides recommendations to optimize your cloud spending based on your usage patterns. The service provides insights and cost management tools to help you monitor, allocate, and optimize your cloud costs.</p>
              <ul>
                <b>Other Options:</b>
                <li><b>Azure Advisor</b> is a service that provides personalized recommendations to help you optimize your Azure resources for high availability, security, performance, and cost. Azure Advisor also provides recommendations to optimize your cloud spending, but its primary focus is on providing guidance for improving the security, reliability, and performance of your Azure resources. While it may include some cost optimization recommendations, it is not solely focused on cost management and billing like Azure Cost Management and Billing. In such questions we'll always choose the BEST choice possible.</li>
                <li><b>Azure Monitor</b> is a service that provides a single pane of glass to monitor the performance and health of your applications and infrastructure in Azure.</li>
                <li><b>zure Policy</b>A is a service that enables you to enforce governance policies for your Azure resources to ensure compliance with organizational standards and regulations.</li>
              </ul>
            </td>
        </tr>
    </table>
</details>

---

### Yes or No: Inter-Region transfer of data is always free of cost.

- [ ] Yes
- [x] No

<details>
  <summary>Explanation</summary>
  <br/>
  <p><b>Reference : </b><a href="https://azure.microsoft.com/en-us/pricing/details/bandwidth/">https://azure.microsoft.com/en-us/pricing/details/bandwidth/</a></p>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Yes</th>
        </tr>
        <tr>
            <td>Inter-Region transfer of data in Azure is not always free of cost. While there are certain scenarios where data transfer between Azure regions may be free, such as within the same region or between regions in the same geography, there are cases where charges may apply for transferring data across different regions or geographies.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              No
            </th>
        </tr>
        <tr>
            <td>The correct choice is No because inter-Region transfer of data in Azure is not always free of cost. Depending on the specific Azure services being used and the regions involved in the data transfer, charges may apply for transferring data across different regions. It is important to review the Azure pricing documentation for detailed information on data transfer costs between regions.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <b>Look at the following details from the official documentation:</b>
              <img src="https://github.com/user-attachments/assets/3de696b7-3168-4a4f-a36d-2115428c4301" />
              <img src="https://github.com/user-attachments/assets/1f9a73e4-2bc5-4238-aa2d-7c26938eef84" />
            </td>
        </tr>
    </table>
</details>

---

### Which of the following displays personalized recommendations for all your subscriptions, and you can use filters to select recommendations for specific subscriptions, resource groups, or services?

- [ ] Azure Service Health
- [x] Azure Advisor
- [ ] Azure Monitor
- [ ] Azure Arc


<details>
  <summary>Explanation</summary>
  <br/>
  <p><b>Reference: </b><a href="https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/2-identify-product-options">https://docs.microsoft.com/en-ca/learn/modules/monitoring-fundamentals/2-identify-product-options</a></p>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Azure Service Health</th>
        </tr>
        <tr>
            <td>Azure Service Health focuses on providing information about the health of Azure services and regions, including ongoing incidents and planned maintenance. It does not offer personalized recommendations or the ability to filter recommendations for specific subscriptions, resource groups, or services.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Azure Advisor</p>
            </th>
        </tr>
        <tr>
            <td>Azure Advisor is the correct choice as it provides personalized recommendations for all your subscriptions. It allows you to use filters to select recommendations for specific subscriptions, resource groups, or services, making it a versatile tool for optimizing your Azure resources.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Monitor</th>
        </tr>
        <tr>
            <td>Azure Monitor is not the correct choice for this scenario. While Azure Monitor provides monitoring and insights into your Azure resources, it does not specifically offer personalized recommendations or the ability to filter recommendations for specific subscriptions, resource groups, or services.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Azure Arc</th>
        </tr>
        <tr>
            <td>Azure Arc is a tool that extends Azure management and services to any infrastructure, including on-premises, multi-cloud, and edge environments. It does not provide personalized recommendations or the ability to filter recommendations for specific subscriptions, resource groups, or services like Azure Advisor does.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><a href="https://azure.microsoft.com/services/advisor/">Azure Advisor</a> evaluates your Azure resources and makes recommendations to help improve reliability, security, and performance, achieve operational excellence, and reduce costs. Advisor is designed to help you save time on cloud optimization. The recommendation service includes suggested actions you can take right away, postpone, or dismiss.</p>
              <p>The recommendations are available via the Azure portal and the API, and you can set up notifications to alert you to new recommendations.</p>
              <p>When you're in the Azure portal, the <b>Advisor</b> dashboard displays personalized recommendations for all your subscriptions, and you can use filters to select recommendations for specific subscriptions, resource groups, or services.</p>
            </td>
        </tr>
    </table>
</details>

---

### Which of the following statements is accurate?

**If you want to migrate a website that is hosted On-Prem presently to Azure, one of the clear benefits is the Pay-As-You-Go Pricing that comes with Azure.**

- [x] The given statement is correct.
- [ ] This is not true, a website hosted on Azure will be costlier as its charged by the second.
- [ ] This is not true. You need a VPN to complete the migration which will cost a lot.
- [ ] This is not true, we first need to pay to transfer all the website data to Azure


<details>
  <summary>Explanation</summary>
  <br/>
  <a href=""></a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>The given statement is correct.</p>
            </th>
        </tr>
        <tr>
            <td>The statement is accurate because one of the benefits of migrating a website from an On-Prem environment to Azure is the Pay-As-You-Go Pricing model, which allows you to pay only for the resources you use, providing cost-efficiency and flexibility.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>This is not true, a website hosted on Azure will be costlier as its charged by the second.</th>
        </tr>
        <tr>
            <td>This explanation is incorrect as the statement in Choice A is accurate. Azure's Pay-As-You-Go Pricing model is designed to provide cost-effective pricing based on actual usage, which can be more cost-efficient compared to traditional hosting models.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>This is not true. You need a VPN to complete the migration which will cost a lot.</th>
        </tr>
        <tr>
            <td>This explanation is incorrect as the statement in Choice A is accurate. While setting up a VPN may be necessary for secure communication during migration, it is not a requirement for the Pay-As-You-Go Pricing model that Azure offers.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>This is not true, we first need to pay to transfer all the website data to Azure</th>
        </tr>
        <tr>
            <td>This explanation is incorrect as the statement in Choice A is accurate. While there may be costs associated with transferring website data to Azure, the Pay-As-You-Go Pricing model refers to the pricing structure once the website is hosted on Azure, not the initial data transfer.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>When planning to migrate a website to Azure, the Pay As you Go pricing model is a big advantage. You can even use Azure Websites to accomplish this.</p>
              <p>Azure Websites is offered in four tiers: <b>Free, Shared (Preview), Basic and Standard</b></p>
              <ul>
                <li><b>Websites Shared (Preview):</b> The price for the Shared tier during preview is <b>$0.013</b> per hour per website instance (~$10/month). This price reflects a 33% preview discount.</li>
                <li><b>Websites Basic and Standard:</b> The Basic and Standard tiers offer multiple instance sizes as well as scaling to meet changing capacity needs starting from $56 for a Basic (Single Small instance) and $75 for a Standard ( Single small instance)</li>
              </ul>
              <p>For more details on features per price tier , click <a href="https://azure.microsoft.com/en-us/pricing/details/websites/">here</a>.</p>
              <ul>
                <b>Incorrect Answers:</b>
                <li>You do not need a VPN for Azure web sites.</li>
                <li>You do not pay to transfer data into Azure web sites.</li>
                <li>You are not charged by the second.</li>
              </ul>
            </td>
        </tr>
    </table>
</details>

---


## Domain : Describe Cloud Concepts

### You are the senior architect of XYZ organization and the senior management has requested to migrate all on-prem resources to the cloud.

The requirement is that only Platform as a Service (PaaS) solutions must be used in Azure.

**Solution: To begin, you create an Azure App Service and Azure SQL databases.**

Would this meet the goal?

- [ ] No
- [x] Yes


<details>
  <summary>Explanation</summary>
  <br/>
  <br/>
  <table>
        <tr>
            <th>No</th>
        </tr>
        <tr>
            <td>This statement is incorrect. Creating an Azure App Service and Azure SQL databases meets the requirement of using Platform as a Service (PaaS) solutions in Azure. Azure App Service and Azure SQL databases are both PaaS offerings that provide managed services for web applications and relational databases, respectively. Therefore, this solution aligns with the goal of migrating on-prem resources to the cloud using PaaS solutions.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Yes</p>
            </th>
        </tr>
        <tr>
            <td>Yes, creating an Azure App Service and Azure SQL databases aligns with the requirement of using Platform as a Service (PaaS) solutions in Azure. Azure App Service is a fully managed platform for building, deploying, and scaling web apps, while Azure SQL databases provide a fully managed relational database service. Both of these services fall under the category of PaaS offerings in Azure, making this solution suitable for the migration of on-prem resources to the cloud.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p>Please always remember - Azure App Service and Azure SQL Databases are both PaaS services!</p>
              <p><b>Azure App Service </b>- Allows us to quickly build, deploy, and scale web apps created with popular frameworks such as .NET, .NET Core, Node.js, Java, PHP, Ruby, or Python, in containers or running on any operating system. It offers rigorous, enterprise-grade performance, security, and compliance requirements by using the fully managed platform for your operational and monitoring tasks.</p>
              <p><b>Reference : </b><a href="https://azure.microsoft.com/en-in/services/app-service/">https://azure.microsoft.com/en-in/services/app-service/</a></p>
              <p><b>Azure SQL Database </b>- Microsoft Azure SQL Database is a managed cloud database provided as a part of Microsoft Azure. A cloud database is a database that runs on a cloud computing platform, and access to it is provided as a service. Managed database services take care of scalability, backup, and high availability of the database.</p>
              <p><b>Reference : </b><a href="https://azure.microsoft.com/en-in/services/sql-database/">https://azure.microsoft.com/en-in/services/sql-database/</a></p>
              <p>Please refer to the image below, and make sure you remember it properly. A lot of the questions in the exam can be answered using this image alone:</p>
              <img src="https://github.com/user-attachments/assets/52cc4f79-dd49-407b-a76f-fbe7fb381eb6" />
            </td>
        </tr>
    </table>
</details>

---

### When computing and processing demand increases beyond an on-premises datacenter’s capabilities, businesses can easily use the ___________ cloud to instantly scale capacity up or down to handle excess capacity.

- [ ] Private
- [x] Public

<details>
  <summary>Explanation</summary>
  <br/>
  <a href="https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/">Reference</a>
  <br/>
  <br/>
  <table>
        <tr>
            <th>Private</th>
        </tr>
        <tr>
            <td>Private clouds, on the other hand, are dedicated cloud environments that are typically used by a single organization. While private clouds offer control and customization options, they do not provide the same level of instant scalability as public clouds. Businesses using a private cloud may face limitations when trying to quickly scale their capacity to handle excess demand beyond the capabilities of their on-premises datacenter.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>
              <p>correct answer</p>
              <p>Public</p>
            </th>
        </tr>
        <tr>
            <td>Public cloud services provide businesses with the ability to instantly scale their computing and processing capacity up or down based on demand. This scalability is achieved by leveraging the resources and infrastructure of a third-party cloud service provider, allowing businesses to quickly adapt to changing workload requirements without the need for additional on-premises hardware or infrastructure investments.</td>
        </tr>
    </table>
  <table>
        <tr>
            <th>Overall explanation</th>
        </tr>
        <tr>
            <td>
              <p><b>From the official docs:</b></p>
              <p>When computing and processing demand increases beyond an on-premises datacenter’s capabilities, businesses can use the cloud to instantly scale capacity up or down to handle excess capacity. It also allows them to avoid the time and cost of purchasing, installing, and maintaining new servers that they may not always need.</p>
              <p><b>Reference : </b><a href="https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/">https://azure.microsoft.com/en-gb/overview/what-is-hybrid-cloud-computing/</a></p>
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
</details>
