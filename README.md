# 青龙面板福利吧自动签到
青龙拉取地址：
ql repo https://github.com/bdzcan77/fubasing.git

添加两个环境变量：FUBA 登录后的cookie（复制cookie:后的全部内容）；FUBAUN 用户名；

之后创建定时任务即可
任务定时：
0 0 2,6 * * *
上面的意思是每天2点和6点各运行一次签到（防止漏签），也可以自行修改
0 0 3 * * *   
这个是每天3点触发
