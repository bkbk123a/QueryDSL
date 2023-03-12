# QueryDSL
Java JPA QueryDSL

- 데이터베이스 생성
	- docker run -d -p 1521:1521 -p 8081:81 -v /mnt/c/User/directory/h2:/opt/h2-data -e H2_OPTIONS="-ifNotExists" --name=h2 oscarfonts/h2

- API 테스트
	- http://localhost:8080/v1/members?teamName=teamB&ageGoe=31&ageLoe=35
	- http://localhost:8080/v2/members?size=5&page=2