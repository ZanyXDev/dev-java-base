# dev-java-base
Base image from Ubuntu 16.04
    
    add-architecture i386
    add repository ppa:openjdk-r/ppa

    install openjdk-8 
	    curl, unzip, sudo
    dpkg-reconfigure locales (ru_RU.UTF-8)
    Download and install  [http://download.oracle.com/otn-pub/java/jce/8/jce_policy-8.zip](http://download.oracle.com/otn-pub/java/jce/8/jce_policy-8.zip "Java Cryptography Extension").
    create user developer

[![Circle CI](https://circleci.com/gh/ZanyXDev/dev-java-base.svg?style=svg)](https://circleci.com/gh/zanyxdev/dev-java-base)

