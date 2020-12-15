# meta-virtium
x86-64 branch

Prerequisites
-------------

+ A Linux host that meets the requirements for using [Wind River Linux LTS 19](https://docs.windriver.com/category/os_linux_lts_19 "OS Wind River Linux 19")
+ [Git](https://git-scm.com/ "Git project page") (>= 1.9)
+ [Python](https://www.python.org/ "Python project page") (>= 2.7)

Download
-------------
x86-64 platform

    $ git clone -b x86-64 https://github.com/virtiumssd/meta-virtium-manual.git

ARM platform

    $ git clone -b arm https://github.com/virtiumssd/meta-virtium-manual.git

Integration
-------------
+ Copy meta-virtium directory into "your project path/layers"
+ Add line "your project path/layers/meta-virtium \" into "your project path/build/conf/bblayers.conf"
+ Add line "IMAGE_INSTALL_append = " vttestcmd vtsecurecmd vtview dataretentiontest sanitizedemonstration"" into "your project path/build/conf/local.conf"
