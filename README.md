![screenshot 2018-10-24 at 12 27 35 pm](https://user-images.githubusercontent.com/40059374/47412063-3c2e6e00-d788-11e8-9d2e-b891c7e72320.png)

<img src="https://user-images.githubusercontent.com/40059374/47410456-83fec680-d783-11e8-87ae-115bbe48e3b9.jpeg" width="48" align="left">
<img src="https://user-images.githubusercontent.com/40059374/47410543-b6a8bf00-d783-11e8-88c6-d964fc35b2fa.png" width="48" align="left">
<img src="https://user-images.githubusercontent.com/40059374/47410599-f8d20080-d783-11e8-9a63-2f0852572355.png" width="48" align="left">
<img src="https://user-images.githubusercontent.com/40059374/47410815-a0e7c980-d784-11e8-8928-6905f2131502.png" width="48" align="left">
<img src="https://user-images.githubusercontent.com/40059374/48661734-d094a380-ea9c-11e8-9b64-5ab07942390f.png" width="48" align="left">
<br/><br/><br/>
<p align="left">
 Hi<br/>
 you will get apache,php7.2,mysql,phpmyadmin with this docker .</p>




### Installation

Let us directly move to the installation part.
### Download repo

choose a suitable directory to work on
```sh
$ mkdir rajdock
$ git init
$ git clone https://github.com/raj1rana/apache-php7.2-mysql57.git
```
### Download Docker
go to www.docker.com and download the suitable version according to your operating system

### Execute docker
``` sh
$ cd /{path to your foler where you cloned the repo}/rajdock
$ ls -la    #to see your docker-compose-yml
$ docker-compose build #wait for the images to install into the docker  
$ docker-compose up -d
$ docker-compose ps  #to see the images and port they are working on
$ Execute Docker contianer :-docker exec -it (contianer name) /bin/bash  #to excute the docker
```
### Thanks to ...
 Abhinav Dobhal for the giudence which he gave me for this repo.  
### check out abhinav dobhal github profile at https://github.com/abhinavdobhal

###### Please comment on the issues if you found any errors while installing this docker 

                                          THANK YOU