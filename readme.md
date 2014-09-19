Self
====

This is the main repository for the Self programming language and environment.

The Self homepage is at http://selflanguage.org

Please go there for prebuilt binaries for Mac OS X and Linux, documentation,
blogs and forums.

For information on:

  * Using Self, read the [Self Handbook][1]
  * Building a Self VM, read the Handbook's [VM building instructions][2]
  * Building a Self World, read the [world building instructions][3]
  
[1]: http://handbook.selflanguage.org/4.5/
[2]: http://handbook.selflanguage.org/4.5/buildvm.html
[3]: http://handbook.selflanguage.org/4.5/buildworld.html

Building On Fedora Linux
------------------------
    # su
    
    # yum install git
    # yum install cmake
    
    # yum install libX11-devel
    # yum install libXext-devel
    # yum install ncurses-devel
    # exit
    
    # git clone https://github.com/AaronNGray/self
    
    # mkdir self-build
    # cd self-build
    # cmake ../self
    # cmake --build .

Building on Debian
------------------
    # su
    # apt-get install xorg-dev
    # apt-get install ncurses-dev
    # apt-get install cmake
    
    # cd vm
    # cmake .
    # cmake --build .
    
    
