# JavaException
放置一些碰到的JAVA錯誤訊息




Error occurred during initialization of VM
Could not reserve enough space for 1048576KB object heap

Arguments > VM arguments: 
-Xmx1024m

測試最大內存:
java -Xmx${Size}M -version

C:\Users\6286>java  -Xmx1024M -version
java version "1.6.0_14"
Java(TM) SE Runtime Environment (build 1.6.0_14-b08)
Java HotSpot(TM) Client VM (build 14.0-b16, mixed mode)

C:\Users\6286>java  -Xmx102411M -version
Invalid maximum heap size: -Xmx102411M
The specified size exceeds the maximum representable size.
Could not create the Java virtual machine.




Exception in thread "main" java.lang.OutOfMemoryError: GC overhead limit exceeded


[2019-11-12 11:56:38][ERROR][][]  - java.sql.SQLRecoverableException: IO 錯誤: The Network Adapter could not establish the connection
java.sql.SQLRecoverableException: IO 錯誤: The Network Adapter could not establish the connection
