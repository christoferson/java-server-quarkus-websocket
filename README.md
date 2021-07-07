# java-server-quarkus-websocket





###

mvn compile quarkus:dev

### Generate

mvn io.quarkus:quarkus-maven-plugin:2.0.0.Final:create \
 -DprojectGroupId="org.demo" \
 -DprojectArtifactId="java-server-quarkus-websocket" \
 -Dextensions="resteasy,resteasy-jackson" \
 -DnoExamples

### Extensions

quarkus:add-extension -Dextensions="websockets"