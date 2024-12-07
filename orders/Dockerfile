FROM gradle:jdk17

COPY --chown=gradle:gradle . /app
WORKDIR /app
#RUN ./gradlew build

EXPOSE 8083
WORKDIR /app

CMD java -jar ./build/libs/orders-0.0.1-SNAPSHOT.jar