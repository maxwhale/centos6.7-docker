# CentOS6.7-Docker

CentOS verison: 6.7 (64bit)

Root password: LNMP123

## Usage

```docker pull registry.aliyuncs.com/max/centos6.7-docker```

```docker run --restart=always -P -ti --name CentOS registry.aliyuncs.com/max/centos6.7-docker ./run.sh```

```docker run --restart=always -p 30000:80 -p 30001:21 -p 30002:22 -p 30003:3306 -p 30004:6379 -p 30005:11211 -ti --name CentOS registry.aliyuncs.com/max/centos6.7-docker ./run.sh```