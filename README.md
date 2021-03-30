# jenkins_home_1

#### 1.Download tomcat
```
wget http://apache-mirror.rbc.ru/pub/apache/tomcat/tomcat-9/v9.0.44/bin/apache-tomcat-9.0.44.zip
unzip apache-tomcat-9.0.44.zip
mv apache-tomcat-9.0.44 tomcat_dev9
cd tomcat_dev9/conf/
vi server.xml
vi tomcat-users.xml
cd ../bin/
chmod +x *
./startup.
```

#### 2. Clone git project
```
git clone https://github.com/kliakos/sparkjava-war-example.git
mkdir jenkins_home_1/src
cp sparkjava-war-example/src/* jenkins_home_1/src/
cp -r sparkjava-war-example/src/* jenkins_home_1/src/
cp sparkjava-war-example/pom.xml jenkins_home_1/
git status
git add *
git commit -m "Lesson13"
git push
```
