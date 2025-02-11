## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:45:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:51:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:48:29 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:50:42 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:46:21 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:46:49 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 00:51:07 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 00:49:39 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:48:00 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:46:47 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:47:10 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:51:57 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:45:22 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:51:16 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:49:00 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:45:05 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:45:18 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:45:18 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 03:16:09 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 03:26:14 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 02:36:24 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 02:55:19 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 02:44:20 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 02:38:58 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 02:42:33 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 02:44:18 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 03:04:25 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 03:00:37 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 03:07:05 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 03:06:35 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 03:02:48 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 03:01:47 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 03:01:32 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 03:03:11 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 02:58:51 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 03:09:06 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 03:06:38 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 03:04:48 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 03:07:37 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 03:07:17 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 03:07:00 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 03:01:55 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 03:31:26 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 03:12:26 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 03:13:00 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 03:10:17 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 03:11:14 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 03:09:53 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 03:08:23 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 03:14:20 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 00:45:11 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 00:44:27 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 00:43:37 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 00:43:26 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 00:44:03 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 00:42:20 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 00:47:52 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 00:45:24 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 00:43:34 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 00:41:58 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 00:42:25 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 00:40:09 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 00:39:19 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 00:43:40 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 00:41:23 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 00:39:54 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 00:39:19 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 00:39:35 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 00:39:44 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 00:38:48 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 00:44:07 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 00:41:47 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 00:39:35 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 00:44:05 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 00:39:39 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 00:39:55 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 00:38:56 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 00:43:53 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 00:42:16 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 00:40:27 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 00:40:19 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 00:40:10 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 00:41:02 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 00:40:37 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 00:44:47 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 00:43:09 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 00:38:16 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 00:39:31 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 00:38:52 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 00:38:44 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 00:37:33 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 00:42:21 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 00:40:13 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 00:38:34 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 00:39:42 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 00:39:19 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 00:39:04 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 00:37:57 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 00:40:09 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 00:40:23 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 00:39:20 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 00:39:23 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 00:38:23 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 00:39:18 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 00:42:06 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 00:41:55 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 00:40:39 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 00:39:25 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 00:39:38 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 00:39:53 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 00:40:29 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 00:38:53 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 00:42:39 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 00:41:04 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 00:39:56 UTC 2025
