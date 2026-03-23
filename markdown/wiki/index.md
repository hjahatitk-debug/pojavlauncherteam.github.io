java.net.UnknownHostException: Unable to resolve host "libraries.minecraft.net": No address associated with hostname
	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:124)
	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:103)
	at java.net.InetAddress.getAllByName(InetAddress.java:1152)
	at com.android.okhttp.Dns$1.lookup(Dns.java:41)
	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:178)
	at com.android.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:144)
	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:86)
	at com.android.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:176)
	at com.android.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:128)
	at com.android.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:97)
	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:289)
	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:232)
	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:465)
	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:411)
	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:248)
	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getInputStream(DelegatingHttpsURLConnection.java:211)
	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getInputStream(HttpsURLConnectionImpl.java:30)
	at net.kdt.pojavlaunch.utils.DownloadUtils.downloadFileMonitored(DownloadUtils.java:70)
	at net.kdt.pojavlaunch.mirrors.DownloadMirror.downloadFileMirrored(DownloadMirror.java:41)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask.lambda$downloadFile$0$net-kdt-pojavlaunch-tasks-MinecraftDownloader$DownloaderTask(MinecraftDownloader.java:469)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask$$ExternalSyntheticLambda0.call(D8$$SyntheticClass:0)
	at net.kdt.pojavlaunch.utils.DownloadUtils.downloadFile(DownloadUtils.java:125)
	at net.kdt.pojavlaunch.utils.DownloadUtils.ensureSha1(DownloadUtils.java:151)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask.downloadFile(MinecraftDownloader.java:468)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask.verifyFileSha1(MinecraftDownloader.java:462)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask.runCatching(MinecraftDownloader.java:447)
	at net.kdt.pojavlaunch.tasks.MinecraftDownloader$DownloaderTask.run(MinecraftDownloader.java:435)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1156)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:651)
	at java.lang.Thread.run(Thread.java:1119)



# Welcome to the PojavLauncher Wiki!
____
* Get started by [installing Pojavlauncher](./getting_started/INSTALL)!
* Got a question? Check out our [FAQ](./faq/INSTALLATIONOFMODSRPWORLDS)!
* Wanna contribute to the project? [Look here](../contribute/CONT-WEBSITE.md)

