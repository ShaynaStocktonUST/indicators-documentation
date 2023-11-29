# Setting up Indicator Item Extensions

### Definition:
Extensions are used to define any required variations to an Indicator Item. This can include variations to the icon appearance and changes to the selection criteria.

### A Simple Usage example: 
An item for a Donor Status with a criteria of "contains" might have the following extensions:
* "Donor Status under $10k"
  * a pale green icon for total donations $0 to $9,999
* "Donor Status $10k - $50k"
  * a dark green icon for total donations $10,000 to $49,999
* "Donor Status $50k - $100k"
  * a pale yellow icon for total donations $50,000 to $99,999
* "Donor Status over $100k"
  * a dark yellow icon for total donations $100,000 or greater

### Prerequisites
* Have an [Indicator Item](Indicator-Item) already set up.


## Create the Indicator Item Extension:
|Field|Example Value|Description|Tip|
|----------|----------|-------------------|--------------------------|
|Label|`Donor Status`|Give it a descriptive name|Include the Object Name
|Indicator Item Extension Name|`Donor_Status`|The API name
|Active|`true`||Leave this unchecked until the Indicator is ready to be added to a Bundle
|Priority||Priority rules: If the first extension priority rule is met then further rules are ignored|Optional
|Minimum (>=)|`0`|The minimum value required|Optional
|Maximum (<)|`1000000`|The maximum value required|Optional
|Contains Text|`$500`|The field contains this text|
|Description|`If the Contact's Donor Status is Entered the icon will show`||Write something useful here, your future self will thank you
|Hover Text|`The Contact has a Donor Status entered`|Text to display when the user hovers over the icon|Leaving the Hover Text blank will show the field value as the hover text
|Static Text||Text to display instead of a field value, icon, or image URL (only the first 3 characters or emojis will display)|Copy and paste Emojis here for some fun Indicators
|Image||The URL to the image of the Indicator when being used instead of Field, Text, or Icon|eg link to a Static Resource, File, or Document in your Org|The use of an Image overrides any Icon settings
|Icon Value|`custom:custom17`|The Lightning Design System icon when being used instead of Field, Text, or Image URL. Get Icons from from https://lightningdesignsystem.com/icons/. Enter the full category and icon name like `custom:custom32'|If Static text is entered, the Icon colour will be used, with the static text in white
|Icon Background||Override the default background of the Indicator's icon
|Icon Foreground||Override the default foreground of the Indicator's icon

### Design Tips
* Don't use Icons that are in use in your Salesforce org elsewhere. Eg if you have Field Service installed, then don't use the standard:service_crew or standard:service_crew_member on Contact, as that will be confusing
* Don't be too literal - just pick an icon that looks good, or use a few characters instead of the Icon. Your users will get used to which icons mean what, and they have the hover text to help them know what the icon means
* Don't get too colourful - you can really make a mess. But use specific brand icons or colours for different brands in your company for example
 * See [[Icon Tips]] for more Icon ideas and tips
 * See [[Fields and Formulas Tips]] for tips on creating new Fields to use in your Indicators
 * See [[Icon Colors]] for tips on creating colourful icons

### Rules

* The indicators Extensions work with Boolean or Text fields. 
  * Date Fields can be used if you enter **Static Text** as the value that is shown does not make much sense. 
  * Number fields can be used as the value on the Indicator Extension, if the number is not too big, or you use **Static Text**. 
* If the field is a Boolean and the value is False the Indicator will not show unless **Show When False or Blank** is checked.
* If the field is a Boolean and there is a value in **Static Text** then that text will show. Limit this text to 3 characters max, and Uppercase. 
* If the field is a Boolean and there is no value in **Static Text** the Icon will be shown.
* If the field is a Text field and there is no value in **Static Text** the first 3 characters of the field value will show, in Uppercase.
* If there is **Static Text**, the Icon image will not be shown, but the colour will be from the **Icon Value** entered. 
* If there is a value in **Image** that image will show.
  * **Image** will take precedence over **Icon Value**
* There is no field validation to ensure you don't use a combination of entries that look weird, so if it looks strange, just go back to simple Boolean or text fields.

### Known Issues
* SLDS Action Icons eg `action:check` do not render in the Indicator Component correctly. Action Icons are not designed for usage in Salesforce Avatar which is what the Indicators are based on. 

### Related Note:
_If you create enough item extensions to cover all required variations, your Indicator Item could contain just the bare minimum information._

## Next Steps
* Create more extensions as needed.