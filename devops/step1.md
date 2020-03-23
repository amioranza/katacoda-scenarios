Executar no terminal 01

```
git clone https://github.com/amioranza/setrem.git && \
cd setrem && \
docker-compose -f katacoda/docker-compose-host01.yaml up -d
```{{execute HOST1}}

Executar no terminal 02

```
git clone https://github.com/amioranza/setrem.git && \
cd setrem && \
docker-compose -f katacoda/docker-compose-host02.yaml up -d
```{{execute HOST2}}

#### Dashboards

**Jenkins**

`echo [[HOST_IP]]`{{execute HOST1}}

`echo https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].[[KATACODA_DOMAIN]]`{{execute HOST1}}

**Gitlab**

`echo [[HOST_IP]]`{{execute HOST2}}

`echo https://[[HOST_SUBDOMAIN]]-8088-[[KATACODA_HOST]].[[KATACODA_DOMAIN]]`{{execute HOST2}}