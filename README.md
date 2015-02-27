docker-transmission
==============

Yet another transmission docker image. With kettu interface.

Specially made for private trackers, use it wisely.

docker run -d -P --name="Transmission" -e USERNAME="rpc_username" -e PASSWORD="rpc_password" -v /config:/config -v /downloads:/downloads -v /etc/localtime:/etc/localtime:ro leeroyding/docker-transmission