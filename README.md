---------------------------------------------------------------------------------------------
                    ☆★ docker-compose up 하기 전 server.xml 파일 설정 ★☆

String dbURL = "jdbc:mariadb://mariadb-host_ip:3306/my_project"; 부분에서 

mariadb-host-ip 부분은 각각 연결할 RDS의  endpoint 주소로 변경해서 저장한 후 build 해주어야 합니다. 

----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------
                    ☆★ http의 conf/workers.properties 파일 host 이름 설정 ★☆

workers.properties 파일의 worker.host 부분에서 

host의 이름은 해당 tomcat 의 service discovery 이름을 지정

----------------------------------------------------------------------------------------------
