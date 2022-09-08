# JDMonitor

# 请勿传播
# 否则随时闭库

# 拉库命令

ql repo https://github.com/tttccz/TczMonitor.git "jd_|t_" "backup" "JS_|notify|pk_|magic|USER_AGENTS|jdCookie|sendNotify" "main"

使用教程

1、需要自备sign接口，具体搭建方法参考 https://github.com/chiupam/Docker/tree/main/official

2、该库支持Redis存放Token操作，可在青龙面板中安装Redis，并设置变量export USE_REDIS=true

tttccz_JDMonitor/t_wx_getToken.js 该文件检测并生成临时Token 20多分钟后过期

3、该库支持REDIS_URL配置，默认为青龙内部安装路径，如需配置请设置变量export REDIS_URL="你的REDIS地址"，格式 ip:port


	
# 青龙面板脚本依赖

png-js
date-fns
axios
dotenv
got
crypto-js
md5
ts-md5
tslib
@types/node
request
tough-cookie
jsdom
download
tunnel
ws
js-base64
qrcode-terminal
moment
redis
