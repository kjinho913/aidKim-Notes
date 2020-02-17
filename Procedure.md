#   Procedure
##  Procedure 소개
* 함수의 단점은 함수 내에서 새로운 transaction을 실행할수 없다. 
* PostgreSQL 11에서부터 트랜잭션을 지원하는 stroe procedure을 지원

## 구문
```
CREATE [OR REPLACE] PROCEDURE procedure_name(parameter_list)
LANGUAGE language_name
AS $$
    stored_procedure_body;
$$;
```

* 먼저, CREATE PROCEDURE절 뒤에 저장 프로 시저의 이름을 지정.
* 다음으로 사용자 정의 함수의 파라미터 목록과 유사한 파라미터 목록을 정의
* 그런 다음 PLpgSQL 및 SQL과 같은 저장 프로 시저에 대한 프로그래밍 언어를 지정
* 그런 다음 해당 AS키워드 다음에 저장 프로 시저 본문에 코드를 배치
* 마지막으로, '$$' 를 두 번 사용하여 저장 프로 시저를 종료
  
 사용자 정의 함수와 달리 저장 프로 시저에는 반환 값이 없다. 필요에 따라 return;을 이용하여 procedure 종료가능


 ## procedure Example

 ```

 ```
