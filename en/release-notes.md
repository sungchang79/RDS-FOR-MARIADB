## Database > RDS for MariaDB > Release Notes

### March 15, 2022

#### Added Features

* Added a feature to use variables in **DB configuration**

#### Bug Fixes

* Fixed an issue where monitoring data is not collected under certain conditions
* Fixed an issue where an automatic backup of failed-over instance is not deleted
* Fixed an issue where an automatic backup that has failed to be created is not deleted when it reaches its expiration date
* Fixed an issue where restoration fails when there are too many users registered in MySQL
* Fixed an issue where a backup settings modification event is logged even when the access rule is modified

### January 11, 2022

#### Added Features

* Added a feature to check the running process list and InnoDB status in MariaDB

#### Feature Updates

* Changed the minimum length of the name that can be entered when creating a DB schema in the web console to 1 character, which is the same as that of MySQL

### December 14, 2021 

#### New Releases 

- TOAST Relational Database Service (RDS) provides Relational Database in the cloud environment. 
- No complicated configuration is required to enable relational database. 
- Supports MariaDB 10.3.30.  
