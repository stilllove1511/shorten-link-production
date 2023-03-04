build or rebuild image
```
docker compose build
```

then run containers
```
docker compose -p <name> up -d
```

genrate id_rsa.pub
```
ssh-keygen
```
then rename the id_rsa.pub to [reanamed]
then config ssh clone
```
mkdir -p ~/.ssh
ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts
```
change config (view tutorial on deploys key multiple repo)
