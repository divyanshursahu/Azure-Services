### Azure Monitor key capabilities

Azure Monitor provides you with a comprehensive solution for collecting, analyzing, and responding to telemetry data from your on-premises and cloud environments. The service features help you understand how your applications are performing. You can use Azure Monitor to proactively identify issues that affect your apps and resources, and take action to maximize their availability and performance.

![image](https://github.com/divyanshursahu/Azure-Services/assets/96013623/57a415d0-be8c-468d-87ff-abf116bc2cf5)

### Azure Monitor provides features and capabilities in three areas:

- **Monitor and visualize metrics:** Azure Monitor gathers numerical metric values from your Azure resources according to your preferences. Azure Monitor offers different methods for viewing your metric data to help you understand the health, operation, and performance of your system.

- **Query and analyze logs:** Azure Monitor Logs (Log Analytics) generates activity logs, diagnostic logs, and telemetry information from your monitoring solutions. The service provides analytics queries that you can use to help with troubleshooting and visualizations of your log data.

- **Set up alerts and actions:** Azure Monitor lets you set up alerts for your gathered data to notify you when critical conditions arise. You can configure actions based on the alert conditions, and take automated corrective steps based on triggers from your metrics or logs.

The following diagram provides a high-level view of how Azure and Azure Monitor work together to provide you with a robust monitoring and diagnostics solution.

![image](https://github.com/divyanshursahu/Azure-Services/assets/96013623/8d6373f8-4e79-4390-bfd5-efa45d70a87e)

- The monitoring and diagnostic services offered in Azure are divided into broad **categories** such as Core, Application, Infrastructure, and Shared Capabilities.

- Data stores in Azure Monitor hold your metrics and logs. [Azure Monitor Metrics](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/data-platform-metrics) and [Azure Monitor Logs](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/data-platform-logs) are the two base types of data used by the service.

- Various **monitoring sources** provide Azure Monitor with the metrics and logs data to analyze. These sources can include your Azure subscription and tenant, your Azure service instances, your Azure resources, data from your applications, and more.

- [Azure Monitor Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview) performs different functions with the collected data, including analysis, alerting, and streaming to external systems.

  - **Get insights:** Access the Azure Application Insights extension to Azure Monitor to use the Application Performance Monitoring (APM) features. You can use APM tools to monitor your application performance and gather trace logging data. Application Insights are available for many Azure services, such as Azure Virtual Machines and Azure Virtual Machine Scale Sets, Azure Container Instances, Azure Cosmos DB, and Azure IoT Edge.

  - **Visualize:** Utilize the many options in Azure Monitor for viewing and interpreting your gathered metrics and logs. You can use Power BI with the Azure Workbooks feature of Azure Monitor and access configurable dashboards and views.

  - **Analyze:** Work with Azure Monitor Logs (Log Analytics) in the Azure portal to write log queries for your data. You can interactively analyze your log data by using Azure Monitor Metrics and the powerful analysis engine.

  - **Respond:** Set up log alert rules in Azure Monitor to receive notifications about your application performance. You can configure the service to take automated action when the results of your queries and alerts match certain conditions or results.

  - **Integrate:** Ingest and export log query results from the Azure CLI, Azure PowerShell cmdlets, and various APIs. Set up automated export of your log data to your Azure Storage account or Azure Event Hubs. Build workflows to retrieve your log data and copy to external locations with Azure Logic Apps.
 
All data collected by Azure Monitor fits into one of two fundamental types, **metrics** and **logs**:

**Metrics** are numerical values that describe some aspect of a system at a particular point in time. Metrics are lightweight and capable of supporting near real-time scenarios.

**Logs** contain different kinds of data organized into records with different sets of properties for each type. Data like events and traces are stored as logs along with performance data so all the data can be combined for analysis.

  
