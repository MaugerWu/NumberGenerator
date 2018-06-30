# NumberGenerator

1. 在终端（LINUX/UNIX或Mac）或命令提示符（Windows）中，浏览到要创建 Java 项目的文件夹。键入以下命令：

   `mvn archetype:generate -DgroupId=com.cqupt -DartifactId=NumberGenerator -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`

2. Maven 目录布局
使用`mvn archetype:generate` + `maven-archetype-quickstart`模板, 以下项目的目录结构被创建: 

   [参考：Maven 标准目录布局](http://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html)

   ```xml
   NumberGenerator
      |-src
      |---main
      |-----java
      |-------com
      |---------cqupt   
      |-----------App.java
      |---test
      |-----java
      |-------com
      |---------cqupt
      |-----------AppTest.java
      |-target
      |-pom.xml
   ```
   所有的源代码放在文件夹 /src/main/java/, 所有的单元测试代码放入 /src/test/java/.
