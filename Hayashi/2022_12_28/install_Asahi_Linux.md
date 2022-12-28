# install asahi linux

## Step

Installed asahi on M1 Mac

[how to download](https://asahilinux.org/2022/03/asahi-linux-alpha-release/)

## Problem

At first the output keep like blow:

```
michaelyuyurose@Michaels-MacBook-Air ~ % curl https://alx.sh | sh
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  1511  100  1511    0     0   1340      0  0:00:01  0:00:01 --:--:--  1350

Bootstrapping installer:
  Checking version...
curl: (35) error:02FFF036:system library:func(4095):Connection reset by peer
michaelyuyurose@Michaels-MacBook-Air ~ % curl https://alx.sh | sh
```
but try to switch the proxy to America, the problem get solved.
