{:toc}

<h1 align="center"> Shipstation Odoo Connector </h1>
{:.no_toc}

<!-- ## Table of contant
- [Overview](#overview)
- [Installation](#installation)
  - [1. Create and configure shipping instance](#create-and-configure-shipping-instance) -->

## 1. Overview
The ShipStation team has long been one of the industry leaders in withholding, fulfilling, and shipping orders from the most popular marketplaces and shopping carts using the most popular carriers. With the ShipStation Odoo Shipping Connector app, you can perform all the functions of the backend directly on Odoo, no matter what the size of your company is. Offer your customers more choice with numerous options for shipping.

## 2. Installation
After successfully downloading the ShipStation Odoo Connector App from the Odoo store or Emipro shop, place it on the Odoo Add-ons path or at any other desired path. Now, restart the Odoo instance and navigate to Apps in the dashboard. Click on Update Apps List from the menu. Once it completes loading successfully, the ShipStation Odoo Connector will be visible in Apps.
Click on the Install button. Success! Now, you are ready to use the ShipStation Odoo Connector in your Odoo.
 

## 3. Create and configure shipping instance
This connector aims to make retailers exceptionally efficient at processing, fulfilling, and shipping their eCommerce orders. To start with, creating and configuring shipping instances in Odoo post successful installation will be the first step to start our successful integration. 

Navigate to ShipStation / Configuration / Shipping Instance and click on the Create button to create the new instance. All the other instances that were configured earlier will be visible in this section. You can modify it if required.
![Instance](https://www.emiprotechnologies.com/website/image/ir.attachment/33313_fad4fd4/datas)

Make sure to select the provider as “ShipStation”. In the Credential tab, enter the ShipStation URL, API Key and Secret Key provided by ShipStation.
![InstanceProvide](https://www.emiprotechnologies.com/website/image/ir.attachment/33314_b21d4fd/datas)

Further, switch the Shipping instance mode to Production during the production setup. Test mode is only meant to be used in a staging or testing environment.
![InstanceEnv](https://www.emiprotechnologies.com/website/image/ir.attachment/33315_18b952f/datas)

Click on the “Check Connection” button to validate the credentials and authentication to the Shipstation. If the credentials are incorrect, a message “Given credentials are incorrect, please provide correct credentials.” will appear in front of you. For the connection established, “Shipstation Connection Successful” message will be displayed.
![InstanceConnection](https://www.emiprotechnologies.com/website/image/ir.attachment/33316_11b087a/datas)

### 3.1 ShipStation Marketplace
You can access the marketplaces from the configuration menu. However, it is also accessible by the “Marketplace” smart button available in shipping instances.
![ShipstationMarketplace](https://www.emiprotechnologies.com/website/image/ir.attachment/33318_ae30d27/datas)

### 3.2 ShipStation Store
Next to the Marketplace, Store is accessible. It can also be accessed by the “Store” smart button available in shipping instance.
![ShipstationStore](https://www.emiprotechnologies.com/website/image/ir.attachment/33319_d5e781e/datas)
