# Zabbix-Proxy-Docker

Comandos úteis: 

Buildar a imagem - docker build -t nagixti/zabbix-proxy:v1.0 .

Enviar para o Registry - docker push nagixti/zabbix-proxy:v1.0

Adicionar TAG à imagem - docker tag nagixti/zabbix-proxy:v1.0 docker.io/nagixti/zabbi-proxy

Baixar a imagem: docker pull nagixti/zabbix-proxy:v1.0

-----

Fazer o download do Script proxy-install.sh através do comando: 
```
wget https://raw.githubusercontent.com/msmello96/Docker/refs/heads/main/Proxy/proxy-install.sh
```
```
chmod +x /tmp/proxy-install.sh
```
```
mkdir /var/opt/zabbix
```
```
echo 114db417461b96a676f8f1ac372370cc8e7300a552cd27aeed89761368d3755b > /var/opt/zabbix/.zabbix-key.psk
```
```
./proxy-install.sh
```

Executar e preencher as informações solicitadas.

