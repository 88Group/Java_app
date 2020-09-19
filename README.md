# Java программа с интерфейсом / Погодное приложение

https://itproger.com/news/272

https://www.youtube.com/watch?v=5mBKzVs5MY0


```
"E:\Program Files\Java\jdk-11.0.8\bin\java.exe" --module-path C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib --add-modules javafx.controls,javafx.fxml --add-modules javafx.base,javafx.graphics --add-reads javafx.base=ALL-UNNAMED --add-reads javafx.graphics=ALL-UNNAMED "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2020.2.2\lib\idea_rt.jar=62500:C:\Program Files\JetBrains\IntelliJ IDEA 2020.2.2\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\halim\IdeaProjects\App\Java_app\out\production\App;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\src.zip;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx-swt.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.web.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.base.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.fxml.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.media.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.swing.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.controls.jar;C:\Users\halim\Desktop\javafx-sdk-11.0.2\lib\javafx.graphics.jar;C:\Users\halim\Desktop\json-20200518.jar sample.Main
Exception in Application start method
java.lang.reflect.InvocationTargetException
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplicationWithArgs(LauncherImpl.java:464)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication(LauncherImpl.java:363)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
	at java.base/sun.launcher.LauncherHelper$FXHelper.main(LauncherHelper.java:1051)
Caused by: java.lang.RuntimeException: Exception in Application start method
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:900)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: javafx.fxml.LoadException:
/C:/Users/halim/IdeaProjects/App/Java_app/out/production/App/sample/sample.fxml

	at javafx.fxml/javafx.fxml.FXMLLoader.constructLoadException(FXMLLoader.java:2625)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:2595)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:2466)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:3237)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:3194)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:3163)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:3136)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:3113)
	at javafx.fxml/javafx.fxml.FXMLLoader.load(FXMLLoader.java:3106)
	at sample.Main.start(Main.java:13)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$9(LauncherImpl.java:846)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at javafx.graphics/com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at javafx.graphics/com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at javafx.graphics/com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	... 1 more
Caused by: java.lang.reflect.InvocationTargetException
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
	at com.sun.javafx.reflect.Trampoline.invoke(MethodUtil.java:76)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
	at javafx.base/com.sun.javafx.reflect.MethodUtil.invoke(MethodUtil.java:273)
	at javafx.fxml/com.sun.javafx.fxml.MethodHelper.invoke(MethodHelper.java:83)
	at javafx.fxml/javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:2591)
	... 17 more
Caused by: java.lang.NullPointerException
	at sample.Controller.initialize(Controller.java:51)
	... 29 more
Exception running application sample.Main

Process finished with exit code 1
```