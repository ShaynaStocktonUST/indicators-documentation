---
layout: default
title: Getting Started with Salesforce Indicators
nav_order: 20
has_children: false
---

## Getting Started with Salesforce Indicators

Thank you for choosing Salesforce Indicators to enhance your Lightning Pages! This documentation will help you get started using the app.

Where and What to Install
1. Training: Install in a trailhead org to learn how to use the tool. Include the sample metadata examples 
2. Your own Salesforce org: Start in sandbox and only install the base package

Object Structure
1. Indicator Item: The individual icon or text display, relating to your Salesforce field, which you want to display visually. For instance, if you want a quick visual indication that a particular contact has lapsed in engagement and you have criteria that indicates that, the Indicator itself can be used to represent that criteria.
2. Indicator Bundle Item: A container object that takes the Indicator Item you have created and represents it for the Bundle. The Indicator cannot be added to the Bundle without this bridge object (Similar to Affiliations for those using NPSP and EDA)
3. Indicator Bundle: Collection of Indicator Bundle Items for display on the Lightning Record Page. Collects the Indicator Items created for an object and added via Indicator Bundle Item into one component for the actual visual representation.
