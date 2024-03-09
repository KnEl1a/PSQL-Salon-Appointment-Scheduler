Learned in https://www.freecodecamp.org/
## Postgres SQL

** The script creates a database named `salon` **
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

