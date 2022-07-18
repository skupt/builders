# builders
JGMP 2022 Task 09
-----------------
How To Build And Install Project Using Maven
--------------------------------
In system command prompt use maven command inside the root directory of project 'builders' `mvn clean install`.
There will be generated following packages:
+ \builders\web\target\web-1.0.war
+ \builders\admin\target\admin-1.0.jar

'builders' will be installed in local Maven Repository.

How To Run Tests
----------------
use maven command inside root directory `mvn test`

How To Build And Install Project Using Gradle
---------------------------------
In system command prompt use gradle command inside the root directory of project 'builders' `gradle clean build`.
There will be generated following packages:
+ \builders\web\build\libs\web-1.0.war
+ \builders\admin\build\libs\admin-1.0.jar 

To publish project use command `gradle publish` or `gradle publishToMavenLocal`. Project destination respectively: 
+ \builders\build\m2repo\
+ you local '.m2' directory

How To Run Tests
----------------
use maven command inside root directory `gradle test`
