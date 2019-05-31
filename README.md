# intelij-config-repository

1. When using a new computer go to intelij

2. Go to File > Settings repository 

3. Add https://github.com/junhuhdev/intelij-config-repository.git as url

4. Press overwrite LOCAL which will add remote settings to ur local.

Optional when you have done changes to your local machine and want to sync to remote, do the opposite and press overwrite REMOTE

(Help > edit custom vm options)
# custom IntelliJ IDEA VM options

```text
-Xms1024m
-Xmx2048m
-XX:ReservedCodeCacheSize=240m
-XX:+UseConcMarkSweepGC
-XX:SoftRefLRUPolicyMSPerMB=50
-ea
-Dsun.io.useCanonCaches=false
-Djava.net.preferIPv4Stack=true
-Djdk.http.auth.tunneling.disabledSchemes=""
-XX:+HeapDumpOnOutOfMemoryError
-XX:-OmitStackTraceInFastThrow
```
