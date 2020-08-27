FROM maven:3.6.3-jdk-8

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get install -y nodejs
RUN npm install serverless -g

CMD ['npm', '--version']
