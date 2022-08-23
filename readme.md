# 관계형 데이터베이스의 필요성
    테이블을 분리하여 데이터의 중복을 제거해줌.
    My SQL을 이용하여 저장할 땐 분산, 확인할 땐 합쳐서 보여줌.

# JOIN
    분리된 테이블을 읽을 때 통합해줌.

    SELECT * FRON DB1 LEFT JOIN DB2 ON DB1.연결할 컬럼 = DB2.연결할 컬럼
    -> 테이블과 테이블 간의 값을 연결해줌.

    AS : 값을 변경해줌.
    
    테이블을 분리함으로써 데이터 하나를 바꾸면 관련있는 모든 테이블의 정보를 자동으로 수정 가능.

# 데이터 베이스 서버
    인터넷 : 정보를 요청하고 응답하면서 동작하는 서비스.(클라이언트<->서버)

    MySQL 데이터 베이스 서버
    데이터베이스 클라이언트(MySQL 명령어 기반 프로그램) <-> 데이터베이스 서버

# MySQL 클라이언트
    CUI(명령어) 기반 프로그램.
    
# MySQL Workbench
    GUI 기반 프로그램.

    SQL을 MySQL 서버에 전송함으로써 데이터베이스 서버를 제어.


