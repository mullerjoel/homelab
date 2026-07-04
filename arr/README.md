# Plexserver

Set the config folders:

```shell
mkdir -p ~/config/plex/config ~/config/plex/transcode
```

Start the docker compose file in this directory with `docker compose up -d` and then configure everything in following link: `http://192.168.0.37:32400/web`


```shell
mkdir -p /home/joel/config/{qbittorrent,sonarr,radarr,prowlarr,bazarr,jellyseerr,jellyfin,recyclarr} && sudo chown -R 1000:1000 /home/joel/config
```
 
```shell
sudo mkdir -p /mnt/hdd01/data/{torrents/{tv,movies,music},media/{tv,movies,music}}
sudo chown -R 1000:1000 /mnt/hdd01/data
```
