FROM betrybe/puppetter:1.0
WORKDIR /app/tests
COPY . /app/tests
ADD node_modules.tar.gz /app/tests
ENTRYPOINT ["npm"]
CMD ["test"]
