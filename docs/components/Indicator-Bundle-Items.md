# Setting up the Indicator Bundle Items

The Indicator Bundle Items link an  [Indicator Item](Indicator-Item) to an [Indicator Bundle](Indicator-Bundle). This allows you to set up different bundles that will display at different times or for different sets of users, but re-use the same Indicators on multiple Bundles. 

* Edit the Settings in CMDT:
  * Navigate to Salesforce **Setup** > **Custom Metadata Types**
  * Scroll to **Indicator Bundle Items** and click **Manage Records**
  * Click **Edit** next to the Indicator Bundle Item you want

* Or alternatively:
  * Navigate to the **Indicator Settings** Tab
  * Click the link on the Indicator Bundle Item you want to edit. 
  * Click the link on the Indicator Bundle Item Object to go to the list of Indicator Bundle Item and add new Custom Metadata records. 

## Prerequisites
* Have an [Indicator Bundle](Indicator-Bundle) already set up.
* Have an [Indicator Item](Indicator-Item) already set up.

## Create the Indicator Bundle Item
|Field|Example Value|Description|Tip|
|---------|----------|-------------------|--------------------------|
|Label|`Contact Default Mobile`|Give it a descriptive name|Include the Object Name
|Indicator Item Name|`Contact_Default_Mobile`|The API name
|Indicator Bundle|`Contact Default`|Choose the Indicator Bundle from the List
|Indicator Item|`Contact Mobile`|Choose the Indicator Item from the List
|Order|`10`|The Order this Indicator will appear in the Bundle

## Tips
* Type part of the name in the lookup fields and it will auto complete them on Save
* Use increments of 10 or more when setting up the Order, so you can add new Indicators in between without re-ordering the whole bundle. Eg 10, 20, 30, then add a new Indicator at 14 later. 


