## 硬件准备
**2\*Pico**  
**2\*~~EBYTE-E28-2G4T12S(SX1280 无线串口模块)~~ might be insteaded by HC-8 because of UART**  ~~*我选择了这个模块因为它相对便宜的售价和在使用全向天线时长达3km的控制范围*~~  
**1\*ULN2003驱动板+28BYJ4步进电机**  *这是一个即将改动的设计，因为我发现它不太适合应用在这种场合中(转速偏慢)*  
**1\*摇杆电位器**  *我使用的是16mm大小，阻值10k，上下自动回中型*  
**1\*0.8模的齿轮**  *需要一个合适的齿数，目前看来35齿左右都较合适*  ***它一定要和电机配合适当***  
**2\*PCB在[这里](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/tree/main/PCB)**  ***你需要一家PCB制造厂商，我推荐[嘉立创](https://www.jlc.com/)的免费打样***  
**一些线材**  
**焊接工具**

## 组装
在PCB上已经有十分完善的丝印标注，你可以直接将对应模块放置到位并锡焊  
你应该在其中一块板上放置电位器，另一块板连接步进电机驱动板并合理的为它们供电  
**注意：请优先将电位器和电机驱动板焊接在1号接口，因为相对超前的PCB设计，按钮和2、3号电位器/电机的焊盘已经预留，但它们还不能发挥作用**  
**小心：各个模块(尤其是邮票孔)似乎不太适合使用电烙铁直接焊接，恒温热风枪是最好的选择(一定要恒温，否则极易过热损坏)，但我用烤箱的效果十分好**

## 软件刷写
micropython的推荐IDE是[Thonny](https://thonny.org/)  
**Pico的初次使用请参见 [树莓派官网](https://www.raspberrypi.com/)**  
下载最新发布的脚本：[发布页](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/releases)  
分别将两个文件配置为你想要的参数并刷入对应的设备  

## 完成
！！！！！
