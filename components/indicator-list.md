---
layout: default
parent: Components
title: Indicator List
nav_order: 1
has_children: false
nav_exclude: true
---

## Using the Indicator List Component

{: warning-title}
>Deprecated Component
>
>This documentation is here for those that still use the Indicator List Component. Whist it has served us well it was very hard to configure well, so it has now been deprecated. 

* Add the **indicatorList** Component to the Lightning Record Page. 
* Enter the Settings for the Lightning Card:
  * **Title** - Not Required, but looks best if it is defined
  * **Icon** - Not Required, but looks best if it is defined - the icon name from [SLDS Icons](https://www.lightningdesignsystem.com/icons/) or default icons such as standard:account, standard:opportunity
  * **Heading Text** - _Optional_ - the text to display above the icons
  * **Icon Size** - large or medium, defaults to large
  * **Icon Shape** - circle or base (square), defaults to base
* Enter the Settings for each Indicator:
  * **Indicator Field Names** - the exact API Name of the field to display - case is important. Separated by a semicolon. 
  * **Indicator Icons** - the icon name from [SLDS Icons](https://www.lightningdesignsystem.com/icons/) or default icons such as standard:account, standard:opportunity separated by a semicolon. 
  * **Indicator Text Values** - the three character (max) text values to show for each icon. Separated by a semicolon. Eg enter ;; if there are 3 icons with no text.
  * **Indicator Image URLs** - the full URL of the Image to display, separated by a semicolon. Note: No quotation marks. Image URLs are not applicable for False values. 
  * **Indicator Hover Texts** - the text to display on hover. Keep it short. Separate by semicolons. No semicolons in the text. Suggest enter Something like "Status - Green: Active - Red: Inactive" as no semicolons or wrapping is allowed. Alt text should be less than 50 chars long for good accessibility.
  * **Icons for False** - if you want the False value to display then enter an icon here. the icon name from SLDS Icons or default icons such as standard:account, standard:opportunity separated by a semicolon. Enter semicolons between all indicators if no False values are to be shown.
  * **Text Values for False** - works similar to Indicator Text Values, but if the value is False or blank. This works in conjunction with Icons for False and the Avatar will only show if Icons for False is entered for that Indicator. 
* After entering all settings, the Indicators should display on the Lightning Page preview and will then change in the preview as you adjust the settings. 
* Click **Save**
* Test a boolean field to ensure the indicator disappears if False. Test a boolean field with False values to make sure the indicator appears if the boolean is False.

  _Hint:_ Use the [configuration worksheet](https://docs.google.com/spreadsheets/d/1e-Qxi0MY9An9Hb9mHPVxFom--HCNK6xNRkWO12xRxg0/edit?usp=sharing) ([Make your own copy](https://docs.google.com/spreadsheets/d/1e-Qxi0MY9An9Hb9mHPVxFom--HCNK6xNRkWO12xRxg0/copy)), It has been created to help you work out the whole component before you set it up on the page.