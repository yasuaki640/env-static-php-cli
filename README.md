# env-static-php-cli
An environment for develop https://static-php.dev/en/ .

## memo

### build environment

```shell
docker compose build 
docker compose up -d

# In container
composer update -n
./bin/spc doctor # Answer questions and select "Yes" to all
```