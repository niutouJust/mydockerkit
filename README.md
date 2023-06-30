## This's a docker compose tools project 

<p>Is development env , local docker in PC , Use portainer manager container for development env</p>

<p>NGinx Port is: 7002</p>
<p>Mysql Port is: 3309</p>
<p>phpmyadmin Port is: 7081</p>
<p>portainer Port is: 6443, Use HTTPS</p>
<p>meilisearch Port is: 7701</p>

### USE

<p>sudo docker compose -f docker-compose.yml --profile tools-app up -d</p>
<p>sudo docker compose -f docker-compose.yml --profile tools-app down</p>
<p>sudo docker compose -f docker-compose.yml --profile tools-db up -d</p>
<p>sudo docker compose -f docker-compose.yml --profile tools-db down</p>

### You can 
<p>alias dockertool='sudo docker compose -f docker-compose.yml --profile'</p>
<p>write to </p>
<p>~/.bashrc && source ~/.bashrc</p>

### And then
<p>dockertool tools-app up -d </p>

<p>writeing</p>

### TODO

[ ] gitlab-ce
[ ] registry