Conventions:

Time:
Server and all data is kept in UTC.
If required, timezone information is stored with data, otherwise, converts to localtime on the client view

Collection hooks are used and established for all collections that have linked data. i.e. if one record is updated, modified or deleted, any related records make the required changes. Strive for configurability.

Make subscribe as detailed as possible for each use case.

Unit and Acceptance tests for all features and functions from the beginning.

Use Flux Dispatcher Pattern

Use Package Pattern, isolate features as much as possible

All items of data have to be mapped to a security provision so that access can be checked, all access is denied by default
-Potentially use roles package role: 'security-basic-rights' 'security-admin-rights' 'security-financial-rights', etc






