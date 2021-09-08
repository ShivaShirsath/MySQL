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
          id         int    (  3   )   NOT NULL  /* ,
      column_name data_type ( size )  constants 
       *
       * specify multiple columns
       * sheparate columns using ‘,’ 
       *
       * id       = column_name
       * int      = data_type 
       * 3        = size
       * NOT NULL = constants
       *
       */
    ) ;
    ```
  - Insert into Table
    ```mysql
    INSERT INTO database_name . table_name
    ( id  /* , column_names */ ) values
    ( 1   /* ,     datas    */ ) /* , 
    ( #1     ,  #2, #3,  …  #N ) 
       
        specify multiple values
        sheparate values using ‘,’
       
       */
    ;
    ```
  - Update 
