Rosdep Setup
============
To be able to download yujin system binaries via rosdep, you need to create a file `/etc/ros/rosdep/source.list.d/15-yujin.list` containing : 
```
yaml https://raw.githubusercontent.com/yujinrobot/rosdistro/master/rosdep/yujinrobot-system.yaml
```

*DEPRECATED* If you also want to be able to retrieve the pacakges built by yujin buildbot you need to add this other line : 
```
yaml https://raw.githubusercontent.com/yujinrobot/rosdistro/master/rosdep/yujinrobot-build-indigo.yaml
```
