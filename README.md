# delog
Delete 10-years-old openBCM log files.

I'm running openBCM over 10 years.
Oneday, I saw the event of 10 years ago.
"logYMMDD.bcm" files have the new and old events!
I should delete old logs before the 10th anniversary.

Installation:

1. Copy delog, delog.imp into $BCMHOME
1. Edit log path in delog.
1. Add this entry into crontab.bcm.

```
50           23    31    12      *   delog
```

I recommend running this program at midnight on New Year's Eve.
