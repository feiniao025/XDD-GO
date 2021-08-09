## 利用github action编译 [@cdle](https://github.com/cdle/jd_study.git) 大佬的JDC
- clone本库到JD目录
- 选择与 `系统匹配` 的XDD
- 配置好 `conf` 文件
- !若在容器内配置运行，请先映射端口
```text
chmod 777 XDD
```
```text
nohup ./XDD &
```
- 你可能会用到的命令  
   `cd /jd/XDD && nohup ./XDD > XDD.log 2>&1 &`                              后台运行JDC并生成日志  
   `ps -ef | grep ./XDD | grep -v grep | awk '{print $1}' | xargs kill -9`   查找并杀死JDC程序
## References:
- [@cdle](https://github.com/cdle/jd_study.git)
