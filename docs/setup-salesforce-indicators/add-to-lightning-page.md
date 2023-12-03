---
layout: default
title: Add the Bundle to the Lightning Page
parent: Set Up Salesforce Indicators
nav_order: 5
has_children: false
---

The [Indicator Bundle](../indicator-bundle) is added to the Lightning Record Page. You can have as many **Indicator Bundles** on Lightning Record Pages as needed. 

## Add the Bundle to your Lightning Page

After the Indicator Bundle, Indicator Items, and Indicator Bundle Items CMDT records have been created...

* Edit your Lightning Record Page (eg Account), and add the **Indicator Bundle** Component by dragging it to the desired location
* Choose the **Indicator Bundle** to show on the Page (eg Account Company Details). Ensure it is the correct Bundle to display for that Object
* Optionally choose to *Display Title* 
* Optionally choose to *Dieplay Description*
* Choose the *Indicator Size* - large or medium
* Choose the *Indicator Shape* - base or circle
* Optionally choose to show the *Refresh Button*. This is useful whilst you are setting up your Bundles.


## Tips

**💡Setup Tips**
* :exclamation: Remember to Save and [Activate](https://help.salesforce.com/s/articleView?id=sf.lightning_app_builder_customize_lex_pages_activate.htm&type=5) the Lightning Record Page :exclamation:
* The **Indicator Bundles** can be hidden using [Component Visibility](https://help.salesforce.com/s/articleView?id=sf.lightning_page_components_visibility.htm&type=5), just like any other Component.

**💡Design Tips**
* For one or two Bundles on the Page it is nice to show an Icon, Title, and Description for each Bundle. 
* For bundles with medium icons it may be OK to not show the Title and Description. 

## Next Steps

* Use the New button to add a new [Indicator Item](../indicator-item), and continue to add more Items
* Use the New button to add a new [Indicator Bundle Item](../indicator-bundle-item) to link the Bundle to the Item
* Check [The Key](../components/the-key)
