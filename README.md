Servers
=======

mvn spring-boot:run -Dserver.port=8761 -Dspring.profiles.active=peer1

mvn spring-boot:run -Dserver.port=8762 -Dspring.profiles.active=peer2



vi /etc/hosts
127.0.0.1   localhost   peer1   peer2


Clients
=======

mvn spring-boot:run -Dserver.port=8080

mvn spring-boot:run -Dserver.port=8081