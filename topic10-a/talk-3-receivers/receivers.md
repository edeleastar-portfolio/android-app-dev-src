BroadcastReceiver

We subclass BroadcastReceiver and within its onReceive method we retrieve the user-input refresh interval and set an alarm to fire at this frequency. Each firing results in downloading the latest service data set and refreshing the local cache. The presentation examines the onReceive method in fine detail.
