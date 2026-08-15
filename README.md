# ServiceNow Incident Lifecycle Automation

## Project Overview

This project demonstrates an **Incident Lifecycle Management implementation in ServiceNow**. It covers incident tracking from creation through resolution and closure, along with related services, configuration items, child incidents, knowledge articles, and SLA information.

The project demonstrates how ServiceNow can be used to manage incidents efficiently, track their progress, identify affected services and configuration items, and maintain complete resolution information.

## Objectives

The main objectives of this project are:

* Manage incidents throughout their complete lifecycle.
* Track incident impact, urgency, and priority.
* Associate incidents with affected Configuration Items (CIs).
* Link incidents with services and service offerings.
* Track child incidents and related records.
* Maintain resolution details and work notes.
* Monitor SLA and timing information.
* Provide better visibility into incident-related information.

## Service Structure

The project uses the following service structure:

* **Service:** Remote Access
* **Service Offering:** Corporate VPN
* **Configuration Item (CI):** VPN Gateway

The incident is associated with the relevant service offering and affected configuration item to provide better impact and dependency tracking.

## Incident Lifecycle

The incident follows a structured lifecycle:

**New → In Progress → On Hold → Resolved → Closed**

The project also supports **reopening an incident** when further action or investigation is required.

### Lifecycle Description

| State           | Description                                                                                  |
| --------------- | -------------------------------------------------------------------------------------------- |
| **New**         | Incident is created and awaiting investigation.                                              |
| **In Progress** | Incident is being investigated or worked on.                                                 |
| **On Hold**     | Incident is temporarily paused due to a dependency or required information.                  |
| **Resolved**    | The issue has been fixed and resolution details are recorded.                                |
| **Closed**      | The incident is completed and officially closed.                                             |
| **Reopened**    | A resolved incident can be reopened if the issue occurs again or further action is required. |

## Incident Details

Example incident used in the project:

* **Incident:** INC0010004
* **Short Description:** Restart VPN-SRV-02 service
* **Impact:** High
* **Urgency:** Medium
* **Priority:** High
* **Affected CI:** VPN Gateway
* **Service:** Remote Access
* **Service Offering:** Corporate VPN

## Resolution Management

The incident record maintains complete resolution information, including:

* **Resolution Code:** Workaround provided
* **Resolution Notes:** Restarted VPN-SRV-02 service as per emergency change request.
* **Probable Cause:** VPN-SRV-02 service was suspended and required restart.

This information helps maintain a clear record of how the incident was investigated and resolved.

## Related Records

The project demonstrates the use of related records such as:

* Child Incidents
* Affected CIs
* Impacted Services/CIs
* Attached Knowledge Articles
* SLAs and Timing Information
* Work Notes
* Resolution Information

These related records provide additional context and help support effective incident management.

## Key Features

* Incident creation and tracking
* Incident lifecycle management
* Impact, urgency, and priority management
* Configuration Item association
* Service and Service Offering association
* Child incident management
* Knowledge article association
* SLA and timing visibility
* Work notes and resolution details
* Incident reopening capability
* Related record management

## ServiceNow Concepts Demonstrated

This project demonstrates practical understanding of the following ServiceNow concepts:

* Incident Management
* Incident Lifecycle
* Impact, Urgency and Priority
* Configuration Management Database (CMDB)
* Configuration Items (CIs)
* Services and Service Offerings
* Knowledge Management
* SLA Management
* Child Incidents
* Related Records
* Resolution Management

## Technologies Used

* ServiceNow
* Incident Management
* CMDB
* Service Management
* Knowledge Management
* SLA Management

## Screenshots

Screenshots demonstrating the ServiceNow Incident Lifecycle Automation implementation are available in the **Screenshots** folder.

The screenshots demonstrate different parts of the project, including:

* Incident details
* Incident lifecycle
* Service and Service Offering
* Configuration Item
* Related Records
* Child Incidents
* Knowledge
* SLA information
* Resolution details

## Project Outcome

This project demonstrates how **ServiceNow Incident Management** can be used to manage incidents from creation through closure.

It shows how incidents can be connected with **business services, service offerings, Configuration Items, knowledge articles, child incidents, and SLA information**, while maintaining proper investigation and resolution details.

The project helped demonstrate practical understanding of ServiceNow's incident management capabilities and its role in improving incident tracking, visibility, and resolution.

## Future Enhancements

The project can be further enhanced by adding:

* Automated incident assignment
* Email notifications
* Automated SLA notifications
* Incident dashboards and reports
* Assignment group automation
* Automated priority calculation
* Flow Designer automation
* Integration with external monitoring tools

## Author

**Meghana**

This project was created as a practical ServiceNow project to demonstrate understanding of **Incident Management, CMDB, Service Management, Knowledge Management, and SLA Management**.
