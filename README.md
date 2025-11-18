# Maven-Archetype
java开发脚手架

## 使用教程
1，下载项目至本地
```
git clone https://github.com/wenzhuo4657/Maven-Archetype.git
```
2.进入maven项目根目录执行命令安装至本地
```
  mvn clean install -DskipTests
```
3, 本地使用

3.1.命令模式使用
```
mvn archetype:generate                                  \
  -DarchetypeGroupId=<archetype-groupId>                \
  -DarchetypeArtifactId=<archetype-artifactId>          \
  -DarchetypeVersion=<archetype-version>                \
  -DgroupId=<my.groupid>                                \
  -DartifactId=<my-artifactId>
```
3.2 idea使用
1），新建项目，找到脚手架页面

![](https://cdn.wenzhuo4657.org/img/2025/11/8f0e272db3c5e808ea058748c25027e5.png)

2）添加本地maven目录
![](https://cdn.wenzhuo4657.org/img/2025/11/b002e43a3610aa55f06ff86c367c45d6.png)
