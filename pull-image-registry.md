```
HQSML-151665:Step1a pkrish00c$ docker login --username=prabhavy --email=bhavyakm@gmail.com
Flag --email has been deprecated, will be removed in 1.14.
Password:
Login Succeeded
HQSML-151665:Step1a pkrish00c$ docker tag 135ea02133a4 prabhavy/learncontainers:helloworld
HQSML-151665:Step1a pkrish00c$ docker push prabhavy/learncontainers
The push refers to a repository [docker.io/prabhavy/learncontainers]
e48e6b085fbf: Pushed
834b6419aa32: Pushed
98a10cea9190: Pushed
eaf32912b55d: Pushed
9fe54912f2c4: Mounted from library/python
dfa5124255b9: Mounted from library/python
cfbe30543147: Mounted from library/python
590266e37bf8: Mounted from library/python
ba2cc2690e31: Mounted from library/python
helloworld: digest: sha256:e7d426ee941bb69b0a1b54898caf1c82d1bd2753da6efb5b57f0d6d1874b1920 size: 2200
HQSML-151665:Step1a pkrish00c$ docker tag 135ea02133a4 prabhavy/helloworld:1
HQSML-151665:Step1a pkrish00c$ docker push prabhavy/helloworld:1
The push refers to a repository [docker.io/prabhavy/helloworld]
e48e6b085fbf: Pushed
834b6419aa32: Pushed
98a10cea9190: Pushed
eaf32912b55d: Pushed
9fe54912f2c4: Mounted from library/python
dfa5124255b9: Pushed
cfbe30543147: Mounted from library/python
590266e37bf8: Mounted from library/python
ba2cc2690e31: Mounted from library/python
1: digest: sha256:e7d426ee941bb69b0a1b54898caf1c82d1bd2753da6efb5b57f0d6d1874b1920 size: 2200
HQSML-151665:Step1a pkrish00c$ docker images
REPOSITORY                 TAG                 IMAGE ID            CREATED             SIZE
test1                      latest              e53a50f40a3f        3 days ago          163 MB
prabhavy/learncontainers   helloworld          135ea02133a4        5 days ago          99.5 MB
helloworld                 latest              135ea02133a4        5 days ago          99.5 MB
prabhavy/helloworld        1                   135ea02133a4        5 days ago          99.5 MB
ubuntu                     latest              ebcd9d4fca80        8 days ago          118 MB
python                     3.5-alpine          bb453bba35e2        12 days ago         89.3 MB
```
