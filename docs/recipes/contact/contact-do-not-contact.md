---
layout: default
title: Contact - Do Not Contact
parent: Contact
grand_parent: Recipes
has_children: false
nav_exclude: true
---


# Contact: Do Not Contact

## Description
> This indicator represents a contact who has requested to not be contacted at all.

## In Bundle
* [Contact Communication Preferences](../bundle-contact-communication-preferences)
* [Contact Preferences](../bundle-contact-preferences)

## Images 

![First Non Empty](../../images/icons/first_non_empty_120.png){: width="50" bg-color="#ff538a"}


## Fields

Fields | Value
-- | --
sObject | `Contact`
Field | `npsp__Do_Not_Contact__c`
Active | `TRUE`
Empty Static Text Behavior | `Use Icon Only`
Hover Text | `Do Not Contact`
Icon Value|`standard:first_non_empty`
Show False or Blank | `TRUE`
Zero Value Handling | `Treat Zeroes as Blanks`

## Preparation
`npsp__Do_Not_Contact__c` is a standard NPSP field. 

## Note 
The default color of this icon is pink after the updates from Winter '24. If you want to make changes, you can just adjust the Icon background and foreground settings. Ex. To change the icon to a red background and white symbol:

| Fields | Value | 
|-----------|-----------|
|Icon Background|`Red`|
|Icon Foreground|`White`|


## Contributed By
Emma Keeling, [Salesforce_Em](https://github.com/Salesforce-Em)
Maida Rider, [RiderM780](https://github.com/RiderM780)




## Description
> An Indicator to show different color icons depending on the Do not contact status of the contact.

## In Bundle
* [[Contact: Contact Preferences]]

## Fields

| Fields | Value | 
|-----------|-----------|
|Label|`Do not Contact`|
|sObject|`Contact`|
|Field|`Do Not Contact`|
|Description|

##Configuration
| Fields | Value | 
|-----------|-----------|
|Hover Text|`Do Not Contact`|
|Static Text|
|Empty Static Text Behavior|`Use Icon Only`|
|Zero Value Handling|`None`|
|Image|
|Icon Value|`standard:first_non_empty`|
|Image|
|Show when False or Blank|`True`|
|Inverse Hover Text|
|Inverse Static Text|
|Inverse Image|
|Inverse Icon Value|
|Inverse Icon Background|
|Inverse Icon Foreground|

##NOTE: The default color of this icon is pink. If you want to make changes, you can just adjust the Icon background and foreground settings. Ex. To change the icon to a red background and white symbol:

| Fields | Value | 
|-----------|-----------|
|Icon Background|`Red`|
|Icon Foreground|`White`|

## Contributed By
Maida Rider, [RiderM780](https://github.com/RiderM780)