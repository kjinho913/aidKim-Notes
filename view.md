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
