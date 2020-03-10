FROM us.gcr.io/grafeas/grafeas-server:v0.1.4
WORKDIR /
COPY ./config.yaml /config.yaml
COPY ./wait.sh /wait.sh
COPY ./start.sh /start.sh
EXPOSE 8080

ENTRYPOINT ["./start.sh"]
