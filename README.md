EventForce – Event Management System
Project Overview
EventForce is a Salesforce-based event management system designed to organize events and manage clients, venues, vendors, and feedback in one place.
Objectives
- Manage event details and schedules.
- Maintain client information.
- Track venue availability.
- Manage vendors associated with events.
- Collect and review client feedback.
- Automate event status updates and reminders.
- Provide reports and dashboards for monitoring event activities.
Salesforce Data Model
The project uses the following custom objects:
- Event – Stores event details, dates, status, and related information.
- Client – Stores client details.
- Vendor – Stores vendor information.
- Venue – Stores venue details and availability.
- Feedback – Stores feedback submitted for events.
- Event Vendor – Connects events with vendors.
Object Relationships
- Event is linked to Client through a lookup relationship.
- Event is linked to Venue through a lookup relationship.
- Feedback is linked to Event and Client through lookup relationships.
- Event Vendor connects Event and Vendor using master-detail relationships.
Main Features
Event Management
Users can create and manage event records, including event dates and statuses.
Venue Availability
Venue availability is managed according to event status. Confirmed events reserve a venue, while canceled events can make it available again.
Double-Booking Prevention
Validation logic helps prevent the same venue from being assigned to overlapping events on the same date.
Automatic Event Completion
Scheduled automation checks event dates and updates past events to Completed.
Notifications and Approvals
Salesforce Flow and approval processes support reminders and event approval workflows.
Reports and Dashboards
Reports and dashboards help users review events, venue usage, and other event-management information.
Security
Salesforce access settings control which users can view or manage project records.
Tools and Technologies
- Salesforce
- Salesforce Objects and Relationships
- Apex Automation
- Salesforce Flow
- Approval Processes
- Reports and Dashboards
Implementation Status
The project was implemented and tested in a Salesforce Developer Edition environment. Production deployment was not part of the implementation described in the project document.
Future Enhancements
- Add more notification options.
- Improve event search and filtering.
- Expand reporting and analytics.
- Prepare and test a deployment package for another Salesforce environment.
Conclusion
EventForce brings event, client, venue, vendor, and feedback management together in Salesforce. Automation and reporting help make event-management tasks more organized and efficient.
