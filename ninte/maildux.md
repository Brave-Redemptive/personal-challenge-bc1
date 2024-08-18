## The MailDux Platform ( Backend )

> This is a project that helps understand how you structure a Node.js project and build out a well written standard and professional software.

## Introduction

The MailDux platform campaign management platform which allows marketers to create and schedule campaigns to send to user emails. The platform will allow for providing click and read analytics of campaigns. This is a role-based access system

## Platform High-Level Features

### Marketers
- Ability to create a marketer account
- Ability to create a campaign
- Ability to create campaign sections and add styles, images, text (rich-text)
- ability to edit campaign details 
- ability to publish a campaign ( publishing campaign means sending the campaign to earlier uploaded emails)
- ability to upload bulk emails to account using a .csv file
- ability to see campaign analytics
- ability to see campaign history
- Ability to send test campaign to specified emails
- Ability to create paid campaigns
- Ability to collect payments for paid campaigns
- Ability to specify if an uploaded email has paid for a campaign

### Platform Users
- Abilities for users to make payment for a paid campaign
- Ability to have a superadmin with access to manage platform
- Ability to add other administrators
- Ability to payout cash to Marketers

> Note: These are high-level features, you are meant to determine other functionalities the software should have. 


## Technology

It is important to note that this is a backend project at first. You will be notified if you need to work on the frontend. 

- Node.js ( Typescript )
- Typescript
- Database - MongoDB
- Server - ExpressJs

## Important architecture to note

- Campaign management with rich text enabled
- Payment functionalities for paid campaigns

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
