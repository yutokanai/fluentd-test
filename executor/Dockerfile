FROM fluent/fluentd:v1.18-1
USER root
# 動作確認でコンテナに入るためにbashを追加 / コンテナ間の疎通確認のためpingを追加
RUN apk add --no-cache bash && apk add --no-cache iputils-ping
USER fluent
