# Geth wallet Blockchain

The geth image service cryptonode and daemon need to be started:

```rake service: daemons [start]```

```rake service: cryptonodes [start]```

* This will start the geth container call and its partial installation.

## Now all commands need to use docker and docker-compose.

Init Geth:

```docker run -it geth```


## Create new main eth account:

```docker run -it geth account new```

## Account list:

```docker run -it geth account list```











