# Tomcat

Apache Tomcat stands as one of the foremost and widely utilized web application servers tailored for the Java programming language. It is complemented by a web-based interface referred to as the "Manager," designed to facilitate the administration and management of web applications hosted within the Tomcat environment through the utilization of a standard web browser. Through the Manager interface, users are empowered to seamlessly deploy novel Web Archive (WAR) applications and exercise authoritative oversight over pre-existing instances, all without necessitating a complete restart of the Tomcat server. Access to the Manager interface conventionally occurs by navigating to the URL: hxxp[://]localhost[:]8080/manager/html.

## Usage

```shell
hydra -L better_default_usernames.txt -P better_default_passwords.txt -f localhost -s 8080 http-get /manager/html
```
