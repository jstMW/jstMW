<https://romanzipp.com/blog/maocs-sequoia-docker-resetta-is-only-intended-to-run-silicon>

# wakapi-readme-stat

## what is it?
A modified fork of [wakatime-readme-stat from ](https://github.com/anmol098/waka-readme-stats), it is now able to
 - use your own hosted [wakapi server](https://github.com/muety/wakapi)
 - [closed pr](https://github.com/anmol098/waka-readme-stats/pull/525/files#conversations-menu)


## secrets for wakapi-readme-stat
- GH_TOKEN
- WAKAPI_API_KEY
  - wakapi api key **no need to encode it!**
- WAKAPI_URL
  - url that you host your wakapi server
- WAKAPI_USRE
  - your wakapi username

## Docker Image

I just use the fork code for now I upload the docker image to [my dockerhub](https://hub.docker.com/r/lonelydcok/wakapi-readme-stat)

### Commands:
to make you own:
 ```bash
docker build --platform linux/amd64 . -f Dockerfile -t your_own_repo
docker push your_own_repo
```
then add that in github workflow config

## Github workflow

Chalenges:
issues:


# selfHosting Wakapi

## cloudflare dns

## nginx configuratio

### ssl :()

## install default-mysql-server

## add systemd/system/wakapi.service

## install go azure

## folow the instructions

## harden config.yml

### error for systemd wakapi.service: Main process exited, code=exited, status=217/USER

user and group is not defined :_)



db can't be accessed and htis helped me,just permission of the dir :( took me about 4-5 hours. https://community.grafana.com/t/problems-with-error-checking-db-error-checking-for-valid-sqlite-file-unable-to-open-database-file-out-of-memory-14/92025/2


great to start: https://insights.ditatompel.com/en/tutorials/running-wakapi-a-self-hosted-wakatime-compatible-backend-for-coding-stats/

## Docker:

I made the docker in arm64 but this helped me to make it for github actions platform specific amd64: https://www.digitalocean.com/community/tutorials/how-to-build-go-executables-for-multiple-platforms-on-ubuntu-16-04

https://romanzipp.com/blog/maocs-sequoia-docker-resetta-is-only-intended-to-run-silicon


good thing to consider: https://github.com/muety/wakapi/issues/318

about serviced: https://systemd.io/CREDENTIALS/, refered here: https://github.com/muety/wakapi/blame/master/etc/wakapi.service


next step to show stats https://github.com/MacroPower/wakatime_exporter, https://grafana.com/grafana/dashboards/12790-wakatime-coding-stats/


client side: https://github.com/wakatime/wakatime-cli


there are alternatives like activity watch which i use for my own personal use not to put in public, https://docs.activitywatch.net/en/latest/examples/extending.html
but you have to match or write your own program to utilize its api.
## github
workflow: one of my issues was specifing the path of action.yml not in a repo that i cloned or forked or in marketplace. but rather in the .github itself. here are some resources and github issues


A neat project you can use is this: https://github.com/vn7n24fzkq/github-profile-summary-cards




SECURITY:
https://app.pentest-tools.com/login
https://app.snyk.io/org/jstmw/integrations
qodana
azure
github and docker


