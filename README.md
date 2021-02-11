## The Will-CatAPI

<!-- Lincense -->
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


## Welcome to Will-CatAPI!

### This is a project done in PHP to consume a Cat API that contains general information about some breeds of cats.

#### (https://github.com/wilsonribeiro/will-catapi.git)



### For run this project you need have the Docker installed in your machine.

(http://www.docker.com)

(https://docs.docker.com/get-docker/)

### For Debian / Ubuntu operating systems:

~# curl -sSl https://get.docker.com | sh

~# /etc/init.d/docker start

~# docker ps -a


### Now, clonning the project in your machine:

~# git clone https://github.com/wilsonribeiro/will-catapi.git

### Enter in the project directory:

~# cd will-catapi/

### Build the application image and PHP Apache Web Server:

~# docker build -t will-catapi-image .

### Run the application container:

~# docker run -p 3000:80 -d --name will-catapi-app will-catapi-image

### See the Application running in your Web Browser:

(http://localhost:3000/)


### That's right! Well done, congratulations!

###

For more information, please access my profile on [LinkedIn](https://www.linkedin.com/in/wilsonribeiro2/)


Thanks!

Wilson Ribeiro.

### License
<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[Apache 2.0 License](https://github.com/wilsonribeiro/will-catapi/blob/master/LICENSE).
