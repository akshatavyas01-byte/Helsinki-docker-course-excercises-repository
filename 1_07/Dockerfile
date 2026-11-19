FROM ubuntu:24.04 

WORKDIR /usr/scr/app

COPY script.sh .

RUN apt-get update && apt-get install -y curl && chmod +x script.sh

CMD ["./script.sh"]