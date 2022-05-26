FROM openjdk:11
COPY src/calculatorjava/calculator.java /tmp
WORKDIR /tmp
 RUN ["javac","calculator.java"]
 ENTRYPOINT ["java","calculator"]
