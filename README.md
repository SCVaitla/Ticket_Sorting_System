# Ticket_Sorting_System
This code is written using groovy

>Database connectivity is established using groovy.sql.Sql, and tickets are retrieved from a hypothetical database with a simple SQL query.
>The forwardTicket method now contains error handling to catch exceptions that might occur during the API request.
>A new method updateTicketStatusInDatabase is added to update the ticket status in the database once it is forwarded successfully.
>Error handling is added in each method to catch and log different exceptions that might occur.

While using this code remember to replace 'jdbc:yourDatabaseURL', 'yourDatabaseUser', 'yourDatabasePassword', and 'yourJDBCDriver' 
with actual values corresponding to your database setup. Also, you'd need to adjust the SQL queries according to your actual database schema.
