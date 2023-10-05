# Exercise 4 - Deploy to Production using Cloud Transport Management 

Triggers Import in Cloud Transport Management by selecting the transport request from production node.

1. Navigate to the [TMS UI](https://ad261-calm-h7f2r9xc.ts.cfapps.eu10.hana.ondemand.com/main/webapp/index.html#/nodeObject/6) and select the PROD from Transport Nodes. 
Select the Transport request with your user suffix "Teched  Demo Transport for AD261-XXX" and click on Import Selected.
This would trigger the deployment to TEST account. The process takes a few minutes to complete. As you wait you can check the Action Logs and additional details by clicking on Logs Icon and attachment icon.
</br><img width="322" alt="image" src="images/TMS-deploy.png">
</br><img width="322" alt="image" src="images/TMS-deploy-prod-ok.png">
</br><img width="322" alt="image" src="images/TMS-Deployment-Success.png">

2. Navigate to Cloud ALM and Confirm Deployment for your feature "Feature AD261-XXX". 
You observe a final confirmation, click OK.
</br><img width="322" alt="image" src="images/ALM-confirm-prod-deployment.png">
</br><img width="322" alt="image" src="images/ALM-Confirm-OK-Prod.png">
</br><img width="322" alt="image" src="images/ALM-deployed-OK.png">

3. Check the history by clicking on the clock icon in the feature detail page. 
</br><img width="322" alt="image" src="images/ALM-History.png">
</br><img width="322" alt="image" src="images/ALM-History-Full.png">



## Summary

You've now deployed the changes to PROD system.

Continue to - [Exercise 5 - View deployed content in Prod account](../ex5/README.md)
