#背景知识提要：
##1.  EVENT的基本知识
```
typedef struct {
        bool bAutoReset;
        bool bIsSet;
    } event_t;
```
##2.Event的基本操作


1.   Set： ```SET_EVENT (__EVENT)```


2.  Wait: ```WAIT_EVENT (__EVENT)```, 返回值是bool，true表示检测到event被set了


3.  Reset: ```  RESET_EVENT (__EVENT)```;


4.  Init: ```   INIT_EVENT(__EVENT,__INIT_VALUE,__MANUAL)```

