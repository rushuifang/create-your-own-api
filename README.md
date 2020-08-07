# create-your-own-api

This repository follows along Andrew Bliss' tutorial at [RapdiAPI Blog](https://rapidapi.com/blog/nodejs-express-rest-api-example/).

There are two main fixes:

1. In /index.js line 16, while using express middleware one should specifiy the required module's name instead of the module's path.
2. In /routes/stats.js, the tutorial didn't define statsFilePath in POST, UPDATA and DELETE methods.
