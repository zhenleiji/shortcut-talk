# Analyze stack trace

Look for the action: "Analyze stack trace"

Example of stack trace:

```
 E  FATAL EXCEPTION: main
    Process: com.zhji.shortcut, PID: 2588
    java.lang.RuntimeException: java.lang.reflect.InvocationTargetException
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:558)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:936)
    Caused by: java.lang.reflect.InvocationTargetException
        at java.lang.reflect.Method.invoke(Native Method)
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:548)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:936)
    Caused by: java.lang.IllegalAccessException: Simulate some bug
        at com.zhji.shortcut.ui.home.HomeFragment.onCreateView$lambda$1(HomeFragment.kt:41)
        at com.zhji.shortcut.ui.home.HomeFragment.$r8$lambda$XaDTicET3LNiZbh2My3rAWCZshM(Unknown Source:0)
        at com.zhji.shortcut.ui.home.HomeFragment$$ExternalSyntheticLambda1.onClick(Unknown Source:0)
        at android.view.View.performClick(View.java:7506)
        at com.google.android.material.button.MaterialButton.performClick(MaterialButton.java:1131)
        at android.view.View.performClickInternal(View.java:7483)
        at android.view.View.-$$Nest$mperformClickInternal(Unknown Source:0)
        at android.view.View$PerformClick.run(View.java:29334)
        at android.os.Handler.handleCallback(Handler.java:942)
        at android.os.Handler.dispatchMessage(Handler.java:99)
        at android.os.Looper.loopOnce(Looper.java:201)
        at android.os.Looper.loop(Looper.java:288)
        at android.app.ActivityThread.main(ActivityThread.java:7872)
        at java.lang.reflect.Method.invoke(Native Method)
        at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:548)
        at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:936)
```
