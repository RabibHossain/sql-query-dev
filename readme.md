## ENUM COLUMN

* Add New Enum Column
  ```sh
  ALTER TABLE table_name ADD column_name ENUM('owner','editor', 'viewer') NOT NULL DEFAULT 'viewer' after after_column_name;
  ```
  
  * Update Existing Enum Column
  ```sh
  ALTER TABLE table_name MODIFY COLUMN column_name ENUM('owner', 'co-owner', 'editor', 'viewer')  NOT NULL DEFAULT 'co-owner';
  ```
