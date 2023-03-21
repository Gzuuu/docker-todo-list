FROM mjgargani/puppeteer:trybe1.0 as todotests

WORKDIR /app

ADD ./node_modules.tar.gz .

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
