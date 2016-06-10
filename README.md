# VulsRepo #

VulsRepo is visualized based on the json report output in [vuls](https://github.com/future-architect/vuls).

Demo movie:[https://youtu.be/DIBPoik4owc](https://youtu.be/DIBPoik4owc)


## Installation ##

### Step1. To create a json report of vuls ###

````
$ vuls scan -report-json
````

Write report to JSON files ($PWD/results/current)


### Step2. Http Server install ###

Aapache Http Server or Nginx is installed.

### Step3. Zip download ###

zip is downloaded and developed in a home directories of an http server.

````
$ wget https://github.com/usiusi360/vulsrepo/archive/master.zip
$ unzip master.zip
$ sudo mv ./vulsrepo/src /var/www/html/vulsrepo
````

### Step4. To link to json report ###

````
$ cd /var/www/html/vulsrepo/
$ ln -s <VulsHome>/results/current cullent
````

## Usage ##

To access the browser

````
http://VulsServer/vulsrepo/
````

## Image ##
![image](https://github.com/usiusi360/vulsrepo/img/image001.png)

![image](https://github.com/usiusi360/vulsrepo/img/image002.png)

![image](https://github.com/usiusi360/vulsrepo/img/image003.png)

![image](https://github.com/usiusi360/vulsrepo/img/image004.png)

