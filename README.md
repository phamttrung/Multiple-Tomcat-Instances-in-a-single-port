# Multiple-Tomcat-Instances-in-a-single-port
How to set multiple Tomcat instances on a single port on Windows (a work in progress)

##Reason for running multiple instance of Tomcat Server

From [vmware|blog](http://blogs.vmware.com/vfabric/2012/10/5-scenarios-and-best-practices-for-running-multiple-instances-of-tomcat-or-tc-server.html)
>*With multiple Tomcat instances, each runs in its own JVM, with its own configuration, and can be started or stopped independently, while still running against the same core binary. There are a variety of reasons to do this in practice. For example:*
>  * *Simplify updates by separating instance specific data like web applications from the core Tomcat software.*
>  * *Maintain central control (and restricted permissions) on core Tomcat software, while allowing Tomcat instances to run as individual users without root permissions.*
>  * *Isolate web applications to a particular Tomcat instance for protection from faults in other applications.*
>  * *Permit application-specific performance monitoring (and usage billing) by having each application in its own Tomcat instance.*
>  * *Configure the Java Virtual Machine specifically for the needs of the application(s) running on that Tomcat instance.*
  
##How to set multiple Tomcat instances on a single port on Windows

Brief step by step guide to install and configure
