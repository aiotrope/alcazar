FROM denoland/deno:alpine-1.29.2

EXPOSE 7777

WORKDIR /app

COPY . .

CMD [ "run", "--unstable", "--watch", "--allow-net", "app.js" ]