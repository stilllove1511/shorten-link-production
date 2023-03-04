build or rebuild image
```
docker compose build
```

then run containers
```
docker compose -p <name> up -d
```

```
ssh-keygen
```
then rename the id_rsa.pub to [reanamed]
then config ssh clone
```
mkdir -p ~/.ssh
ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts
```

add key to listen
```
ssh-keygen -l -f [key-file]
```
example
```
ssh-keygen -l -f ~/.ssh/reanamed.pub
```
