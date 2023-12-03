See [[Installing Salesforce Indicators]] if you have not already installed Salesforce Indicators

## 1. Design your Salesforce Indicators model

* Before creating your first **Indicator Bundle** or **Indicator Item** consider the data that will drive your indicators. 
* Below is a visual of the data model for each Component.

![Salesforce Indicators Data Model](../images/setup/DataStructure.png){: width="590"}

* Consider your field design. Design field to be multi-use where ever possible.
>>this needs to be built out further describing the challenge of using boolean fields with other data, giving the example of memberships (is active) and months to end date
* Are you using [Declarative Lookup Rollup Summaries (DLRS)?](https://github.com/SFDO-Community/Salesforce-Indicators/wiki/Additional-Complementary-Apps-and-Components-to-Enhance-Your-Org#declarative-lookup-rollup-summary-salesforce-open-source-commons) Consider whether DLRS could help you surface the data for the indicators you need.

## 2. Access the Salesforce Indicators setup Item
Go to the **Indicators Setup** Item
![Open Indicators Setup](../images/setup/OpenIndicatorsSetup.png){: width="590"}

![Indicators Setup Menu](../images/setup/IndicatorsSetupMenu.png){: width="590"}

## 2. Set up your Indicator Bundle

* Use the New button to add a new [Indicator Bundle](indicator-bundle)

## 3. Add your Indicator Item/s

* Use the New button to add a new [Indicator Item](indicator-item), and continue to add more Items

## 4. Add your Indicator Bundle Item

* Use the New button to add a new [Indicator Bundle Item](indicator-bundle-items) to link the Bundle to the Item

## 5. Add to your Lightning Page

* Now you can add your Indicator Bundle to your [Lightning Page](https://github.com/SFDO-Community/Salesforce-Indicators/wiki/Add-to-Page)

## 6. Review The Key

* Once published, review [[The Key]] and make any adjustments to improve the user experience

## 6. Using Indicator Item Extensions

* **_Tip!_** Start using the Salesforce Indicator Bundles, Items and Item Bundles **first** before moving on to Indicator Item Extensions
* Once you are comfortable with the basic Salesforce Indicator set up process, use the New button to add a new [Indicator Item Extension](Extensions) to an existing Item

For any help or comments, please ask a question on our [Trailblazer Community group](https://trailhead.salesforce.com/trailblazer-community/groups/0F94S000000HEDASA4)

