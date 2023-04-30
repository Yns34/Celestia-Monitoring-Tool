# Celestia-Monitoring-Tool
Installation of Monitoring Tool Netdata and Node monitoring

### Upgrades all installed packages 

```console
sudo apt-get update -y
sudo apt-get install -y \
  zlib1g-dev \
  uuid-dev \
  libmnl-dev \
  pkg-config \
  curl \
  gcc \
  make \
  autoconf \
  autoconf-archive \
  autogen \
  automake \
  python \
  python-yaml \
  python-mysqldb \
  nodejs \
  lm-sensors \
  python-psycopg2 \
  netcat \
  git
  ```
  ### Dependencies needed to run Netdata
  
  ```console
  git clone https://github.com/firehol/netdata.git --depth=1 ~/netdata
 ```
 
 ### Enter the Netdata directory and complete the necessary steps

 
   ```console
   cd netdata
 ```
 ```console
 sudo ./netdata-installer.sh
```

You can log in to the web browser using http://yourip:19999 and check the status of the node.


![Netdata in
action](https://user-images.githubusercontent.com/1153921/113440964-449c2180-93a2-11eb-9664-663afa1257a8.gif)









 
 
 
 
 
 
