{:toc}

## 3. Create and configure shipping instance
This connector aims to make retailers exceptionally efficient at processing, fulfilling, and shipping their eCommerce orders. To start with, creating and     configuring shipping instances in Odoo post successful installation will be the first step to start our successful integration. 

Navigate to ShipStation / Configuration / Shipping Instance and click on the Create button to create the new instance. All the other instances that were configured earlier will be visible in this section. You can modify it if required.
![01_shipping_instance](03_shipping_instance/images/01_shipping_instance.png)

Make sure to select the provider as “ShipStation”. In the Credential tab, enter the ShipStation URL, API Key and Secret Key provided by ShipStation.
![02_shipping_instance](03_shipping_instance/images/02_shipping_instance.png)

Further, switch the Shipping instance mode to Production during the production setup. Test mode is only meant to be used in a staging or testing environment.
![03_shipping_instance](03_shipping_instance/images/03_shipping_instance.png)

Click on the “Check Connection” button to validate the credentials and authentication to the Shipstation. If the credentials are incorrect, a message “Given credentials are incorrect, please provide correct credentials.” will appear in front of you. For the connection established, “Shipstation Connection Successful” message will be displayed.
![04_shipping_instance](03_shipping_instance/images/04_shipping_instance.png)






### 3.1 ShipStation Marketplace
You can access the marketplaces from the configuration menu. However, it is also accessible by the “Marketplace” smart button available in shipping instances.

### 3.2 ShipStation Store
Next to the Marketplace, Store is accessible. It can also be accessed by the “Store” smart button available in shipping instance.

### 3.3 ShipStation Sync
Click on the Sync button. It will Sync Marketplaces, Stores, Carriers, Services, Packages, and Warehouses. You will get the “ShipStation Sync is completed” message on successful sync.

### 3.4 Shipment Email Notification
Email Shipment Notification via Email is the requirement for any online seller, specifically when shipment takes days to reach the destination. A shipment notification email is a feature to notify the customer about their shipment with the tracking details. To enable this feature go to Shipstation / Configurations / Shipping instance and enable the Auto Send Shipment Email checkbox. You need to provide a link to the Shipstation Branded Tracking Page. This link will be included in the email. You will also get an email notification when the tracking number is available.

