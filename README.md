# Mongodb

Simple MongoDB interaction examples from R.

## Prerequisites

A local mongodb instance needs to be found, either using Docker:

```bash
docker pull mongo
docker run --name some-mongo -p 27017:27017 -d mongo
```

Or get it from MongoDB's [official website](https://www.mongodb.com/try/download/community).