```
$ npm install
```

```
$ npm run test
```

You can start [mailhog](https://github.com/mailhog/MailHog):

```
$ docker-compose up -d
```

Access to mailhog: http://127.0.0.1:8025/

```
$ export SMTP_URL="smtp://user:password@127.0.0.1:1025/?pool=true"
```

`user` and `password` must be
[**url encoded**](https://www.w3schools.com/tags/ref_urlencode.asp).

```
$ npm run watch
```


Access to Swagger docs: http://127.0.0.1:5000/docs/