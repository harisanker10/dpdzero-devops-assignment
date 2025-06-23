FROM ghcr.io/astral-sh/uv:alpine
RUN apk add curl

WORKDIR /app
COPY . .

CMD ["uv","run","app.py"]
