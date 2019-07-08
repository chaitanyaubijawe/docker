FROM selenium/node-chrome:latest
RUN sudo apt-get update && \
    sudo apt-get install -y curl

RUN sudo curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

RUN sudo apt-get install -y nodejs
#RUN sudo ln -s /usr/bin/nodejs /usr/bin/node
RUN npm -v
RUN node -v



#RUN sudo ln -s /usr/local/n/versions/node/8.11.1/bin/node /usr/bin/node

RUN sudo wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
RUN sudo sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'

RUN sudo apt-get install google-chrome-stable


#/usr/local/n/versions/node/8.11.1
