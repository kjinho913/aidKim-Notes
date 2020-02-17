# EDB & PostgreSQL catalog table / View 목록
## EPAS 전용 
|VIEW NAME	| DESCRIPTION|
|-----------|------------|
|all_objects |현재 로그인 한 사용자가 액세스 할 수 있는 모든 개체|
|all_synonyms |모든 시노늄|
|all_tab_columns|현재 로그인 한 사용자가 액세스 할 수 있는 모든 테이블의 모든 열|
|all_tables|현재 로그인 한 사용자가 액세스 할 수 있는 모든 테이블|
|all_users|모든 데이터베이스 사용자의 목록.|
|all_view_columns|모든보기의 모든 열 목록 – 비 오라클 표준.|
|all_views|모든 뷰의 목록|
|DBA_role_privs|모든 역할에 할당 된 모든 권한 목록|
|DBA_roles|모든 데이터베이스 역할 목록|
|product_component_version |버전 관련 정보.|
|user_objects|현재 로그인 한 사용자가 소유 한 모든 개체|
|user_synonyms|현재 로그인 한 사용자가 액세스 할 수 있는 모든 시노늄.|
|user_tab_columns|현재 로그인 한 사용자가 소유 한 모든 테이블의 모든 열|
|user_tables|현재 로그인 한 사용자가 소유 한 모든 테이블.|
|user_view_columns|현재 사용자가 소유 한 뷰의 모든 열 목록 – 비 오라클 표준.|
|user_views|현재 사용자가 소유 한 모든보기의 목록입니다|
|sysindexes| 모든 인덱스|
|sysobjects       | 모든 오브젝트|
|systables        | 모든 테이블|
|systypes         | 모든 데이터 타입|
|sysusers         | 모든 유저|
|edb_package      | 모든 pacage와 코드|
|edb_pkgelements  | All package spec level procedure and function declarations.|
## EPAS & PostgreSQL
|VIEW NAME	| DESCRIPTION|
|-----------|------------|
|pg_aggregate     | 제공된 SQL을 포함하여 정의 된 모든 집계 함수|
|pg_am            | 모든 인덱스 액세스 방법.|
|pg_amop          | 모든 액세스 방법 연산자|
|pg_amproc        | 모든 액세스 방법 절차.|
|pg_attrdef       | 모든 열 기본값|
|pg_attribute     | 모든 테이블 열|
|pg_authid        | 승인 된 모든 사용자 및 그룹 (역할).|
|pg_auth_members  | 역할 간의 관계.|
|pg_autovacuum    | 테이블 별 자동 진공 설정.|
|pg_buffercache   | buffercache의 쿼리에 대한 실시간 정보.|
|pg_cast          | 가능한 모든 데이터 유형 캐스트.|
|pg_class         | 모든 테이블과 같은 객체.|
|pg_constraint    | 정의 된 모든 제약|
|pg_conversion    | 언어 인코딩 정보.|
|pg_database      | 현재 클러스터의 모든 데이터베이스에 대한 정보|
|pg_depend        | Oracle의 all_dependcies와 같은 객체 간 종속성|
|pg_description   | 데이터베이스 객체 설명.|
|pg_function      | 데이터베이스의 모든 기능|
|pg_group         | 모든 데이터베이스 그룹|
|pg_index         | 인덱스 정보.|
|pg_indexes       | 테이블 인덱스 정보.|
|pg_inherits      | 부모 / 자식 테이블 상속 관계.|
|pg_language      | 모든 절차 언어 정의 (PL / pgSQL과 유사)|
|pg_largeobject   | lo_ * 지원 기능을 통해 채워진 큰 오브젝트.|
|pg_locks         | 데이터베이스의 모든 트랜잭션 잠금|
|pg_namespace     | 스키마 정보.|
|pg_opclass       | 인덱스 액세스 방법.|
|pg_operator      | SQL 연산자|
|pg_pltemplate    | 사전 정의 된 절차 언어에 대한 템플릿 데이터.|
|pg_prepared_xacts| 2 단계 커밋 트랜잭션 준비.|
|pg_proc          | 모든 저장 프로 시저 및 기능|
|pg_procedure     | 모든 사용자 저장 프로 시저|
|pg_rewrite       | 쿼리 다시 쓰기 규칙|
|pg_shadow        | 모든 데이터베이스 사용자|
|pg_shdepend      | 공유 객체, 즉 사용자 / 테이블 / 역할에 대한 종속성|
|pg_stat_*        | 일반적인 서버 활동 및 행 수준 액세스 통계|

|pg_statio_*      | 디스크 블록 레벨 액세스 통계.|
|pg_statistic     | 플래너 통계.|
|pg_stats         | pg_statistic 이상의 정보|
|pg_synonym       | 모든 시노늄.|
|pg_tablespace    | 모든 테이블 스페이스|
|pg_trigger       | 모든 트리거.|
|pg_type          | 모든 데이터베이스 데이터 유형|
|pg_roles         | 모든 데이터베이스 역할|
|pg_rules         | 모든 데이터베이스 규칙.|
|pg_settings      | 매개 변수 설정을 변경하거나 보는 트랜잭션 방법.|
|pg_tables        | 모든 테이블.|
|pg_user          | 모든 데이터베이스 사용자|
|pg_views         | 모든 데이터베이스 뷰|


## pg_stat_* / pg_statio 상세 항목
|VIEW NAME	| DESCRIPTION|
|-----------|------------|
|pg_stat_activity                  | 서버 프로세스 당 하나의 행으로 상태 및 현재 쿼리와 같은 해당 프로세스의 현재 활동과 관련된 정보를 표시     |
|pg_stat_all_indexes               | 현재 데이터베이스의 각 인덱스에 대해 하나의 행으로, 해당 특정 인덱스에 대한 액세스에 대한 통계가 표시
|pg_stat_all_tables                | 현재 데이터베이스의 각 테이블마다 하나의 행으로, 해당 특정 테이블에 대한 액세스에 대한 통계가 표시
|pg_stat_archiver                  | WAL 아카이버 프로세스 활동에 대한 통계를 표시
|pg_stat_bgwriter                  | 백그라운드 기록기 프로세스의 활동에 대한 통계 표시
|pg_stat_database                  | 데이터베이스 전체에 대한 통계를 보여주는 데이터베이스 당 하나의 행으로 표시
|pg_stat_database_conflicts        | 대기 서버에서의 복구와의 충돌로 인한 쿼리 취소에 대한 데이터베이스 전체 통계
|pg_stat_progress_vacuum           | 각 백엔드 process 별 VACUUM현재 진행 상황을 보여주는
|pg_stat_replication               | WAL sender process 당 하나의 행으로, sender에 연결된 stand by 서버로의 복제에 대한 통계가 표시
|pg_stat_ssl                       | 연결 당 하나의 행 (일반 및 복제)으로이 연결에 사용 된 SSL에 대한 정보가 표시
|pg_stat_subscription              | 서브 스크립 션 작업자에 대한 정보를 표시
|pg_stat_sys_indexes               | pg_stat_all_indexes시스템 테이블의 인덱스 만 표시된다는 점을 제외하고 와 동일
|pg_stat_sys_tables                | pg_stat_all_tables시스템 테이블 만 표시된다는 점을 제외하고 와 동일 
|pg_stat_user_functions            | 추적 된 각 기능에 대해 한 행씩 해당 기능의 실행에 대한 통계를 표시
|pg_stat_user_indexes              | pg_stat_all_indexes사용자 테이블의 인덱스 만 표시된다는 점을 제외하고 와 동일
|pg_stat_user_tables               | pg_stat_all_tables사용자 테이블 만 표시된다는 점을 제외하고 와 동일
|pg_stat_wal_receiver              | 해당 수신자의 연결된 서버에서 WAL 수신자에 대한 통계를 표시
|pg_stat_xact_all_tables           | pg_stat_all_tables와 비슷하지만 pg_stat_all_tables 및 관련 뷰에 아직 포함되지 않은 현재 트랜잭션 내에서 지금까지 수행 한 작업을 계산
|pg_stat_xact_sys_tables           | pg_stat_xact_all_tables시스템 테이블 만 표시된다는 점을 제외하고 와 동일 합
|pg_stat_xact_user_functions       | pg_stat_user_functions과 비슷하지만 현재 트랜잭션 (pg_stat_user_functions에 아직 포함되지 않은) 동안의 call만 계산
|pg_stat_xact_user_tables          | pg_stat_xact_all_tables사용자 테이블 만 표시된다는 점을 제외하고 와 동일 합니다.
|pg_statio_all_indexes             | 현재 데이터베이스의 각 인덱스마다 하나의 행으로, 해당 특정 인덱스의 I / O에 대한 통계가 표시
|pg_statio_all_sequences           | 현재 데이터베이스의 각 시퀀스마다 하나의 행으로, 해당 특정 시퀀스의 I / O에 대한 통계가 표시
|pg_statio_all_tables              | 현재 데이터베이스의 각 테이블마다 하나의 행으로, 해당 특정 테이블의 I / O에 대한 통계가 표시
|pg_statio_sys_indexes             | pg_statio_all_indexes시스템 테이블의 인덱스 만 표시된다는 점을 제외하고 와 동일
|pg_statio_sys_sequences           | pg_statio_all_sequences시스템 시퀀스 만 표시된다는 점을 제외하고 와 동일
|pg_statio_sys_tables              | pg_statio_all_tables시스템 테이블 만 표시된다는 점을 제외하고 와 동일
|pg_statio_user_indexes            | pg_statio_all_indexes사용자 테이블의 인덱스 만 표시된다는 점을 제외하고 와 동일
|pg_statio_user_sequences          | pg_statio_all_sequences사용자 시퀀스 만 표시된다는 점을 제외하고 와 동일
|pg_statio_user_tables             | pg_statio_all_tables사용자 테이블 만 표시된다는 점을 제외하고 와 동일
|pg_statistic                      | 
|pg_statistic_ext                  | 
|pg_statistic_ext_name_index       | 
|pg_statistic_ext_oid_index        | 
|pg_statistic_ext_relid_index      | 
|pg_statistic_relid_att_inh_index  | 