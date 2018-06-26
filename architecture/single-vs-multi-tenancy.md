Single Tenant Vs Multi Tenant Architecture

In Single Tenant Architecture
- Each Tenant gets its own DB, unshared with any other tenant.
- Authorisation between tenants is never a problem.
- moving to on-premise for the client is simpler.
- moving back to a multi tenant application, data migration becomes a night mare. Retaining relationships in particular.
- deployment to multiple clients as the number increases becomes tedious.
- separate features for clients gets piled up and loss of product focus.

In multi Tenant Application
- Each Tenant logs into same application and same database.
- Authorisation between data of different tenants becomes a responsibility if the application.
