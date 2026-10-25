# BAI

BAI is a multi-tenant Blazor Server business application built on Clean Architecture. The current implementation includes contact, document, product, picklist, tenant, identity, audit-trail, and system-log workflows.

## Build and run

Install the .NET SDK required by the solution, then run `dotnet build CleanArchitecture.Blazor.slnx` and `dotnet test CleanArchitecture.Blazor.slnx`. Start the web application from `src/Server.UI`.

The repository includes SQL Server, PostgreSQL, and SQLite migrator projects. Supply database and identity configuration locally or through environment variables; do not commit secrets.
