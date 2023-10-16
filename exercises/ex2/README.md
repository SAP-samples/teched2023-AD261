# Exercise 2 - Export content using Content Agent service

Use the standardized tool “Content Agent” to select desired contents across BTP application and export it using Cloud Transport Management service. The goal is to create a transport request using TMS. 

1. Launch [Content Agent UI](https://ad261-001-0q6x29xc.content-agent.cfapps.eu10.hana.ondemand.com/) from DEV account AD261-001. The UI loads with Overview page where you can view active content types and activities performed and available content resources. 
</br><img width="500" alt="image" src="images/launchCASUI.png">

2. Go To Content Types Page and check the status of Content Types. Since the status is Active, you would be able to perform content operations for that content type in this account.
</br><img width="500" alt="image" src="images/CAS-Content-Types.png">

3. Navigate To Content Resources and explore the available content coming from across SAP BTP applications.
View the metadata and general information available for different content resources. 
</br><img width="500" alt="image" src="images/Content-resources.png">

4. Start the export step by clicking on “Export” icon from left hand side menu.
Select multiple contents from different content types as shown below in the table. You can use the filters for Content Type. After selection proceed to Step 2.
    | Content Type   | Content Name  |
	| -------------  | ------------- |
	| Cloud Integration   |SAP Responsible Design and Production Integration with SAP ERP.ad261.0012
	| SAP API Management  |  DevPortal_Application_CF_2_0  
	| Role Collection  |  Role Collection for Content Export | 
	
<br/> <img width="500" alt="image" src="images/export.png">

5. Since these content types do not have any dependencies, you observe an empty list. Skip this optional step to add dependencies and proceed to Step 3.
</br><img width="500" alt="image" src="images/Depedencies.png">

6.	Select Export Mode as “SAP Cloud Transport Management” and enter Description “Teched Demo Transport for AD261-XXX”. Proceed to Step 4.
for example “Teched  Demo Transport for AD261-001”. 
</br><img width="500" alt="image" src="images/ExportMode.png">

7. You would now be able to review all the choices you made about the content and transport. Proceed to Step 5. This would now start the export in the background and display logs and progress.
</br><img width="500" alt="image" src="images/CASExportReview.png">

8. Navigate to the page from the menu in the left.
</br><img width="500" alt="image" src="images/Export-Activities-Performed.png">

9. Check the logs for the last activity by clicking on Logs icon
</br><img width="500" alt="image" src="images/ActivityLogs.png">

10.	Check the content information and transport info by clicking on the info icon.
</br><img width="500" alt="image" src="images/ActivitiesTransportInfo.png">

## Summary

You've now successfully created a transport request in Cloud Transport Management service.
Continue to [Exercise 3 - Deploy to TEST using features in Cloud ALM ](../ex3/README.md)
