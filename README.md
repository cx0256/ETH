 **如何（使用币安矿池）挖以太坊ETH** 

    - 币安矿池ETH挖矿教程
    - 显卡选择
    - 矿池选择
    - 下载挖矿软件
    - 如何ETH转换成USDT
    - FAQ

 **币安矿池ETH挖矿教程** 
本教程适用用手头有空闲的显卡挖矿，不建议炒币以及看到此教程买设备挖矿，请理性看待。

 **显卡选择** 
首先你需要一张显存在4g以上的显卡，如果你的显存在4g以下，下面的内容就可以不用看了。
是我用2070s挖的，2070s在小小超频的情况下算力能在40左右。
2070s算力和收益
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/234336_3ede17dd_8758987.png "屏幕截图.png")

 **矿池选择** 
矿池就是大家一起合作挖矿的地方，然后根据贡献算力的多少来分奖励。矿池选择小白的话建议直接交易所矿池，直接到账免去提现门槛。
这里选择币安矿池。

1.币安矿池注册地址：https://accounts.binancezh.top/zh-CN/register?ref=274087129

2.注册完以后进入币安矿池。https://pool.binancezh.cc/.


3.选择好语言，算法选择Ethash，点击挖矿账户管理。
![](https://images.gitee.com/uploads/images/2021/0307/233915_09b4838a_8758987.png "屏幕截图.png")

4.点击添加挖矿账户输入你自己想的用户名创建即可。

![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/233943_6d9b06b9_8758987.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/234001_f23c7692_8758987.png "屏幕截图.png")

接下来就是下载挖矿软件了。

 **下载挖矿软件** 
这里我选择原版挖矿软件claymore。https://claymoredualminer.com/

不方便下载的话 我下载好了 https://wwa.lanzous.com/ir6ZRllglpe/
解压密码claymore

解压好之后（可能会被杀毒软件报毒无视即可）
找到start.bat文件，右键编辑，修改成如下即可，把xxx修改成之前创建挖矿账户的名字，
yyy改成随便一个名字标识你的电脑就行

EthDcrMiner64.exe -epool ethash.poolbinance.com:8888 -ewal xxx -eworker yyy -epsw x -asm 2 -dbg -1 -allpools 1 -mode 1

EthDcrMiner64.exe -epool ethash.poolbinance.com:8888 -ewalxxx -eworker yyy -epsw x -mode 1 -allpools 1

（上面两段用一段你能用就行了）
之后运行start.bat即可（可能会闪退检查杀毒软件或者使用我下方更新的另外一个挖矿核心）

等待一分钟如果出现下面样子说明就基本成功了

![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/234016_8d5ff3e5_8758987.png "屏幕截图.png")

等待15分钟去之前的矿池网站看一下如果你的页面也长这样的话说明就成功了，第二天等着查看收益就好了
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/234021_149a80b3_8758987.png "屏幕截图.png")

 **如何ETH转换成USDT** 
之前很多人问我eth挖的太少也不能提现，不建议直接用eth提现，也不建议使用一键卖币功能，eth价格波动大，不建议拿手上，建议换成稳定币达到提现额度再提。

我的方法是把每天的eth卖成usdt（如果不够10usdt起卖点可以拿着等等），然后等够提现了再去提现或者直接花usdt，想卖的话找到eth/usdt的交易对进行现货交易就可以了。

 **什么是usdt** ：usdt是一种和美元锚定的虚拟货币，是虚拟货币交易市场上的通货，价格基本上和美元1:1不会变得。

变成usdt你之前挖的eth就不会因为eth的价格变化了，当然eth价格上涨也更你无关了，不过建议我们这种小白来讲，还是把每天的eth换成usdt好，不过如果你不想立马变现的话我还是建议用你挖矿来的usdt去投资别的虚拟货币，没准你投资的货币变成一下个狗狗币了呢。

具体讲讲如何提现：基本就通过交易所法币交易提现，最近通过提现了一次没有什么问题，不过建议还是卖成usdt提现，eth直接提现最低门槛太高不方便。

 **FAQ** 

Q：为什么我挖了一天了没有收益

A：币安矿池收益计算周期是北京时间昨日上午8:00至今日上午8:00，每日收益将在北京时间上午10:00至下午18:00进行结算。结算完成后直接打款至用户的币安矿池钱包。一整天是24小时嘛，如果不是请等12点之后再看看，大概率就有了。

Q：为什么我卖不了我挖的eth呀

A：首先你需要把你的eth从矿池账户划转到现货账户，再者你卖一次币最少需要10usdt

Q：运行提示“不是内部或外部命令，也不是可运行的程序”

A：格式有问题，建议不要使用记事本来编辑，下载个vscode之类编辑器使用，或者把复制下来的文字粘贴到word再复制黏贴到记事本中

