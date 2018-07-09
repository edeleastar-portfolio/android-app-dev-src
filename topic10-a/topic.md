#10-a: Services

A service is an application component that can perform a background task. A receiver is a component that allows registration for system or application events. We use both as a means of automatically refreshing cache data from the service. A BroadcastReceiver listens for a particular intent, sent either in response to booting the device or when our application starts. It then sets an alarm that triggers the refresh service at either default or user-define intervals. We also demonstrate how to manually refresh data by making a direct call to service.
