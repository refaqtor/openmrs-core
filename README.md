LibreHealth EMR is an extensible, patient-based electronic medical record system.
Read more about the project & find documentation at: http://librehealth.io

The project tree is set up as follows:

<table>
 <tr>
  <td>.settings</td>
  <td>Eclipse specific settings. Useful for character encoding and formatting (for devs using eclipse anyway)</td>
 </tr>
 <tr>
  <td>api/</td>
  <td>java and resource files for building the java api jar file.</td>
 </tr>
 <tr>
  <td>release-test</td>
  <td>Cucumber/selenium integration tests. Run daily against a running web app.
 </tr>
 <tr>
  <td>test</td>
  <td>TBD</td>
 </tr>
 <tr>
  <td>tools</td>
  <td>Meta code used during compiling and testing. Does not go into any released binary (like doclets)</td>
 </tr>
 <tr>
  <td>web/</td>
  <td>java and resource files that are used in the webapp/war file.</td>
 </tr>
 <tr>
  <td>webapp/</td>
  <td>jsp files used in building the war file.</td>
 </tr>
 <tr> 
  <td>build.properties</td>
  <td>(deprecated) default properties used by the deprecated ANT build.xml file</td>
 </tr>
 <tr>
  <td>build.xml</td>
  <td>(deprecated) ANT build file containing convenience methods into the maven build</td>
 </tr>
 <tr>
  <td>liquibase.build.xml</td>
  <td>ANT build file containing convenience methods to run liquibase actions</td>
 </tr>
 <tr>
  <td>openmrs-checkstyle.properties</td>
  <td>properties for the checkstyle library</td>
 </tr>
 <tr>
  <td>pom.xml</td>
  <td>The main maven file used to build and package OpenMRS</td>
 </tr>  
</table>
