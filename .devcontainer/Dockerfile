FROM node:16

WORKDIR /workspace

RUN /bin/bash &&\
    apt-get update -y &&\
    apt-get upgrade -y &&\
    npm install -g npm @vue/cli &&\
    apt-get install -y git

CMD /bin/bash