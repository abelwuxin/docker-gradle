# docker-gradle
docker-gradle with OpenJDK 7

# Sampile

我编译的版本：
registry.aliyuncs.com/abeldeng/gradle:jdk7

进入工程目录

$ docker run -it --rm -v $PWD:/project -v $HOME/.gradle:/gradle/.gradle registry.aliyuncs.com/abeldeng/gradle:jdk7 build --info

Have Fun!
