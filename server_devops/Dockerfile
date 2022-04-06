FROM rust:latest

WORKDIR /home/aissata/master1/DD2482-executable-tutorial/server_devops/
COPY . .

RUN cargo install --path .

CMD ["server_devops"]


EXPOSE 7878
