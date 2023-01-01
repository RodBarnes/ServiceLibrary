# ServiceLibrary
Collection of classes and methods to support service and process management

## ProcessManagement ##
### RunCommand ###
Run a system command or executable.  Accepts the FQPN of the command and an optional working directory.  Captures all output from the command (both Standard and Error) and returns it as a formatted string.

### StartService ###
Start an existing service.  Accepts the name of the service and a timeout (mSec) of how long to wait for the start to complete before throwing an exception.

### StopService ###
public static void StopService(string serviceName, int timeoutMilliseconds)
Stop a running service.  Accepts the name of the service and a timeout (mSec) of how long to wait for the stop to complete before throwing an exception.
