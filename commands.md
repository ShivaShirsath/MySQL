# Commands

+ At NULL database level
  - Show All DataBases
    ```mysql
    SHOW databases ;
    ```
  - Create Database
    ```mysql
    CREATE DATABASE database_name ;
    ```
  - Show Currunt Database
    ```mysql
    SELECT dataBase() ;
    ```
  - Create Table
    ```mysql
    CREATE TABLE database_name . table_name (
      id int (3) NOT NULL
      /*
       * specify multiple columns
       * sheparate columns using ‘,’ 
       *
       * id       = column name
       * int      = data_type 
       * 3        = size
       * NOT NULL = CONSTANTS
       *
       */
    ) ;
    ```
