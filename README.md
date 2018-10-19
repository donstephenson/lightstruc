# lightstruc
The LightStruc framework was created to provide for the rapid prototyping and deployment of single page (post-back free) browser-hosted web applications.  The framework in conjunction with the lsPanel library component forms a seamless namespace isolated environment for  individual HTML markup segments. The framework is implemented in three logical units.
  •	The LightStruc object broker
  •	The LightStruc  library
  •	The CloudStruc object service
  
LightStruc object request broker
The LightStruc object  broker is made up of two components that act together to create a seamless execution environment with the client code.  A client JavaScript module instantiates JavaScript function objects in the form of client proxies based on a server side class definition.  The classes are instantiated on the server at call-time by the CloudStruc object service and execute methods on behalf of the client.
