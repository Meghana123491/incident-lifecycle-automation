# ServiceNow Incident Lifecycle Automation

## Project Overview

This project demonstrates an Incident Lifecycle Management implementation in ServiceNow. It covers incident tracking from creation through resolution, along with related services, configuration items, child incidents, knowledge articles, and SLA information.

 ## Objectives

* Manage incidents through their lifecycle.
* Track incident impact, urgency, and priority.
* Associate incidents with affected Configuration Items (CIs).
* Link incidents with services and service offerings.
* Track child incidents and related records.
* Maintain resolution details and work notes.
* Monitor SLA and timing information.

## Service Structure

The project uses the following service structure:

* Service: Remote Access
* Service Offering: Corporate VPN
* Configuration Item (CI): VPN Gateway

The incident is associated with the relevant service offering and affected configuration item to provide better impact and dependency tracking.

## Incident Lifecycle

The incident follows a structured lifecycle:

**New → In Progress → On Hold → Resolved → Closed**

The project also supports reopening an incident when further action is required.

## Incident Details

Example incident used in the project:

Incident: INC0010004
Short Description: Restart VPN-SRV-02 service
Impact: High
Urgency: Medium
Priority: High
Affected CI: VPN Gateway
Service: Remote Access
Service Offering: Corporate VPN

## Resolution Management

The incident records resolution information such as:

* Resolution Code: Workaround provided
* Resolution Notes: Restarted VPN-SRV-02 service as per emergency change request.
* Probable Cause: VPN-SRV-02 service was suspended and required restart.

## Related Records

The project demonstrates the use of related records including:

* Child Incidents
* Affected CIs
* Impacted Services/CIs
* Attached Knowledge
* SLAs and timings

## Technologies Used

* ServiceNow
* Incident Management
* Configuration Management Database (CMDB)
* Service and Service Offering Management
* Knowledge Management
* SLA Management

## Screenshots

Screenshots demonstrating the ServiceNow Incident Lifecycle Automation implementation are included in the `Screenshots` folder.

## Project Outcome

This project demonstrates how ServiceNow can be used to manage incidents, track their lifecycle, connect incidents with business services and configuration items, maintain resolution information, and provide visibility into related records and SLAs.
