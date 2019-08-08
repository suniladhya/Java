# Installation
* System Information > System Type
* Download Path: [Tomcat Link](https://tomcat.apache.org/download-80.cgi) (Download Tomcat as per the system type)
* Installation Type: Full
* Provide the path of the JRE intalled in the system.
## Tomcat service Settings
* Te service can be configured using
  * Services.msc or
  * C:\Program Files\Apache Software Foundation\Tomcat 8.5\bin\Tomcat8w.exe
  * It is good practice to set startup type as manual.
## App hosting in Tomcat
* Edit properties of installation folder (C:\Program Files\Apache Software Foundation\Tomcat 8.5)
* in security tab, Edit permission of USERS to allow to provide 'FULL CONTROL'.
* Now apps can be created in the Tomcat 8.5\WebApps folder
