查找镜像：
docker ps -a

docker start civi-1
docker exec -it civi-1 /bin/bash

检测后台：
ps aux | grep -E 'apt|dpkg' | grep -v grep


检测版本：
python3.10 --version
python3.10 -m pip --version

