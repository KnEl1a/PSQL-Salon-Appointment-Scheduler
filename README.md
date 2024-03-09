Learned in https://www.freecodecamp.org/
## Postgres SQL

The script creates a database named `salon` :
 It then defines three tables:
    * `appointments`: stores information about appointments, including customer ID, service ID, and time (as a string).
    * `customers`: stores customer information, including ID, phone number, and name.
    * `services`: stores information about services offered by the salon, including ID and name.
* The script creates sequences to generate unique IDs for each table.
* It also sets some default values and constraints, including:
    * Primary keys for each table to uniquely identify each record.
    * A unique constraint on the phone number in the `customers` table to ensure no duplicate entries.
    * Foreign keys in the `appointments` table referencing the `customers` and `services` tables to ensure data integrity.

In essence, this script defines a schema for a salon management system database, allowing you to store and manage appointments, customer information, and offered services.

## Advanced Bash Scripting: 

#### Summary of the .sh file

** This script .sh is a quotation reserve system for a beauty salon. **

** Functions: **

*** Show a list of services available. **
*** Allow the user to choose a service for id. **
*** Request the customer phone number. **
**Verify if the customer exists in the database. **
*** If the client is new: **
     *** Request the customer name. **
     *** Add customer information to the database. **
*** Request the desired time for the appointment. **
*** Add the appointment to the database. **
*** Confirm the customer appointment. **

** Workflow: **

1. A menu is shown with the list of services available.
2. The user chooses a service for ID.
3. The customer phone number is requested.
4. It is verified if the customer exists in the database.
5. If the client is new, his name is requested and added to the database.
6. The desired time for the appointment is requested.
7. The appointment is added to the database.
8. The meeting of the client is confirmed.

** Variables: **

* `PSQL`: Command to connect to the database.
* `Services`: List of services available.
* `Service_id_Selected`: ID of the service chosen by the user.
* `Customer_Phone`: customer phone number.
* `Customer_name`: customer name (if new).
* `Service_name`: Name of the chosen service.
* `Service_Time`: Desired time for the appointment.
* `Customer_id`: Customer ID in the database.
* `Appaint_inclusion`: Result of the insertion of the appointment in the database.

**Note:**

* This script uses the `PSQL` variable to connect to the database. Be sure to replace it with the information of your own database.
