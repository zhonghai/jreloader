# Getting JReloader up and running in 2 minutes #

## Step 1 ##

Download and explode the zip file somewhere in your filesystem.

## Step 2 ##

You need only to add a couple of vm arguments, as in the example below:

```
java -noverify -javaagent:c:\jreloader-0.2\jreloader.jar -Djreloader.dirs=c:\project\target\classes com.foo.Main
```

or, if you have a jar file:

```
java -noverify -javaagent:c:\jreloader-0.2\jreloader.jar -Djreloader.dirs=c:\project\target\classes -jar foo.jar
```

If you have multiple modules, you can add more than one class dir:

```
-Djreloader.dirs=c:\project\target\classes,c:\project2\target\classes,c:\project2\target\classes
```