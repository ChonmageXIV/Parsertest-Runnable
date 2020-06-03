1.
Installera jdk1.8.0_251, apache-zookeeper-3.6.1-bin, kafka_2.12-2.5.0 
och apache-maven-3.6.3 i C:

2.
Skapa miljövariablerna "JAVA_HOME", "M2_HOME", "MAVEN_HOME" och "ZOOKEEPER_HOME" 
Lägg sedan till deras \bin och "C:\kafka_2.12-2.5.0\bin\windows" i 'Path'

3.
Kör start-zookeeper.cmd 
(kolla så att addressen i kommandot stämmer överrens med installationsvägen)

4.
Kör start-kafka.cmd
(kolla så att addressen i kommandot stämmer överrens med installationsvägen)

5.
Kör create-topic.cmd

6.
Kör consumer och bekräfta ditt output path
Exempel i CMD: Java -jar C:\Arbetsprov-Bergefur\Consumer.jar

Exempel för output path (exkluderar filnamn):
C:/arbetsprov/arbetsprov-java-parser/

7.
Kör producer och bekräfta din input path
Exempel i CMD: Java -jar C:\Arbetsprov-Bergefur\Producer.jar

Exempel för input path (inkluderar filnamn):
C:\arbetsprov\arbetsprov-java-parser\syslog.txt

----KLART----