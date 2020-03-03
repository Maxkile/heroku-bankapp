FROM openjdk:11
WORKDIR ../docker-bankapp
COPY bankapp.jar bankapp.jar
COPY bankapp-start.sh bankapp-start.sh

ADD https://github.com/ufoscout/docker-compose-wait/releases/download/2.7.3/wait /wait
RUN chmod +x /wait

RUN chmod +x bankapp-start.sh

CMD /wait && ./bankapp-start.sh
