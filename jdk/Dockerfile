FROM java:openjdk-8u66-jdk

RUN echo openjdk-8-jdk hold | dpkg --set-selections
RUN echo openjdk-8-jre hold | dpkg --set-selections
RUN echo openjdk-8-jre-headless hold | dpkg --set-selections
RUN apt-get update;
RUN apt-get dist-upgrade -y;
