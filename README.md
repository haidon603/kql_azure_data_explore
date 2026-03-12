KQL Queries to aid in security investigations within Azure Data Explorer. Consider adding these queries to dashboards so that you can continuously monitor and hunt. Here are some dashboard examples.

Join EDR DNS events with Proxy events to determine if the request was allowed.
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/kql_join.png)

Intune Analysis
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/intune1.png)
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/intune2.png)
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/intune3.png)


Search an IoC across all databases in the cluster.
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/IoC_Landing_Page.png)

![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/IoC_Sample_Search.png)

User Agent Analysis for potential password spraying. Notice anything abnormal about the Go user agent?
![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/ADX_dashboard_User_Agent_Analysis_for_Password_Spraying_2.png)

![Alt text](https://github.com/haidon603/kql_azure_data_explore/blob/main/ADX_dashboard_User_Agent_Analysis_for_Password_Spraying_1.png)




