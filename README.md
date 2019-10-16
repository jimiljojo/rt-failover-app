This app generates an OutOfMemory exception by eating up all the JVP heap space to demo the automatic failover between replicas when mule applications are deployed onto Anypoint Runtime Fabric. 

Mule Runtime version - 4.1.3

API Resources available

/kill - this crashes the app by generating the error

/sample - this returns a sample payload to check if the worker is still up and running 