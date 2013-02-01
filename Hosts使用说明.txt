把hosts覆盖到C:\windows\system32\drivers\etc

提示：没有权限 解决方法
1.找到Hosts文件（ipv6用户将文件名改成hosts即可），将Hosts文件复制到桌面。 （Windows7系统Hosts文件路径为：C:\WINDOWS\system32\drivers\etc\hosts）

2.用记事本打开，浏览器打开https://smartladder.googlecode.com/svn/trunk/hosts
Ctrl+A 全选Ctrl+C复制再回到记事本中Ctrl+V 粘贴

3.将修改好的Hosts文件再复制回Hosts文件目录，提示是否覆盖时选择覆盖即可。

通过这个方式可以解决提示无权修改Hosts文件，以后需要修改Hosts时就不再需要再复制到桌面了，因为文件属性已经修改，以后只需要在Hosts目录下修改即可

建议使用DNS 8.8.8.8/8.8.4.4
            114.114.114.114/114.114.115.115


ipv6hosts仅限ipv6用户使用 ipv4使用 后果自负。