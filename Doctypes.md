# DocTypes & General Tables Structure

## DocType
### Intro
A doctype is a block representing an entity or table.
* E.g. Lead, Sales Order, Employee.

### Components
* Fields(Columns of the table).
* Permissions.
* Scripts(client-side and server-side).
* Reports(The strucutre of pdf reports for a doctype or the so).
* Views(How the document is viewed 

### Remarks
* Doctypes can have titles such `Weird Case` as their Id.
* Insertion a doctype goes through: before_insert -> validate -> on_update -> after_isnert.
