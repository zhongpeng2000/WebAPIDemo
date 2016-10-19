
add-migration -ConfigurationTypeName SchoolAPI.Migrations.School.Configuration "InitialCreate"

dd-migration -ConfigurationTypeName WebAPIDemo.Migrations.School.Configuration "InitialCreate"
Scaffolding migration 'InitialCreate'

update-database -ConfigurationTypeName WebAPIDemo.Migrations.School.Configuration