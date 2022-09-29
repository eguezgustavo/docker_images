FROM ubuntu

RUN apt-get update && apt-get install -y git-crypt && \
    mkdir /repo

WORKDIR /repo

CMD ["git-crypt"]
