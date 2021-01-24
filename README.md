# FatBoi

Basic app for tracking food intake

## Entry

Easy entry and meals / snacks
-   Designed mobile first
-   Easy to enter, minimal inputs

## Reconciliation

Reconcile food intake over a period, assign kcals for each meal & other meta data

## Review

Review food intake, looking at the data over certain time periods. 

## Tags

Can add different tags to meals.

Example:
Vegetarian, vegan, meat
Snack, lunch, dinner
Dairy
Homecooked, restaurant etc

## Implementation

Try to keep it API agnostic for the time being until I've sorted out a hosting provider

Options:
Azure, Firebase, AWS, third party, Box in the shed. 

Front end in Angular, using NgRx for state management.
Going full on Reactive Forms & Modules stuff. 

## Schema

Entry
-   Title
-   Tags
-   Date
-   Notes

Tag
-   Category
-   Label

Category
-   Label
-   Colour

Eat
-   Food
-   Date

Food
-   Title
-   Tags
-   Kcal