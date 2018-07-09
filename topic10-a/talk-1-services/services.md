Auto-refresh cache

We configure an alarm within BroadcastReceiver's onHandleIntent method that initiates a process terminating in a refresh of local cached data obtained 	from a cloud service. The process is run on a worker thread and avails of the Retrofit HTTP client to communicate across the network so as to keep the local cached data in sync with that of the service.