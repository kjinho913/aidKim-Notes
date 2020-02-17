p{text-indent: 30px;}
# PostgreSQL 

## PostgreSQL schema search_path 작성법
* 스키마 변경 관련 작성법  
    ```
    alter system set search_path = '$usr','public';
    ```
    * 각각 별도로 묶어 주어야 하며 조회시 나오는 "" 입력하지 말아야 한다

* 잘못된 작성법
    ```
    1. alter system set search_path = '"$user"'.'public';
    2. alter system set search_path = '"$user".public';
    3. alter system set search_apth = '$user,public';
    ```
    * 시발거
    * 
## postgreSQL schema 관련



