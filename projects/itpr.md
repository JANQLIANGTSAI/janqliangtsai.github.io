---
layout: page
title: ITPR
permalink: /projects/itps
excerpt:
---
  
  
### Information Technology Purchasing Request: Self-Service System

<hr style="border-top: 1px dotted #8c8b8b;" />  

[About](#about)  
[Process/Data Flow diagram](#processdata-flow-diagram)  
[Technology Stack](#technology-stack)  

<hr style="border-top: 1px dotted #8c8b8b;" />  
  
#### About
**IT Purchase Review (ITPR)**

The Information Technology Purchase Review (ITPR) form and process was created to help purchase requesters make well-informed purchasing decisions for IT products and services, address the University’s obligations to comply with existing laws, policies, and standards, and make best use of campus IT resources.

The ITPR form must be completed prior to the purchase or acquisition of any IT-related product or solution, regardless of funding source or total cost. The ITPR form was designed to be dynamic, and the number and types of questions displayed changes based upon specific responses about the purchase, the product/solution and its intended use.

Based upon responses provided in the ITPR form, a more in-depth assessment may be required to address:

* Accessibility
* Information Security and Privacy
* Technology Integration and Support
* Procurement and Contracting  

#### Process/Data Flow diagram 

![Technical Diagram](/images/projects/itpr/ITPR-SS_Technical.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/ITPR-SS_Technical.png){: target="_blank"}

The ITPR/S (IT Purchasing Requests / Self-Service) system is designed to support two options of notification and task tracking:

Option 1 (default option)

* Direct Email Notification to the individual reviewers thru Qualtrics; and 
* Additional Timer option and Email Processor for scheduled reminders thru the ITPSS/R Status Tracking component

Option 2 (Chewell option - Pending)

* Cherwell tasks triggered by the monitoring the Qualtrics ITPSS email queue
* Reviewers will process the requests thru the regular Cherwell workflow


#### Technology Stack

**Web Portal with Single Sign On**  

* LAMP (Linux, Apache, MariaDB, and PHP) platform
* Single Sign On integration with LDAP Authentication

**Qualtrics Integration**  

* Qualtrics InSight Platform
* [Embedded Data - Passing Information Via Query Strings](https://www.qualtrics.com/support/integrations/api-integration/passing-information-through-query-strings/){: target="_blank"}
* [Web Services](https://www.qualtrics.com/support/survey-platform/survey-module/survey-flow/advanced-elements/web-service/){: target="_blank"}

**REST API**  

* [Lumen Micro-framework](https://lumen.laravel.com/){: target="_blank"}


#### UX / UI

1. Portal Frontpage  
![Portal Frontpage](/images/projects/itpr/01-Portal.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/01-Portal.png){: target="_blank"}

2. Main Menu (post login)  
![Main Menu](/images/projects/itpr/02-MainMenu.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/02-MainMenu.png){: target="_blank"}

3. New Request (push to Quatrics with Embedded data)  
![New Request](/images/projects/itpr/03-AddQualtrics.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/03-AddQualtrics.png){: target="_blank"}

4. Staus Dashboard  
![Staus Dashboard](/images/projects/itpr/04-Dashboard.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/04-Dashboard.png){: target="_blank"}

5. Debug (Raw Data)  
![Debug](/images/projects/itpr/05-BebugRaw.png){: .image-thumbnail }  
[Full Size](/images/projects/itpr/05-BebugRaw.png){: target="_blank"}

-----
Last updated: 10/01/2016 12:22PM (janq)  

-----

```
Project Contacts  

Technical Architecture and Development Lead  
[Max Tsai](janq@csufresno.edu)  
Innovation Architect, Technology Services  

Qualtrics Design and Implemenation Lead  
[Chris Hernandez](chhernandez@csufresno.edu)  
Research Analyst, Office of Institutional Effectiveness   

Business Process / Functional Design Lead  
[Tom Siechert](tsiechert@csufresno.edu)                                                             
ATI Procurement Program Manager | Senior IT Buyer
```

