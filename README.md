# dev-java-base
Base image from Ubuntu 16.04
    
    add-architecture i386
    add repository ppa:openjdk-r/ppa

    install openjdk-8 
	    curl, unzip, sudo
    dpkg-reconfigure locales (ru_RU.UTF-8)
    Download and install  [Java Cryptography Extension](http://download.oracle.com/otn-pub/java/jce/8/jce_policy-8.zip)
    create user developer

[![Circle CI](https://circleci.com/gh/ZanyXDev/dev-java-base.svg?style=svg)](https://circleci.com/gh/zanyxdev/dev-java-base)

