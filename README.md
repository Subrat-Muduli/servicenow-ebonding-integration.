# ServiceNow-to-ServiceNow E-Bonding Integration

### Project Overview
A unidirectional e-bonding integration built between two ServiceNow personal developer instances (PDIs) to automate incident management workflows across environments.

### Technical Details
* **Domain:** IT Service Management (ITSM) / Application Integration
* **Tech Stack:** ServiceNow (Global Scope), JavaScript, REST API (JSON)
* **Authentication:** Basic Authentication
* **Core Components:** 
  * **Advanced Business Rule:** Triggers asynchronously upon incident insertion to capture record data and execute the integration logic.
  * **Outbound REST Message:** Configured with HTTP POST, PATCH  methods and custom JSON payloads to securely transmit data to the target instance endpoint.

### How to Review
The repository contains the exported ServiceNow Update Set XML file. It captures the complete configuration architecture, including the script logic, REST endpoint mappings, and system properties used for this integration.
