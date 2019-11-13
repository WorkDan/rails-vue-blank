FROM node:10

WORKDIR /app

# Add a script to be executed every time the container starts.
COPY docker/frontend/entrypoint.sh /usr/bin/
RUN chmod +x /usr/bin/entrypoint.sh
ENTRYPOINT ["entrypoint.sh"]

EXPOSE 8080

CMD ["yarn", "serve"]
