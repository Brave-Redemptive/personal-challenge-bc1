## The SpaceRug Platform ( Backend )

> This is a project that helps understand how you structure a Node.js project and build out a well written standard and professional software.

## Introduction

The SpaceRug platform is a real-estate platform that bridges the gap between real-estage managers or asset owners ( i.e. landlords, house owners, property owners e.t.c ) and buyers or customers. asset owners are meant to setup accounts where they can list assets ( land, house, cars ) and buyers/customers can come to check out assets and make proposition to buy them. Buyers should also setup accounts for proper management.

## Platform High-Level Features

### Asset Owner ( Real Estate Managers )
- Ability to create a business account
- Ability to add assets ( land, cars, house )
- Assets are meant have high-level properties like name, type, location, status, price
- Ability to set if an asset is used, new or landed
- Landed (land) assets should always have the "landed" type
- Ability to determine the used date ( i.e. from and to ) of an asset if it is used
- Ability to edit properties of an asset
- Ability to change the status of an asset; statuses are available, booked or bought or leased
- Ability to determine if an asset is meant for lease or selling
- Ability to recieve reminders for assets leased for payment
- Ability to recieve payments for assets sold or leased
- Ability to see history of payments and history of assets added on the platform
- Ability to see the location of an asset on a map
- Ability to upload not more than 10 images for an asset

### Buyer or Customer
- Ability to create customer or buyer account
- Ability to see assets in a public place, view asset details and make a decision to buy
- Ability to make payment for an asset online
- Ability to recieve reminders, emails and more on an asset bought or rented ( via lease )
- Ability to view and track the location of an asset on a map
- Ability to search assets within the same location on the map
- Ability to search assets by type and or status
- Ability to draw location on map and search assets within that location

### Platform Users
- Ability to have a superadmin with access to manage platform
- Ability to add other administrators
- Ability to setup account for an asset owner
- Ability to payout cash to Asset Owners

> Note: These are high-level features, you are meant to determine other functionalities the software should have. 

>Note: Geo-Location search is an important feature of the platform


## Technology

It is important to note that this is a backend project at first. You will be notified if you need to work on the frontend. 

- Node.js ( Typescript )
- Typescript
- Database - MongoDB
- Server - ExpressJs

## Important architecture to note

- Build Authentication from Scratch
- Build Geo-Location Search functionalities
- Users of the platform can have multiple roles

## Instructions

- You are required to complete the project in 10 days. If you need more time, reach out to the instructor and explain why to get more time.
- You are required to complete the project so that it passes all acceptance criterias given
- You are required to write UNIT test cases for the project
- You are required to write API documentation for the project using the POSTMAN API Client
- For your submission, please create a "PRIVATE" and add [@immatobi](https://github.com/immatobi) to the repository with proper description on how to run the project in a README.MD file

## Acceptance Criterias

> Note that this will be update on the go. Check back for updates

- Authentication must be built from scratch
- Authentication must include protect and authorize middlewares
- Authentication must check and verify user roles
- MVC pattern should be well implemented
