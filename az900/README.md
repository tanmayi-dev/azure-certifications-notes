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
            <th>Azure Service Health</th>
        </tr>
        <tr>
            <td>
              <p>correct answer</p>
              <p>Azure Service Health is the correct choice as it specifically provides information about Azure service incidents, planned maintenance, and can notify users of issues via Email, SMS, and push notifications. It helps users stay informed about the status of Azure services they are using.</p>
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

### How does Defender for Cloud contribute to the security of Azure-native services?

- [ ] By enforcing access controls on physical hardware.
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
            <th>By enforcing access controls on physical hardware.</th>
        </tr>
        <tr>
            <td>Defender for Cloud does not enforce access controls on physical hardware. Instead, it focuses on securing Azure-native services and resources within the Azure cloud environment.</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Header 1</th>
        </tr>
        <tr>
            <td>Data 1</td>
        </tr>
    </table>
    <table>
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
