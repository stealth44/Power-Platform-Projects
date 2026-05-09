# Loan Approval Workflow using Power Automate

## Project Overview

This project automates the loan approval process using Microsoft Power Automate and SharePoint. It is designed to reduce manual approval steps, improve response time, and maintain a clear record of loan requests and approval decisions.

## Tools Used

* Microsoft Power Automate
* SharePoint
* Outlook

## Business Problem

Manual loan approval processes often involve email follow-ups, delayed responses, and poor visibility into request status. This workflow provides an automated approval process that improves efficiency and tracking.

## Solution Design

A SharePoint list is used to capture loan requests. When a new request is submitted, Power Automate automatically sends an approval request to the assigned approver. Based on the response, the request status is updated and the applicant receives a notification.

## Workflow Process

1. Applicant submits a loan request through SharePoint
2. Flow triggers automatically when a new item is created
3. Approval request is sent to the approver
4. Approver reviews and approves or rejects
5. SharePoint status updates automatically
6. Applicant receives email notification

## SharePoint Columns

* Applicant Name
* Loan Amount
* Loan Purpose
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

(Add screenshots here)

## Future Improvements

* Multi-level approval
* Reminder notifications
* Integration with Dataverse
* Teams notification support
