
1. ## Java环境

jdk

1. 环境变量
   JAVA_HOME—D:\Java\jdk1.8.0_111

   GRADLE_HOME—D:\gradle-4.4.1

   GRADLE_USER_HOME—D:\GradleCaches(*设置一个目录，作为gradle的下载缓存目录*)

   CLASSPATH—;.D:\Java\jdk1.8.0_111\bin;D:\Java\jdk1.8.0_111\lib\tools.jar

   M2_HOME—D:\apache-maven-3.3.9(*设置为maven的安装目录*)

   M2—D:\apache-maven-3.3.9\bin

   spring.profiles.active=development 

2. Path
   D:\Java\jdk1.8.0_111\bin 

   D:\Java\jdk1.8.0_111\jre\bin 

   D:\gradle-4.4.1\bin

   D:\apache-maven-3.3.9\bin

   测试命令：java -version、javac、gradle -v、mvn -version

3. 设置

   1. 可以在F:\maven\conf\settings.xml文件中的localRepository节点定义一个仓库缓存目录，如<localRepository>F:\maven-repository</localRepository> 

   2. idea设置版权信息以及文件描述
      setting-file and code template

      ```
      #parse("File Header.java")
      #if (${PACKAGE_NAME} && ${PACKAGE_NAME} != "")package ${PACKAGE_NAME};#end
      /**
       * Description:
       * 
       * 
       * @author ${USER}
       * @date ${DATE} ${TIME}
       */
      public class/interface/enum/@interface ${NAME} {
      }
      ```

      file header

      ```
      /**
       * Copyright(c) Runsdata Technology Co.,Ltd.
       * All Rights Reserved.
       * <p>
       * This software is the confidential and proprietary information of Runsdata
       * Technology Co.,Ltd. ("Confidential Information"). You shall not disclose
       * such Confidential Information and shall use it only in accordance with the
       * terms of the license agreement you entered into with Runsdata Technology Co.,Ltd.
       * For more information about Runsdata, welcome to http://www.runsdata.com
       * <p>
       * project: ${PROJECT_NAME}
       * <p>
       * Revision History:
       * Date          Version       Name            Description
       * ${DATE} 1.0          ${USER}          Creation File
       */
      ```

