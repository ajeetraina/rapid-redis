rapid-redis
===========

Simple example to query Twitter and cache results in Redis.

1. Log into Twitter and create an app: [https://apps.twitter.com]()

2. Change config.js to set to your values for Twitter and Redis configuration.

3. Ensure Redis is running (or available remotely).


Before you run the below command, ensure that you have below packages installed

```
npm install twit
```

4. Run `node index.js query` (query is your search text).
