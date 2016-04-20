# Frequently Asked Questions #

**Can I run JBoss, Tomcat, etc. with JReloader?**

Yes you can. Personally, I've been using it with Tomcat6, JBoss4, JBoss5, from small applications to fairly big ones with multiple EARs/WARs and hundreds of EJBs per module, including tens of class directories. The performance impact is negligible.

**Do I need to configure something in my IDE?**

If you start the JVM from within the IDE then you need to add the required JVM parameters in your launch configuration. Also, you need to enable the "compile on save" feature. That's usually all you need.

**How long does it take to see the changes once I save the .java file in Eclipse?**

Usually 1-2 seconds.