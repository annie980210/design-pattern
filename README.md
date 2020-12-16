## 개발 환경

- Windows 10 64bit
- Visual Studio Code
- Windows PowerShell

## 실행 방법

#### 프로젝트 폴더 이동 및 콘솔 실행

```shell
> cd 'C:\dp2020'
> java -cp 'C:\dp2020\bin' 'com.holub.database.jdbc.Console'
```

#### 데이터베이스 경로 입력

```
c:/dp2020/Dbase
```

데이터베이스 경로를 입력하라는 창이 뜨는데 그곳에 데이터베이스 경로를 입력한다.

#### SQL 입력

```sql
select * from address;
select * from address where addrId = 0;
```

데이터베이스로 SQL을 보내면 응답이 출력된다.
