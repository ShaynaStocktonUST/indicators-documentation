---
title: Install Salesforce Indicators
nav_order: 2
has_children: false
---
# Getting Started with Salesforce Indicators

Thank you for choosing Salesforce Indicators to enhance your Lightning Pages! This documentation will help you get started using the app.

[Install Salesforce Indicators](https://install.salesforce.org/products/indicators/latest){: .btn .btn-green }{:target="_blank"}

* Install the latest version of the managed package from the [Install Page](https://install.salesforce.org/products/indicators/latest). 
* See the [Release Notes](/indicators-documentation/docs/release-notes) for the updates included in the latest version.

## Using Metadeploy to Install

Salesforce Indicators is a managed package and has been security reviewed by Salesforce. Installation, along with many other great Salesforce.org Open Source Commons applications, is done through Salesforce.org's [MetaDeploy installer](https://github.com/SFDO-Tooling/MetaDeploy).

* On the Metadeploy page, log into your org. You will be asked to give the Metadeploy tool access to your org. This is necessary for installation. 
* Click the **Install** button.
* Confirm the Product Terms of Use and Licences around the use of the Open Source licence. 
* The install will begin, you can expand the Steps section to see the progress of the Install. 
* When the Installation is successful, click **View Org** to open your org. 

As with all managed packages, the installed package is visible in **Setup** > **Installed Packages**.

## After install

* Assign the Permission Set **Indicators Setup Access** to your Salesforce Administrator user.
* Assign the Permission Set **Indicators User Access** to your Users who will be viewing the Indicators. 

<img src="https://SFDO-Community-Sprints.github.io/indicators-documentation/docs/images/setup/AssignPermissionSet.png" width="590" height="280"/>


* Using the App Launcher button (9 dots), search for **Indicators Setup** and open the Indicators Setup tab. 

![Open Indicators Setup](/indicators-documentation/docs/images/setup/OpenIndicatorsSetup.png)

Congratulations! Now you are ready to start setting up Salesforce Indicators for your org!

## Next Steps

* [Plan your Indicators](/plan-indicators) and Data
* Use the New button to add a new [Indicator Bundle](indicator-bundle)
* Use the New button to add a new [Indicator Item](indicator-item), and continue to add more Items
* Use the New button to add a new [Indicator Bundle](indicator-bundle-item) Item to link the Bundle to the Item
* Optionally use the New button to add a new [Indicator Item Extension](item-extension) to an existing Item
* Add the [Indicator Bundle](indicator-bundle) to the Lightning Record Page. 
