## Salesforce Permissions Needed

* To create [Custom Metadata Records](https://help.salesforce.com/s/articleView?id=sf.custommetadatatypes_ui_populate.htm&type=5), users need the `Customize Application` permission. 
  * See the [Customize Application](https://help.salesforce.com/s/articleView?id=000386451&type=1) help document.
  * Customize Application is part of the System Administrator profile.
  * Be careful giving this permission to any other users.

## Salesforce Indicators Permission Set

* Assign the `Indicators Setup Access` permission set to any users.
  * This grants access to the Indicators Setup Tab.

## User Permissions

* Once the Indicator Bundle is added to the Lightning page, all users who can see that page can see the bundle, unless it is hidden by [Component Visibility](https://help.salesforce.com/s/articleView?id=sf.lightning_page_components_visibility.htm&type=5). 
* Users will only see the Indicator Items if they have read access to the field and sObject the [[Indicator Item]] is based on. 
* Test your Indicator Bundles to ensure that there are no blank bundles, which doesn't look good for users. 

## About Custom Metadata 
* See this [Trailhead Module](https://trailhead.salesforce.com/content/learn/modules/custom_metadata_types_dec) to learn more about Custom Metadata in Salesforce.

## Next Step/s

* [[Installing Salesforce Indicators]]
* [[Setup Salesforce Indicators]]

For any help or comments, please ask a question on our [Trailblazer Community group](https://trailhead.salesforce.com/trailblazer-community/groups/0F94S000000HEDASA4)




