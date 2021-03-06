mybatis-generator-gui
==============

mybatis-generator-gui is a mybatis generator GUI tool, used to easy generate mybatis java mapping files and mapper xml file.

![MainUI](https://cloud.githubusercontent.com/assets/3505708/16894610/0416f83a-4b8e-11e6-9a25-904f8d2e5583.png)

### Requirements
This tools require JRE 8.0, if you have JDK or JRE installed, you can download no jre version, otherwise
you need download jre bundled version.

### Downloads
You can download no jre release from here: https://github.com/astarring/mybatis-generator-gui/releases/download/v0.3/mybatis-generator-gui-no-jre.zip

Cause github upload release binary is very very slow, I just upload no jre version
if I found it faster, I will upload the jre bundled version.

### Building from source
    git clone https://github.com/astarring/mybatis-generator-gui
    cd mybatis-generator-gui
    mvn jfx:jar
### Run
* Run mybatis-generator-gui


    cd target/jfx/app/\
    java -jar mybatis-generator-gui.jar

* Run in Eclipse or IntelliJ IDEA, just find the main class MainUI, and run this class.

### Documentation
----
For more information on how to the GUI tool, please reference my wiki page:
* [Usage](https://github.com/astarring/mybatis-generator-gui/wiki/Usage-Guide)


### Contribution
This project currently is only develop by me, if you want's to join, I will
really appreciate and try my best to  improve the functionality, to support this project you can:
* Post thoughts or issues about new features/optimizations that important to you
* Submit bug using one of the following patterns:
    * The step how to reproduce the issue
    * Any snapshot that show the issue is appreciate


------
Licensed under the Apache 2.0 License

Copyright 2016 by Owen Zou
