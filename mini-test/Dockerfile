FROM openjdk:17-jdk-alpine
ADD https://piston-data.mojang.com/v1/objects/59353fb40c36d304f2035d51e7d6e6baa98dc05c/server.jar /minecraft/server.jar

RUN echo "eula=true" > eula.txt
EXPOSE 8888

CMD ["java", "-Xmx1024M", "-Xms1024M", "-jar", "server.jar", "--port", "8888", "nogui"]


