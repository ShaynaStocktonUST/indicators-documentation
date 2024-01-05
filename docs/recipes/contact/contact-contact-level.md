---
layout: default
title: Contact - Contact Level
parent: Contact
grand_parent: Recipes
has_children: false
nav_exclude: true
---


# Contact: Contact Level

## Description
> This indicator shows a different icon based on different donor levels identified.

## In Bundle
* [Contact Communication Preferences](../bundle-contact-communication-preferences)

## Fields

Fields | Value
-- | --
sObject | `Contact`
Field | `Donor_Level_Value_Formula__c`
Active | `TRUE`
Empty Static Text Behavior | `Use Icon Only`
Show False or Blank | `FALSE`
Zero Value Handling | `Treat Zeroes as Blanks`

## Extensions

## Preparation
`Donor_Level_Value_Formula__c` is a custom field that returns a text value for XX and YY based on the value of the total donations received from that Contact. 
Note: You can also just use values in the Indicator Item Extensions. However, creating a formula field allows the field to be used in multiple places, incluiding Reports.  

## Contributed By
Emma Keeling, [Salesforce_Em](https://github.com/Salesforce-Em)