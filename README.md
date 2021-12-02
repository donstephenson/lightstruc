# lightstruc
LightStruc was created to provide for the rapid prototyping and deployment of single page web applications. It provides components that reside on both the browser and server that create a unified namespace across the stack. From the browser’s perspective this namespace extends across the network and is symmetrically bound to the server side processes to minimize impedance mismatch within the application.
The lighstruc framework is implemented in two components, browser and server. The browser component consists of:
  •	LightStruc panel that provides a namespace isolated container for HTML components plus bindings to backend data.
  •	Object broker which binds the browser function proxies to the service routine on the server. 
The server component consists of:
  •	Model
  
The LightStruc object  broker is made up of two components that act together to create a seamless execution environment with the client code.  A lightStruc client component instantiates client proxies based on a server-side class definition.  The classes are instantiated on the server as singletons that service and execute methods on behalf of the client.
