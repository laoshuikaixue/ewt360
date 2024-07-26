# ewt360

## 前言
> 请不要滥用此仓库中的内容  
> ewt有时可能会做更新，程序不保证一定能用  

## 目前实现的功能

- [x] 绕过会员检测
- [x] 绕过点击检测（无数据上报 慎用）

## 使用说明

 - ## 绕过会员检测

   ![图片](https://github.com/user-attachments/assets/da92d66a-a441-4d61-ac57-33b448fae0af)

   此功能用于观看视频出现此提示的绕过 你需要安装油猴脚本插件 安装方法请自行上网搜索

   随后添加这个脚本：https://greasyfork.org/zh-CN/scripts/500965-ewt360-permission-interceptor 即可绕过

   原理：

   ![图片](https://github.com/user-attachments/assets/008bc04e-5118-4633-99e6-b48f9be353b1)

   拦截返回内容 修改这部分内容 对播放器进行欺骗

 - ## 绕过点击检测：

   首先 打开视频页面
   
   随后 打开浏览器的DevTools（按F12或右键 这里推荐使用EDGE以及谷歌浏览器）
   
   ![图片](https://github.com/user-attachments/assets/25b47c75-28cd-47c0-8a61-aa2c664db7fb)
   
   找到此JS 右键点击 点击替代内容（如果没有 请更换上述推荐浏览器并检查浏览器版本）
   
   在文件导航对话框中，选择本地计算机上的一个文件夹来存储要替换的资源文件，例如 **C:\Users\myusername\overrides**，然后单击 **选择文件夹** 按钮

   DevTools 警告你必须具有对该文件夹的完全访问权限，并且不应泄露任何敏感信息

   单击 **允许** 按钮 随后在打开的页面中粘贴项目中txt文本内的内容（JS加密了 可能会无响应 可以修改后缀后直接替换掉这个文件）

   随后刷新一次页面 弹出

   ![图片](https://github.com/user-attachments/assets/3e33bf66-4f97-404d-a578-be8f88eb9002)

   即代表加载成功 随后关闭DevTools 即可播放视频

   ### 注意：此操作会导致教师后台无点击通过率数据 谨慎使用

   ### 如果你需要加载补丁 你需要每次打开页面的时候都打开DevTools进行一次刷新操作

## 推荐的同类项目

- [刷课+自动完成选择题的工具箱](https://greasyfork.org/zh-CN/scripts/471375-ewt-ewt-e%E7%BD%91%E9%80%9A-%E5%88%B7%E8%AF%BE-%E8%87%AA%E5%8A%A8%E5%AE%8C%E6%88%90%E9%80%89%E6%8B%A9%E9%A2%98%E7%9A%84%E5%B7%A5%E5%85%B7%E7%AE%B1) 刷课+自动完成选择题的工具箱（油猴脚本）
- [刷课+自动完成选择题的工具箱](https://github.com/SudoSuBash/EWT-Killer-Box) 上述脚本开源地址  
- [ewt360](https://github.com/landuoguo/ewt360) Python实现刷e网通假期课程进度（停止维护）

## 后言

此仓库内容仅供学习参考使用 学习后请立即删除 因使用者产生的个人问题与本仓库开发者无关

**禁止滥用**本仓库的内容 若进行二开请严格遵守license 严禁各类**商业行为**

若发现失效等情况 请在issues提出 并欢迎PR

## Sponsors

暂无:(
