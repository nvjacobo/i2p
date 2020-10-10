# Mirroring i2p website via docker

Steps to install a getip2.net mirror

Requirements

- docker 
- disk space: 294M

Cloning the repository

```
git clone https://github.com/i2p/i2p.www/
```

Into directory 

```
cd i2p.www
```

Set variable -d to detached when deployment done

In file site-updater-docker.sh add line

```
i2p_www_docker_run_args="-d"
```

Deployment

```
./site-updater-docker.sh
```

Finally, you have a web service on the container in port 8090. 


