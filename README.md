JReloader 是一个用来重新加载class文件而无需重启JVM的工具。

使用方法：

?
1
2
3
java -noverify -javaagent:c:\jreloader-0.2\jreloader.jar -Djreloader.dirs=c:\project\target\classes com.foo.Main
 
java -noverify -javaagent:c:\jreloader-0.2\jreloader.jar -Djreloader.dirs=c:\project\target\classes -jar foo.jar
