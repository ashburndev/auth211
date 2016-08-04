# auth211
a simple Grails pluging created using Grails 2.1.1

## creating the grails 2.1.1 plugin

    ashburndave@dphnuc:~/g2projects$ grails --version
    
    Grails version: 2.1.1
    ashburndave@dphnuc:~/g2projects$ javac -version
    javac 1.7.0_80
    ashburndave@dphnuc:~/g2projects$ java -version
    java version "1.7.0_80"
    Java(TM) SE Runtime Environment (build 1.7.0_80-b15)
    Java HotSpot(TM) 64-Bit Server VM (build 24.80-b11, mixed mode)
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ grails --non-interactive --plain-output --stacktrace -verbose create-plugin auth211
    
    Base Directory: /home/ashburndave/g2projects
    |Loading Grails 2.1.1
    |Configuring classpath
    .
    |Environment set to development
    ......    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/src
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/src/java
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/src/groovy
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/controllers
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/services
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/domain
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/taglib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/utils
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/views
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/views/layouts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/i18n
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/conf
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/test
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/test/unit
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/test/integration
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/scripts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/web-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/web-app/js
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/web-app/css
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/web-app/images
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/web-app/META-INF
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/lib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/conf/spring
    .    [mkdir] Created dir: /home/ashburndave/g2projects/auth211/grails-app/conf/hibernate
    ..     [copy] Copying 1 resource to /home/ashburndave/g2projects/auth211
    .    [unjar] Expanding: /home/ashburndave/g2projects/auth211/grails-shared-files.jar into /home/ashburndave/g2projects/auth211
    .   [delete] Deleting: /home/ashburndave/g2projects/auth211/grails-shared-files.jar
    .     [copy] Copying 1 resource to /home/ashburndave/g2projects/auth211
    .    [unjar] Expanding: /home/ashburndave/g2projects/auth211/grails-plugin-files.jar into /home/ashburndave/g2projects/auth211
    .   [delete] Deleting: /home/ashburndave/g2projects/auth211/grails-plugin-files.jar
    .     [copy] Copying 3 files to /home/ashburndave/g2projects/auth211
    ..
    |Created Eclipse project files.
         [move] Moving 1 file to /home/ashburndave/g2projects/auth211
    ..
    |Created plugin Auth211
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ tree auth211
    auth211
    ├── application.properties
    ├── Auth211GrailsPlugin.groovy
    ├── grails-app
    │   ├── conf
    │   │   ├── BuildConfig.groovy
    │   │   ├── Config.groovy
    │   │   ├── DataSource.groovy
    │   │   ├── hibernate
    │   │   ├── spring
    │   │   └── UrlMappings.groovy
    │   ├── controllers
    │   ├── domain
    │   ├── i18n
    │   ├── services
    │   ├── taglib
    │   ├── utils
    │   └── views
    │       ├── error.gsp
    │       └── layouts
    ├── lib
    ├── scripts
    │   ├── _Install.groovy
    │   ├── _Uninstall.groovy
    │   └── _Upgrade.groovy
    ├── src
    │   ├── groovy
    │   └── java
    ├── test
    │   ├── integration
    │   └── unit
    └── web-app
        ├── css
        ├── images
        ├── js
        ├── META-INF
        └── WEB-INF
            ├── applicationContext.xml
            ├── sitemesh.xml
            └── tld
                ├── grails.tld
                └── spring.tld
    
    27 directories, 14 files
    ashburndave@dphnuc:~/g2projects$ 
    

