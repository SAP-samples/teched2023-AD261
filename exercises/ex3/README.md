# Exercise 3 - Deploy to TEST using features in Cloud ALM 

To use better traceability option with regards to changes pushed in the transport, feature can be used to track deployment status following change management policies of moving changes through pre-defined stages in auditable manner. The goal here is to assign the transport request in Cloud ALM and deploy content based on change workflow. 


1. Navigate to [SAP Cloud ALM UI](https://ad261-calm-h7f2r9xc.eu10.alm.cloud.sap/) and select the feature you created "Feature AD261-XXX" and click on Edit.
</br><img width="500" alt="image" src="images/ALM-Features-Edit.png">

2. Edit the feature and click on Assign under Transport. Choose the Transport Request with description that contains your user as suffix, “Teched Demo Transport for AD261-XXX ”. 
</br><img width="500" alt="image" src="images/ALM-edit-feature.png">

3. Select the transport request you created "Teched  Demo Transport for AD261-XXX" and click on Assign
</br><img width="500" alt="image" src="images/ALM-assign-TR.png">

4. Save and close
</br><img width="500" alt="image" src="images/ALM-Feature-Save.png">

5. To deploy the changes in the TEST landscape you can use Cloud ALM feature and Deploy the transport request "Teched  Demo Transport for AD261-XXX".
</br><img width="500" alt="image" src="images/ALM-deploy-tr.png">
</br><img width="500" alt="image" src="images/ALM-Deployment-scheduled.png">

6.	After the status shows “Deployed in TEST”, change status from Implementation to testing.
</br><img width="500" alt="image" src="images/ALM-handover-to-Testing.png">

7.	Show Deployment Status in Feature Traceability. Explore the different options and filters in Feature traceability. End users can use this view to decide on what all features should be released to production. 
Navigate to Features Overview and select “Analytics.”
</br><img width="500" alt="image" src="images/ALM-analytics.png">
</br><img width="500" alt="image" src="images/ALM-FeatureTrace.png">



## Summary

You've now deployed the changes to TEST system. Now the different Integration and Acceptance tests can be performed on the Test tenant.

Continue to - [Exercise 4 - Deploy to Production using Cloud Transport Management](../ex4/README.md)
