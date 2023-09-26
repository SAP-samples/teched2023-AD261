# Exercise 3 - 3.3	Deploy to TEST using features in Cloud ALM 

To use better traceability option with regards to changes pushed in the transport, feature can be used to track deployment status following change management policies of moving changes through pre-defined stages in auditable manner. The goal here is to assign the transport request in Cloud ALM and deploy content based on change workflow. 


1. Navigate to SAP Cloud ALM UI and select the feature created and click on Edit.
</br><img width="322" alt="image" src="images/ALM-Features-Edit.png">

2. Edit the feature and click on Assign under Transport.
</br><img width="322" alt="image" src="images/ALM-edit-feature.png">

3. Select the transport request and Assign
</br><img width="322" alt="image" src="images/ALM-assign-TR.png">

4.	Save and close
</br><img width="322" alt="image" src="images/ALM-Feature-Save.png">

5.	Deploy the transport from Cloud ALM feature.
</br><img width="322" alt="image" src="images/ALM-deploy-tr.png">
</br><img width="322" alt="image" src="images/ALM-Deployment-scheduled.png">

6.	After the status shows “Deployed in TEST”, change status from Implementation to testing.
</br><img width="322" alt="image" src="images/ALM-handover-to-Testing.png">

7.	Show Deployment Status in Feature Traceability. Explore the different options and filters in Feature traceability. End users can use this view to decide on what all features should be released to production. 
Navigate to Features Overview and select “Analytics.”
</br><img width="322" alt="image" src="images/ALM-analytics.png">
</br><img width="322" alt="image" src="images/ALM-FeatureTrace.png">



## Summary

You've now deployed the changes to TEST system.

Continue to - [Exercise 4 - Deploy to Production using Cloud Transport Management](../ex4/README.md)
