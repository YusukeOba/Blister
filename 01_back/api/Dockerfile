FROM golang:1.13

# 作業dirの確定
WORKDIR /go/src

# ホストのファイルをコンテナの作業ディレクトリとして確定
ADD ./src /go/src

RUN go build .

COPY entrypoint.sh /usr/bin/
RUN chmod +x /usr/bin/entrypoint.sh
ENTRYPOINT ["entrypoint.sh"]
