请不要fork！！！fork太多会导致项目直接挂掉,如需使用，请在右上角选择新建项目，导入代码
## 使用注意 :warning:

- :warning: 请不要fork，因为GitHub Actions也会fork过去。那样会给番组计划的服务器造成压力；又或者请求过多，有可能触发拒绝请求的保护机制，造成项目被后台删除。
- :warning: lxk大佬的代码已私人化，请自寻路径了，以前的代码不更新还能用  

  依次按下顺序运行代码  

  使用termux高级教程配置好，百度第一个就是  

  pkg update  

  pkg install git perl nodejs-lts wget curl nano cronie moreutils  

  git clone https://gitee.com/wudongdefeng/jd-base.git ~/storage/shared/jd  

  cd  ~/storage/shared/jd  

  cp sample/auth.json config/auth.json  

  cp sample/termux.list.sample config/crontab.list  

  cp ~/storage/shared/jd/sample/config.sh.sample config/config.sh  

  bash git_pull.sh  

  至此代码已OK！  

  控制面板开启方法  

  cd panel\n
  npm install || npm install --registry=https://registry.npm.taobao.org.com  

  node server.js  

 出现端口5678提示，进手机网页127.0.0.1:5678就好了  

 出现错误无非是npm的问题，自己在网页搜索相关的教程，一般重新安装nodejs-lts就能解决  

