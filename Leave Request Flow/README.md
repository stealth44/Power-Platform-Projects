# Leave Approval Workflow using Power Automate

## Project Overview

This project automates the leave approval process using Microsoft Power Automate and SharePoint. It is designed to reduce manual approval steps, improve response time, and maintain a clear record of leave requests and approval decisions.

## Tools Used

* Microsoft Power Automate
* SharePoint
* Outlook

## Business Problem

Manual leave approval processes often involve email follow-ups, delayed responses, and poor visibility into request status. This workflow provides an automated approval process that improves efficiency and tracking.

## Solution Design

A SharePoint list is used to capture leave requests. When a new request is submitted, Power Automate automatically sends an approval request to the assigned approver. Based on the response, the request status is updated and the applicant receives a notification.

## Workflow Process

1. Applicant submits a leave request through SharePoint
2. Flow triggers automatically when a new item is created
3. Approval request is sent to the approver
4. Approver reviews and approves or rejects
5. SharePoint status updates automatically
6. Applicant receives email notification

## SharePoint Columns

* Applicant Name
* Leave Amount
* Leave Purpose
* Submission Date
* Status
* Approver Email

## Key Features

* Automated approval workflow
* Conditional branching
* Email notifications
* SharePoint integration
* Status tracking

## Business Value

* Reduces manual processing time
* Improves approval visibility
* Creates a reliable audit trail
* Enhances response speed

## Screenshots

<img width="1672" height="873" alt="Adding new item or leave request" src="https://github.com/user-attachments/assets/db925179-d378-4f76-8e71-6e5453391b25" />

<img width="1812" height="637" alt="approval email" src="https://github.com/user-attachments/assets/31573d67-0298-4e24-959b-cafe23e0251a" />

<img width="1852" height="967" alt="automate flow" src="https://github.com/user-attachments/assets/1702ae0b-fab9-4c7b-bc40-3441149a0a84" />

<img width="1856" height="316" alt="Leave request" src="https://github.com/user-attachments/assets/ca2be59e-8b98-476b-bd42-e33f2a46fe01" />



## Future Improvements

* Multi-level approval
* Reminder notifications
* Integration with Dataverse
* Teams notification support
