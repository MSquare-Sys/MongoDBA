### Goto /home/mongo location

`[mongo@ip10.20.30.1 ~]$ cd /home/mongo`


### Download BI Connector from MongoDB Website based on the OS (RedHat, CentOS, Ubuntu, SUSE and Debian)

`[mongo@ip10.20.30.1 mongo]$ wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-rhel70-6.0.4.tgz`


### Extract the tar installer

`[mongo@ip10.20.30.1 mongo]$ tar -zxvf https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-rhel70-6.0.4.tgz`


### Rename the folder

`[mongo@ip10.20.30.1 mongo]$ mv mongodb-linux-x86_64-rhel70-6.0.4 mongodb-bi`

[mongo@ip10.20.30.1 mongo]$ ls  
data  log  mongodb  `mongodb-bi`  mongodb-bi-linux-x86_64-rhel70-v2.14.5.tgz  mongod.conf  run


### Configure BI Connector

`[mongo@ip10.20.30.1 mongo]$ cd mongodb-bi`                    // move to mongodb-bi directory

`[mongo@ip10.20.30.1 mongo]$ vi mongod.conf`                   // create new configuration file

