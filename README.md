# fish-plugins

Plugins used on PanRyba.pl Minecraft server

## How to build

````
git clone https://github.com/PanRybaPl/fish-plugins.git --recursive
cd fish-plugins
mvn install:install-file -Dfile=BarAPI.jar -DgroupId=me.confuser -DartifactId=BarAPI -Dversion=3.0 -Dpackaging=jar
mvn package
````

Built plugins (jar files) can be found in relevant "target" folder in each plugin directory.
