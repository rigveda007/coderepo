FROM ubuntu
WORKDIR /var/www/html
RUN apt-get update && \
    apt-get install nginx vim git -y
COPY copy.yml ${WORKDIR}
RUN git clone https://github.com/rigveda007/coderepo.git
ENV name sai
