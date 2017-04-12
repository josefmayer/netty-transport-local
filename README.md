## Netty Local Transport
Building a simple echo server with Netty framework. <br />
Local transport inside JVM via pipes.<br />
Application reads user input from CLI, client prints echo.


### Technologies
Netty, LocalServerChannel



### Steps
Compile: <br />
*mvn clean compile*

Run Server and Client: <br />
*mvn exec:java -Dexec.mainClass="io.netty.example.localecho.LocalEcho"*




