Base image from Ubuntu 16.04 owner root
    
    add-architecture i386
    add repository ppa:openjdk-r/ppa

    install openjdk-8 
	    curl, unzip, sudo
    dpkg-reconfigure locales (ru_RU.UTF-8)


Download and install  [Java Cryptography Extension](http://download.oracle.com/otn-pub/java/jce/8/jce_policy-8.zip)

Test Circle CI [![Circle CI](https://circleci.com/gh/ZanyXDev/dev-java-base.svg?style=svg)](https://circleci.com/gh/zanyxdev/dev-java-base)

Docker image info [![](https://images.microbadger.com/badges/image/zanyxdev/dev-java-base.svg)](https://microbadger.com/images/zanyxdev/dev-java-base "Get your own image badge on microbadger.com")
