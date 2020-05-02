#Jumpserver Docker-撰写

#$ git clone https://github.com/jumpserver/Dockerfile.git

#$ cd Dockerfile

#$ cat .env

#$ docker-compose up

#建立

#$ cd Dockerfile

#$ cat .env

#$ docker-compose -f docker-compose-build.yml up

#说明

#.env的变量用在docker-compose里面，可以自己看下可能还有一些替换检测到的问题，尝试自己调试一遍后再使用

#如果自己编译，可以在docker-compose的环境：处加入版本：$ Version，取代Dockerfile的ARG
