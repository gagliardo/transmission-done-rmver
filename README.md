# transmission-done-rmver
This script removes 100% downloaded torrents (with data) from Sonarr and Radarr (or any) directories, after a settable period of seeding

## Transmission

set up username, password, host and  port of your Transmission

`Username="your_username"`

`Password="your_password"`

`Host="transmission_ip_address" #localhost?`

`Port="transmission_port" #default is 9091`

## Seeding

Seeding lead time is the time in seconds you want to keep the donwnloaded torrent for seeding.

`SeedingLeadTime="200000"  #seeding leadtime in seconds, after which you want the torrent to be removed 
LogFile="rmver.log"`

## Direcotories

The script will remove only the torrents that are downloaded in the directories you select here. This way you can configure different directories for different services (like Radarr or Sonarr) and keep torrents for the service you want, or for manual downloaded torrents

`Sonarr_dir="Sonarr"`

`Radarr_dir="Radarr"`

`Custom_dir1=""`

`Custom_dir2=""`

`Custom_dir3=""`
