# WebLottery
在线网页抽奖，可以实现分批次抽取，或一次性抽取
# 环境
pycharm（其他python环境也可以）
# 依赖
python tornado（用pip安装即可）
# 程序说明
浏览器输入服务器ip，加冒号，再加端口号8000（用户也可以自己更改）
# 功能介绍
用户可以使用该程序为某活动设置一、二、三等奖名额，以及参与人员名单
参与人员奖项不能兼得，每人只有一次中奖机会，每次可以抽取同等奖项若干位中奖者
# 技术要求：
客户端采用H5网页，服务端采用tornado，所有数据直接记录在内存中，一次抽取若干名，要求采用Numpy随机函数一次生成
# 作者
gaozhiguang
# 联系方式
zhiguanggao@163.com
