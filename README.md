# upsoft-bootparent
spring boot parent dependencies 为了不让springboot项目继承默认的spring-boot-parent
  

`Useage:`
  

 1、 在POM中添加
 
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.upsoft</groupId>
                <artifactId>upsoft-bootparent</artifactId>
                <version>1.0-SNAPSHOT</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

   

