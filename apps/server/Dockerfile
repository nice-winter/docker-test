FROM alpine

RUN echo "[RUN] Token: $TURBO_TOKEN" &&\
  echo "[RUN] Token: $TURBO_TOKEN"

WORKDIR /app

COPY . .

RUN chmod +x test.sh

ENTRYPOINT [ "sh", "test.sh" ]
