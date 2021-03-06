!SLIDE subsection
#~~~SECTION:MAJOR~~~ Groovy Script & Jenkins CLI

!SLIDE bullets noprint
# Groovy Script
Topics in this chapter

* General Groovy Usage
* Possible applications
* Simple Groovy Script Example
* Security Concerns

!SLIDE smbullets printonly
# Groovy Script
Topics in this chapter

* General Groovy usage
* Possible applications
* Simple Groovy script example
* Security concerns

!SLIDE bullets noprint
# What Is Groovy
* Apache Groovy, actually
* Scripting language for Java
* Used to create Domain-Specific Langauges (DSL)
* Not excactly Java

!SLIDE bullets noprint
# General Groovy Usage
* /script for web console
* CLI can be used with curl
* 'Remoting' as an insecure legacy option
* `JENKINS_HOME/init.groovy.d/*.groovy` is run on startup

~~~SECTION:notes~~~
sadsad
~~~ENDSECTION~~~

!SLIDE smbullets printonly
# General Groovy Usage
The Jenkins script console is accessible in two locations:

* `/script` for web console
* CLI can be used with curl
* 'Remoting' as an insecure legacy option
* `JENKINS_HOME/init.groovy.d/*.groovy` is run on startup

!SLIDE bullets noprint
# Possible Applications
* Groovy is quite powerful.
* It can also be safely ignored.
* Can be used to make tedious tasks easy...
* ... Or automate Jenkins deployment completely

!SLIDE smbullets printonly
# Possible Applications
* Groovy is quite powerful.
* It can also be safely ignored.
* Can be used to make tedious tasks easy...
* ... Or automate Jenkins deployment completely

!SLIDE bullets noprint
# Manage Jenkins
* Can manage the complete configuration
* Setup agents, credentials, authorization
* Enable and configure Plugins

!SLIDE smbullets printonly
# Manage Jenkins
* Can manage the complete configuration
* Setup agents, credentials, authorization
* Enable and configure Plugins

!SLIDE bullets noprint
# Jenkins Job DSL
* job-dsl Plugin
* Basically Groovy with job objects
* Allows to move job config from xml to script

!SLIDE smbullets printonly
# Jenkins Job DSL
* job-dsl Plugins
* Basically Groovy with job objects
* Allows to move job config from xml to script
