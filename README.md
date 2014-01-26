webtools
========

Web Interface for Autonomous Robot

Node.js is the underlying web framework for this project. It depends on [roslibjs](https://github.com/RobotWebTools/roslibjs) package.


Installation:

    1. install [roslibjs](https://github.com/RobotWebTools/roslibjs/blob/devel/utils/README.md)
    
    2. install webtools
        git clone https://github.com/Autonomous-Robot/webtools.git
      
Configuration:

    1. Change IP in file views/layout.jade
        url:'ws://<ip-address>:9090'
        9090 is the default port number
    2. Change topic name 
        name : '/chatter',
        
Run:

    In the webtools folder
        node app.js
