# sitwdf19_codejam
CodeJam SITWDF19 (2019-01-25)

Presenters: Andre Fischer, Jan Ole Skirke, Benjamin Kernberger

Documents: https://tinyurl.com/codejam-sitwdf-2019

Getting started Tutorial:
1. Create Your First ABAP Console Application https://developers.sap.com/tutorials/abap-environment-console-application.html
2. Expose a Standard Core Data Service for ABAP Environment (Step 9+) https://developers.sap.com/tutorials/abap-environment-business-service-provisioning.html
(following steps could not be done due to missing Cloud Platform Cockpit access)

Booking Tutorial:
1. Create a Simple Database Table for ABAP Environment https://developers.sap.com/tutorials/abap-environment-create-table.html
2. Create and Expose Core Data Services Based on a Database Table https://developers.sap.com/tutorials/abap-environment-create-cds-view.html
3. Add Transactional Behavior to Your Core Data Services https://developers.sap.com/tutorials/abap-environment-transactional-enablement.html (Persistence, Actions, ...only unmanaged behavior yet)

Other tutorials:
1. Create an HTTP Service https://developers.sap.com/tutorials/abap-environment-create-http-service.html
2. Call an External API (with given destination) https://developers.sap.com/tutorials/abap-environment-external-api.html

Demos:
- Create an OData Proxy in ABAP (to call a service in S/4HANA from ABAP Environment)
- Transporting objects from one ABAP Environment instance to another (uses an invisible git repository in the background)

Notes:
- The internal code name for the ABAP Cloud Environment is 'Steam Punk'
- OData V4 is not supported yet but will be supported in the future.
- ABAP Environment is updated bi-weekly.
- Restful ABAP Programming (RAP) Model will also be available on-premise with the next release of S/4HANA called S/4HANA 1909.
- S/4HANA 1809 is based on NetWeaver 7.53, S/4HANA 1909 will probably be based on NetWeaver 7.54.
- Behavior definitions with managed persistence are not yet released so you have to implement read and write access on your business object yourself.
