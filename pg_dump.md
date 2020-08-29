# PG_DUMP

## PG_DUMP 사용법

## PG_DUMP option 별 시간 비교

> 10GB database meoery 1GB 

### pg_dump no option
```
postgres@localhost ~]$ source dump.sh
2019. 12. 11. (수) 18:03:00 KST
2019. 12. 11. (수) 18:05:32 KST
```

### pg_dump with -j option (only directory mode)
 ```
[postgres@localhost dump]$ source dump.sh
2019.12. 11. (수) 18:10:29 KST
2019.12. 11. (수) 18:22:39 KST
 ```
 *  새로운 디렉토리가 생성되며 DB의 각 테이블별로 분리 후 압축 파일 형태로 저장
    -> 압축해제시 평문으로 저장


```
[postgres@localhost dump]$ source dump.sh
2019. 12. 11. (수) 18:36:56 KST
2019. 12. 11. (수) 18:49:58 KST
```


### pg_dump -Fc  with -Z option
```
2019. 12. 11. (수) 18:51:09 KST
2019. 12. 11. (수) 19:03:25 KST
```
* Z 9


[postgres@localhost dump]$ source r.sh
2019. 12. 11. (수) 19:44:54 KST
2019. 12. 11. (수) 19:49:57 KST


# 결론
코어수가 1개라 무의미한 실험이었다 시발거
