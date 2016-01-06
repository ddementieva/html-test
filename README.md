# html-test
| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Start Apache | `sudo service apache2 start` |
| 2      | Stop Apache      |   `sudo service apache2 stop` |
| 3 | Follow access and error logs      |    `sudo tail -f /var/log/apache2/access.log -f /var/log/apache2/error.log` |

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and copy war | `mvn -f ${current.project.path} clean install && cp ${current.project.path}/target/*.war $TOMCAT_HOME/webapps/ROOT.war` |
| 2      | Run Tomcat      |   `$TOMCAT_HOME/bin/catalina.sh run` |
| 3 | Stop Tomcat      |    `$TOMCAT_HOME/bin/catalina.sh stop` |
| 4 | Tomcat Debug Mode      |    `$TOMCAT_HOME/bin/catalina.sh jpda run` |

| :------------- |
| `cd ${current.project.path}` |
| `npm install && bower install` |
| `gulp serve` |
