Logcat output:

```
2019-10-17 09:32:07.734 28747-28747/? I/ple.spotifyaut: Late-enabling -Xcheck:jni
2019-10-17 09:32:07.755 28747-28747/? E/ple.spotifyaut: Unknown bits set in runtime_flags: 0x8000
2019-10-17 09:32:07.778 28747-28747/? W/ActivityThread: Application com.example.spotifyauth is waiting for the debugger on port 8100...
2019-10-17 09:32:07.779 28747-28747/? I/System.out: Sending WAIT chunk
2019-10-17 09:32:09.780 28747-28747/com.example.spotifyauth I/System.out: Debugger has connected
2019-10-17 09:32:09.780 28747-28747/com.example.spotifyauth I/System.out: waiting for debugger to settle...
2019-10-17 09:32:09.981 28747-28747/com.example.spotifyauth I/System.out: waiting for debugger to settle...
2019-10-17 09:32:10.181 28747-28747/com.example.spotifyauth I/System.out: waiting for debugger to settle...
2019-10-17 09:32:10.381 28747-28747/com.example.spotifyauth I/System.out: waiting for debugger to settle...
2019-10-17 09:32:10.982 28747-28747/com.example.spotifyauth I/chatty: uid=10248(com.example.spotifyauth) identical 3 lines
2019-10-17 09:32:11.182 28747-28747/com.example.spotifyauth I/System.out: waiting for debugger to settle...
2019-10-17 09:32:11.383 28747-28747/com.example.spotifyauth I/System.out: debugger has settled (1483)
2019-10-17 09:32:11.525 28747-28747/com.example.spotifyauth W/ple.spotifyaut: JIT profile information will not be recorded: profile file does not exits.
2019-10-17 09:32:11.539 28747-28747/com.example.spotifyauth I/chatty: uid=10248(com.example.spotifyauth) identical 10 lines
2019-10-17 09:32:11.540 28747-28747/com.example.spotifyauth W/ple.spotifyaut: JIT profile information will not be recorded: profile file does not exits.
2019-10-17 09:32:11.564 28747-28747/com.example.spotifyauth I/InstantRun: starting instant run server: is main process
2019-10-17 09:32:11.785 28747-28747/com.example.spotifyauth W/ple.spotifyaut: Accessing hidden method Landroid/view/View;->computeFitSystemWindows(Landroid/graphics/Rect;Landroid/graphics/Rect;)Z (greylist, reflection, allowed)
2019-10-17 09:32:11.786 28747-28747/com.example.spotifyauth W/ple.spotifyaut: Accessing hidden method Landroid/view/ViewGroup;->makeOptionalFitsSystemWindows()V (greylist, reflection, allowed)
2019-10-17 09:32:12.037 28747-28791/com.example.spotifyauth I/Adreno: QUALCOMM build                   : bc00834, I609ab310b2
    Build Date                       : 04/11/19
    OpenGL ES Shader Compiler Version: EV031.26.07.00
    Local Branch                     : 
    Remote Branch                    : 
    Remote Branch                    : 
    Reconstruct Branch               : 
2019-10-17 09:32:12.037 28747-28791/com.example.spotifyauth I/Adreno: Build Config                     : S L 8.0.6 AArch64
2019-10-17 09:32:12.042 28747-28791/com.example.spotifyauth I/Adreno: PFP: 0x005ff110, ME: 0x005ff066
2019-10-17 09:32:12.068 28747-28791/com.example.spotifyauth W/Gralloc3: mapper 3.x is not supported
2019-10-17 09:32:12.150 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/HelloDetails; annotation class 20
2019-10-17 09:32:12.154 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/HelloDetails; annotation class 23
2019-10-17 09:32:12.181 28747-28795/com.example.spotifyauth I/chatty: uid=10248(com.example.spotifyauth) AsyncTask #1 identical 6 lines
2019-10-17 09:32:12.183 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/HelloDetails; annotation class 23
2019-10-17 09:32:12.186 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Info; annotation class 20
2019-10-17 09:32:12.189 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Info; annotation class 23
2019-10-17 09:32:12.238 28747-28795/com.example.spotifyauth I/chatty: uid=10248(com.example.spotifyauth) AsyncTask #1 identical 22 lines
2019-10-17 09:32:12.241 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Info; annotation class 23
2019-10-17 09:32:12.243 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/HelloDetails; annotation class 23
2019-10-17 09:32:12.244 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/HelloDetails; annotation class 23
2019-10-17 09:32:12.247 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Roles; annotation class 20
2019-10-17 09:32:12.248 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Roles; annotation class 23
2019-10-17 09:32:12.260 28747-28795/com.example.spotifyauth I/chatty: uid=10248(com.example.spotifyauth) AsyncTask #1 identical 6 lines
2019-10-17 09:32:12.261 28747-28795/com.example.spotifyauth W/ple.spotifyaut: Unable to resolve Lcom/spotify/protocol/types/Roles; annotation class 23
2019-10-17 09:32:12.690 28747-28747/com.example.spotifyauth E/MainActivity: {"message":"Could not authenticate within 60 s."}
    com.spotify.android.appremote.api.error.AuthenticationFailedException: {"message":"Could not authenticate within 60 s."}
        at com.spotify.android.appremote.api.LocalConnector.asAppRemoteException(LocalConnector.java:131)
        at com.spotify.android.appremote.api.LocalConnector.access$001(LocalConnector.java:35)
        at com.spotify.android.appremote.api.LocalConnector$2.onConnectionFailed(LocalConnector.java:111)
        at com.spotify.android.appremote.internal.SdkRemoteClientConnector$ConnectionTask.onPostExecute(SdkRemoteClientConnector.java:144)
        at com.spotify.android.appremote.internal.SdkRemoteClientConnector$ConnectionTask.onPostExecute(SdkRemoteClientConnector.java:76)
        at android.os.AsyncTask.finish(AsyncTask.java:756)
        at android.os.AsyncTask.access$901(AsyncTask.java:192)
        at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:773)
        at android.os.Handler.dispatchMessage(Handler.java:108)
        at android.os.Looper.loop(Looper.java:215)
        at android.app.ActivityThread.main(ActivityThread.java:7357)
        at java.lang.reflect.Method.invoke(Native Method)
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:493)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:931)
     Caused by: com.spotify.protocol.client.error.RemoteClientException: {"message":"Could not authenticate within 61 s."}
        at com.spotify.protocol.client.RemoteWampClient.getRemoteClientException(RemoteWampClient.java:140)
        at com.spotify.protocol.client.RemoteWampClient.access$201(RemoteWampClient.java:16)
        at com.spotify.protocol.client.RemoteWampClient$2.onAbort(RemoteWampClient.java:44)
        at com.spotify.protocol.client.WampRouterImpl.routeAbort(WampRouterImpl.java:101)
        at com.spotify.protocol.client.WampRouterImpl.route(WampRouterImpl.java:27)
        at com.spotify.protocol.client.AppProtocolCommunicator.onData(AppProtocolCommunicator.java:79)
        at com.spotify.android.appremote.internal.RemoteServiceIo.handleMessage(RemoteServiceIo.java:114)
        at com.spotify.android.appremote.internal.RemoteServiceIo.access$001(RemoteServiceIo.java:47)
        at com.spotify.android.appremote.internal.RemoteServiceIo$IncomingHandler.handleMessage(RemoteServiceIo.java:92)
        at android.os.Handler.dispatchMessage(Handler.java:108) 
        at android.os.Looper.loop(Looper.java:215) 
        at android.app.ActivityThread.main(ActivityThread.java:7357) 
        at java.lang.reflect.Method.invoke(Native Method) 
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:493) 
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:931) 
```


Signing report:
```
9:30:27 AM: Executing task 'signingReport'...

Executing tasks: [signingReport]


> Task :app:signingReport
Variant: debugAndroidTest
Config: debug
Store: /home/arch/.android/debug.keystore
Alias: AndroidDebugKey
MD5: AA:33:D3:A7:1D:BF:A9:FB:07:32:32:2D:38:09:FA:3C
SHA1: 81:7B:6E:52:FF:2C:57:45:7F:8E:28:A3:4D:A8:00:71:6D:48:88:74
SHA-256: AE:98:9E:8E:8C:E2:07:7C:B8:CE:C9:97:FF:9F:DE:21:26:C6:2D:66:DD:A4:70:DA:9F:1A:0A:84:C6:A0:65:89
Valid until: Saturday, July 17, 2049
----------
Variant: debugUnitTest
Config: debug
Store: /home/arch/.android/debug.keystore
Alias: AndroidDebugKey
MD5: AA:33:D3:A7:1D:BF:A9:FB:07:32:32:2D:38:09:FA:3C
SHA1: 81:7B:6E:52:FF:2C:57:45:7F:8E:28:A3:4D:A8:00:71:6D:48:88:74
SHA-256: AE:98:9E:8E:8C:E2:07:7C:B8:CE:C9:97:FF:9F:DE:21:26:C6:2D:66:DD:A4:70:DA:9F:1A:0A:84:C6:A0:65:89
Valid until: Saturday, July 17, 2049
----------
Variant: release
Config: none
----------
Variant: debug
Config: debug
Store: /home/arch/.android/debug.keystore
Alias: AndroidDebugKey
MD5: AA:33:D3:A7:1D:BF:A9:FB:07:32:32:2D:38:09:FA:3C
SHA1: 81:7B:6E:52:FF:2C:57:45:7F:8E:28:A3:4D:A8:00:71:6D:48:88:74
SHA-256: AE:98:9E:8E:8C:E2:07:7C:B8:CE:C9:97:FF:9F:DE:21:26:C6:2D:66:DD:A4:70:DA:9F:1A:0A:84:C6:A0:65:89
Valid until: Saturday, July 17, 2049
----------
Variant: releaseUnitTest
Config: none
----------

BUILD SUCCESSFUL in 0s
1 actionable task: 1 executed
9:30:28 AM: Task execution finished 'signingReport'.
```
