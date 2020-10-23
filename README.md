# Simple_chat
Simple_chat using spring Boot and rabbitMQ

Henry Chen 300082076

Run the docker image `docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management`
Navigate to the root folder and enter command `/gradlew bootJar`to generate a Jar subfile in the sub-folder build/libs

In the libs folder, you will find rabbit-chat-0.0.1-SNAPSHOT.jar

Run the created Jar with `java -jar rabbit-chat-0.0.1-SNAPSHOT.jar --chat.alias=Bob`

