# activity-node-id-generator

## Setup
- Add agiliteActivityNodeIdGenerator.json application to your Conenctions organisation
- Ensure the include-files property pulls the correct path referencing the agiliteCore.js and agiliteActivityNodeIdGenerator.js files

## Description
The purpose of this Customizer application is to populate a readable unique identifier (e.g. 00001) into a custom field called "Ref No" (Case Sensitive) for any Activity Node where custom fields can be created. The Customizer app makes use of the [Agilit-e](http://agilit-e.com) Cloud Numbering microservice to generate the unique numbers.

To test this functionality, simply create an Activity Entry or To Do. For the Entry or To Do, create a custom field with the label "Ref No". A readable unique number will almost immediately be populated into the field.

This functionality works especially well with Entry and To Do Templates. In the template, make sure a custom field with the label "Ref No" exists. 

## Screenshots

![Screenshot 1](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-activity-node-id-generator-1.jpg)
![Screenshot 2](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-activity-node-id-generator-2.jpg)