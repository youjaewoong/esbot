# esbot

ElasticSearch 클러스터 상태 체크를 하는 스크립트를 기술합니다.
* 개발환경 - Python 2.7.10

## esbot 스크립트 설치하기

```bash
[ec2-user@ip-xxx-xxx-xxx-xxx ~]$ sudo yum -y install git
[ec2-user@ip-xxx-xxx-xxx-xxx ~]$ cd /usr/local/
[ec2-user@ip-xxx-xxx-xxx-xxx local]$ sudo git clone https://github.com/benjamin-btn/esbot.git
[ec2-user@ip-xxx-xxx-xxx-xxx local]$ cd esbot
[ec2-user@ip-xxx-xxx-xxx-xxx esbot]$ ./esbot
Usage : ./esbot [options] [Cluster URL]

        i : ES Info
```
