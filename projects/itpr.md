---
layout: page
title: ITPR
permalink: /projects/itps
excerpt:
---

### Information Technology Purchasing Request: Self-Service System

#### Process/Data Flow diagram 

![Technical Diagram](/images/projects/ITPR-SS_Technical.png){: .image-thumbnail }  
[Full Size](/images/projects/ITPR-SS_Technical.png){: target="_blank"}

The ITPR/S (IT Purchasing Requests / Self-Service) system is designed to support two options of notification and task tracking:

Option 1 (default option)

* Direct Email Notification to the individual reviewers thru Qualtrics; and 
* Additional Timer option and Email Processor for scheduled reminders thru the ITPSS/R Status Tracking component

Option 2 (Chewell option - Pending)

* Cherwell tasks triggered by the monitoring the Qualtrics ITPSS email queue
* Reviewers will process the requests thru the regular Cherwell workflow


#### Technology Stack

#### Web Portal with Single Sign On
* LAMP (Linux, Apache, MariaDB, and PHP) platform
* Single Sign On integration with LDAP Authentication

#### Qualtrics Integration
* Qualtrics InSight Platform
* [Embedded Data - Passing Information Via Query Strings](https://www.qualtrics.com/support/integrations/api-integration/passing-information-through-query-strings/){: target="_blank"}

* [Web Services](https://www.qualtrics.com/support/survey-platform/survey-module/survey-flow/advanced-elements/web-service/){: target="_blank"}

#### REST API
* [Lumen Micro-framework](https://lumen.laravel.com/){: target="_blank"}


