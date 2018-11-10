#### macOSX 10.11.6下通过brew install mongodb安装mongodb时出现错误

`mongodb: A full installation of Xcode.app 8.3.2 is required to compile this software. Installing just the Command Line Tools is not sufficient. Xcode can be installed from the App Store. Error: An unsatisfied requirement failed this build.` 

#### 解决方法

1. `$ brew link --force mongodb@3.0` 
2. `$ echo 'export PATH="/usr/local/opt/mongodb@3.0/bin:$PATH"' >> ~/.bash_profile` 