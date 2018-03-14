# **黄杰**
---

# 个人信息

 - 男/1993 
 - 本科/西华师范大学/**电子信息工程**
 - 工作经验：1年半
- 手机： ```15182998005```
- 邮箱： ```jackhuang719668276@163.com```
- 微信：```JackHuang_China```
 - **主页**： www.linuxforstudents.com
 - **Github**： https://github.com/HuangJiaLian
---

# 自我评价
 
**动手能力强，Linux运用自如，精通C和Python，英语听说读写俱佳(六级)。**

---

<div STYLE="page-break-after: always;"></div> 

# 项目经历

## 上海鹰捷智能科技有限公司 （ 2016年8月至今 ）

###  **1. DataMatrix（DM）解码项目**（ C, C++ ）
#### 简介
我负责获取DM码所有关键点位置以及得到DM码的大小。该部分约占
整个DM码图像处理**50%**，它连接起图像预处理和采样译码，是整个DM
解码算法中关键的一部分。

#### 完成情况
- 算法能够很好的应对常规的DM二维码，准确找出关键位置;
- 算法对码大小为24~132的106张DM码图片进行了测试,识别
正确率达到**81.13%**，满足常规应用需要。


### **2. QR解码项目** ( C, C++ )
#### 简介
我独立完成QR图像处理算法和解码算法的编写，配合底层嵌入式工程师
移植解码算法到嵌入式平台。且项目采用了两种不同的方法实现图像处理。

#### 完成情况
算法能够快速准确地实现QR码的解码，实现了鹰捷公司自主解码算法
**从0到1**的突破。

###  **3. USB通讯程序**( C, C++, LibUSB )
#### 简介
该程序将嵌入式平台采集的图片通过USB传送到上位机,实现快速传输。
在该项目中我独立编写了下位机发送程序与上位机接收程序。其中下位机
数据发送程序，运行在新塘CPU; 上位机数据接收程序可运行在**Windows**
和**Linux**两种操作系统下。

#### 完成情况
完成该程序后公司产品使用USB传输，一张1M大小图片的传输时间为**0.5s**
(其他公司使用串口要大约60s),大大提高了工作效率 。

<div STYLE="page-break-after: always;"></div> 

### **4. 闪电开票项目**（ Python ）
#### 简介
增值税发票的手工填写非常繁琐：开发票速度慢，税号太长容易填错。
**闪电开票**项目利用扫描枪扫码实现快速开票。我独立开发了一款辅助快速
开票的软件---"**发票助手**"
#### 完成情况
**发票助手V1.3** 使用各种型号2D扫描枪，结合支付宝的发票管家或微信的票开开
小程序，实现闪电开票，开专用增值税发票的的时间由**5分钟缩短为1秒钟**，极
大地提升了开发票的速度。


 
## 西华师范大学 （ 2012年9月 ~ 2016年6月 ）
### **基于树莓派的线性CCD扫描翻译装置** 

[Raspberry Pi-based Scanning Translation Device [链接] ](http://www.linuxforstudents.com/wp-content/uploads/2016/06/CCD%E7%BF%BB%E8%AF%91%E8%A3%85%E7%BD%AE.pdf)
#### 功能
- 由**Raspberry Pi**获取线性CCD的信号，保存为文本; ( C )
- 通过网络传输信号到Linux主机，为图像处理做准备; ( C , **TCP/IP** )
- 图像处理，包括放大信号，去噪声等; ( Python )
- OCR光学字符识别; ( Tesseract )
- 字符处理,发音; ( Espeak, Shell, AWK )
- 翻译。( 有道API, Python )

#### 成绩
该设计获得**94**分的成绩，被评为**优秀毕业设计**。


---

<div STYLE="page-break-after: always;"></div> 

# 开源项目和作品

## 开源项目

### **1. China Weather Station** ( Python )： 
https://github.com/HuangJiaLian/cws 

这是一个在Linux操作系统下获取中国各个城市天气的软件。
它有如下五个基本功能：

- 显示当前的天气状况
- 显示今天的各项指数
- 预报未来５天的天气状况
- 显示日出日落时间
- 显示天气预警信息

### **2. Jball** ( C )： 
https://github.com/HuangJiaLian/Jball 

这是我开发的一个Linux下运行的终端游戏。该游戏结合了Linux 系统编程，
我在写游戏的同时对系统编程有了更深的了解。

## 作品

### **1. LinuxForStudents网站**  www.linuxforstudents.com 
该网站的主要目标是推广Linux使用技能。
### **2. 技术文章**
 - **CCD翻译装置**：[Raspberry Pi-based Scanning Translation Device [链接]](http://www.linuxforstudents.com/wp-content/uploads/2016/06/CCD%E7%BF%BB%E8%AF%91%E8%A3%85%E7%BD%AE.pdf)
 
 - **DataMatrix解码**: [DataMatrix Decoder [链接] ](http://oycwqc1xi.bkt.clouddn.com/FalconDM_decoder.pdf) 

 - **QR Code Generator**： [Jtext2code–Use Python to make a QR code generator [链接]](http://www.linuxforstudents.com/186) 
 
---

<div STYLE="page-break-after: always;"></div> 

# 技能清单

- **Linux**：**5年的linux使用经验**，在Linux下开发得心应手。
- **C**：解码项目,USB通讯等多个项目均由C,C++开发。
- **Python**：熟练使用Python开发闪电开票,China Weather Station 等项目。
- **Git**:熟练掌握git的使用。
- **Shell编程**：擅长在Linux环境下使用Shell脚本进行自动化操作。
- **全国计算机等级考试三级**：嵌入式开发技术。
- **English**: **英语应用能力优秀**，**大三过英语六级**，能够毫无压力
地阅读专业文献，**具有与国外企业进行技术沟通的经验**。

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
