Pre-reqisists softwares to be installed.
a. install Java 1.8 and verify whether the Java is available in the system by checking java commands in the command prompt. cmd: java --version/-version.
b. maven and likewise check maven is installed, use the following command. cmd: mvn -version
c.[optional] to access the code and view the source code, instal any IDE (Sts4 or IntelliJ Idea).


Please follow below steps to run the application.
----------------------------------------------------
Step1: unzip the project and store it in your local directory.
Step2: go inside **/atm-service/ directory using CD. execute the maven command.
Step3: mvn clean install and this command will get run, check for the dependencies and pulls it in the system.
Step4: after the successful build, we will get the jar file. and it will be available inside /target diresctory.
Step5: use CD to **/atm-service/target and run the java command to kick start the application to run on the system .CMD-> java -jar jar-name.jar 
Step5: Application should be up and runnning on the port number 8080. 

Step6: launch any testing tools like postman/any tool where we can test our apis.

note: To see the api urls visit swagger link: http://localhost:8080/swagger-ui.html#/ and this should bring up you the site with the listed.