FROM openjdk:11-jdk-slim-buster
COPY springwebdemo.jar /usr/local/
WORKDIR /usr/local
CMD java -jar springwebdemo.jar

#ARG JAR_NAME
#ENV PROJECT_NAME ${JAR_NAME}
#ENV PROJECT_HOME /usr/local/${PROJECT_NAME}
#
#RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
#RUN echo 'Asia/Shanghai' >/etc/timezone
#RUN mkdir $PROJECT_HOME && mkdir $PROJECT_HOME/logs
#
#ARG JAR_FILE
#COPY ${JAR_FILE} $PROJECT_HOME/${JAR_NAME}.jar
#
#ENTRYPOINT java -jar -Xmn128m -Xms256m -Xmx256m $PROJECT_HOME/$PROJECT_NAME.jar