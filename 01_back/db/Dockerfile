FROM amazon/dynamodb-local:1.12.0

WORKDIR /home/dynamodblocal

# UID=1000 → DynamoDB Local の実行ユーザ
RUN mkdir data && chown -R 1000 data
