# EF Core

For adding migrations/running updates when you have a dataproject and an api project.
cd project.data
dotnet ef --startup-project ../project.api/ migrations add [MigrationName]
