# FAQ

## 解析时出现视频无法下载的问题

当在解析时出现某个视频无法下载的情况时，如果原因是 「啥都木有」，那么你只需要重新启动程序一般就可以解决。

而原因是其他情况时，请针对该情况进行检查，如果该视频你确实没有获取权限，请利用选集参数跳过该视频，这样就可以下载其余视频了。

## 总是解析一段时间后就崩溃了

可能是网络不佳，你可以通过增加 `-p` 参数每次下载一话，多运行几次就好了。

## 出现 `requests.exceptions.ProxyError`

由于你开启了系统代理会导致一些问题，所以请使用[参数 `--disable-proxy`](../cli/#绕过系统代理) 绕过系统代理。

## 可以下载互动视频吗？

暂时不可以，也不在现阶段计划中，因为本地的体验必然不如直接在 B 站上看体验好，建议直接在 B 站看哦～

## 可以不生成 `- bilibili` 目录吗？

当前也是不可以的，不过 bilili2.x 提供了更加灵活的路径设置方式，如果有兴趣可以尝试 v2 ～
