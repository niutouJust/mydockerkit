## This's a docker compose tools project 

<p>Is development env , local docker in PC , Use portainer manager container for development env</p>

<p>NGinx Port is: 7002</p>
<p>Mysql Port is: 3309</p>
<p>phpmyadmin Port is: 7081</p>
<p>portainer Port is: 6443, Use HTTPS</p>
<p>meilisearch Port is: 7701</p>

### USE


```bash
sudo docker compose -f docker-compose.yml --profile tools-app up -d
sudo docker compose -f docker-compose.yml --profile tools-app down
sudo docker compose -f docker-compose.yml --profile tools-db up -d
sudo docker compose -f docker-compose.yml --profile tools-db down
```

### You can 

```bash
alias dockertool='sudo docker compose -f docker-compose.yml --profile'
```
<p>write to </p>

```bash
~/.bashrc && source ~/.bashrc
```


### And then

```bash
 dockertool tools-app up -d 
```

<p>writeing</p>

### TODO


> - [ ] gitlab-ce
> - [ ] registry