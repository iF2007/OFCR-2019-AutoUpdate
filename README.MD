# OFCR2019  

* 附OFCR2019 rFactor mod下载链接（不含Vehicles文件夹）  
~~[百度网盘，提取码r6em](https://pan.baidu.com/s/14BYf29h7_AemJl2AF6HzSg)~~      
~~[Google Drive](https://drive.google.com/open?id=1nzLE-shLsc9lgF4T0oiTpUhLOdZjQX9f)~~    
已知内部文件损坏问题，待修复  

**本文档将引导如何设置并进行OFCR rFactor mod热升级功能**.

用户可从以下两种选项中任选一项进行设置: (1) 使用 `Git`命令提示符(效率较高); (2) 带有图形界面的[GitHub桌面版](https://desktop.github.com/)，易于上手操作

## 命令提示符

1. [下载Git](https://git-scm.com/downloads)，选择适用于你的操作系统版本（32/64位）_参与过公测的用户请忽略这一步_;  
2. 在 `\\rFactor\GameData\Vehicles\`文件夹下新建`OFCR2019`文件夹;  
3. 右击 `OFCR2019`文件夹, 并选择 `Git Bash Here`，弹出如下窗口  
![image](https://i.ibb.co/BV6Q86j/TIM-20190107234748.png)  
**或者**  
4. 打开Windows的命令提示符，使用cd指令指向`OFCR2019`文件夹，如图所示  
![image](https://i.ibb.co/8NZjC8g/TIM-20190107234945.png)  
5. 输入`git init .`进行初始化;  
6. 设置git下载节点，海外用户推荐使用GitHub节点`git remote add origin https://github.com/OMGCA/OFCR2019.git`;  
中国大陆用户推荐使用阿里云节点`git remote add origin https://code.aliyun.com/OMGCA/OFCR2019.git`;  
**注意：这里命令行中的`origin`可以是你任意设置的词**  
7. 从节点下载文件，输入`git pull origin master`(origin处要和你之前设置的词相匹配)。  
**以上为初始化设置过程，若进行更新操作，只需执行步骤7即可**  
注意：如果想要修改节点，只需在更新前输入`git remote set-url `后接你想要更换的节点即可。  


## GitHub桌面版设置  

1. [下载GitHub桌面版](https://desktop.github.com/)，由于GitHub没有大陆节点，下载速度比较慢，请耐心等待;  
2. 首次打开GitHub桌面版可能会提示注册账号，该步骤可以跳过，如果想要通过GitHub进行涂装/车手更新则需要注册账户;  
3. 打开后出现如下界面，选择最右侧的`Clone a repository`  
![image](https://i.ibb.co/z4vgckn/TIM-20190107235732.png)  
4. 首先选择Vehicles文件夹，如图所示  
![image](https://i.ibb.co/xHSmFH0/TIM-20190107235902.png)  
5. 其次设置下载节点，国外用户推荐使用GitHub节点，在上方输入`https://github.com/OMGCA/OFCR2019.git`  
中国大陆用户推荐使用阿里云节点，在上方输入`https://code.aliyun.com/OMGCA/OFCR2019.git`  
6. 出现如下界面表示正在进行下载并等待下载完成，mod即可使用  
![image](https://i.ibb.co/jk78sX3/TIM-20190108000121.png)  

### 进行更新操作（桌面版）  
1. 打开如下界面后点击如图所示fetch  
![image](https://i.ibb.co/GHBQnJb/TIM-20190108000314.png)  
2. 右上角按钮更改为`pull origin`时代表有更新可用，此时再点击`pull origin`即可完成更新  
![image](https://i.ibb.co/cvwgF8t/TIM-20190108000432.png)  

使用桌面版进行配置后使用命令行进行更新只需重复命令行步骤中的1,3,7即可  

## 如何通过GitHub网页版上交涂装/车手文件  
1. 确保你已经有一个可用的GitHub账号  
2. [进入OFCR更新库](https://github.com/OMGCA/OFCR2019)，点击右上角的Fork  
![image](https://i.ibb.co/yFHYkFY/TIM-20190108000839.png)  
该操作会复制一份更新库到你的账号中并允许你在不修改原始库的情况下上传或更改文件 
(以上步骤为初始化，以下为每次提交更新的步骤）  
3. 进行提交前请确保你的repo与原始repo版本相同：
**如果你的repo首页有以下消息，请忽略该步骤**  
![image](https://i.ibb.co/Fn1Q0yS/TIM-20190108124029.png)  
* 1. 进入**你的**repo页面，点击New pull request  
![image](https://i.ibb.co/Gn2jZ8q/TIM-20190108123422.png)  
* 2. 左侧选择你的repo，右侧选择原始repo 
![image](https://i.ibb.co/4mdhBkh/TIM-20190108123731.png)  
* 3. 点击Create pull request  
![image](https://i.ibb.co/9tnK8Dj/TIM-20190108123810.png) 
* 4. 进入你的repo页面后点击pull request，找到你刚刚发起的request，点击Merge pull request  
![image](https://i.ibb.co/hDNYNMT/TIM-20190108123955.png)  
4. 选择到你更改过后文件的存放位置（以更新IXR涂装为例），点击右上角的Upload new files并按照提示进行操作  
![image](https://i.ibb.co/0t0F6cS/TIM-20190108000951.png)  
5. 上传完成后，在你自己的库中首页会出现`pull request`选项并点击  
![image](https://i.ibb.co/QCKZWXn/TIM-20190108001058.png)  
6. 点击`Create pull request`即可，OFCR管理人员即可看到你发起的文件修改申请并予以通过/不通过  
![image](https://i.ibb.co/vDvWj3L/TIM-20190108001213.png)  
