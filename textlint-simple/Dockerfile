FROM node:latest
MAINTAINER san-tak

RUN npm install -g textlint \
    && npm install -g \
       textlint-rule-preset-japanese textlint-rule-prh
WORKDIR /work

ENTRYPOINT ["textlint"]
CMD ["-h"]