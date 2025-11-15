<div align="center">
    <h2>
        <a href="#">
            <img width="128" height="128" alt="pangolin_smart" src="https://github.com/user-attachments/assets/398b8c03-b696-4ffe-8c39-8d2cf8e731a4" />
        </a>
        <br>
        Pangolin <span> | </span>穿山甲
    </h2>
    
</div>

<div>
  <h1>
      简介
  </h1>
<p>Pangolin(穿山甲)，是一款纯自研C2平台，支持Windows、Linux平台，支持TCP、HTTP/HTTPS协议，具有命令执行、文件管理、网络管理、进程管理、屏幕截图、权限维持、权限提升、内网扫描、内网穿透等实用功能，针对该平台深度定制了一台免杀方案，可绕过某数字软件、某绒，某擎、某电脑管家、WinDefender、卡巴斯基等常见杀软实现上线、内网扫描、内网穿透、权限维持，其中部分功能依赖开源或闭源项目，在此一并表示感谢，如有侵权，联系我删除。整体界面</p>
    <img width="2878" height="1716" alt="image" src="https://github.com/user-attachments/assets/53864923-d97b-4e4b-8cd0-88b4f3ba042c" />

</div>

## 安装
- 仔细阅读免责声明，同意可继续  
  <img width="478" height="208" alt="image" src="https://github.com/user-attachments/assets/76e49c46-579a-4ece-8db5-4273f05096fc" />
- 配置服务端IP和端口
一般为VPS公网IP，端口可1-65535之间的未被占用的端口  
  <img width="478" height="208" alt="image" src="https://github.com/user-attachments/assets/7e08e2ce-2b39-45c1-bc36-dd9fbe4d8f17" />
- 如果没有域名上线需求，一般保持默认即可  
  <img width="478" height="208" alt="image" src="https://github.com/user-attachments/assets/a1dcf708-ba0b-4272-932a-64d3bfd09915" />
 - 启动成功，安装极其简单，无任何依赖  
    <img width="478" height="208" alt="image" src="https://github.com/user-attachments/assets/53864923-d97b-4e4b-8cd0-88b4f3ba042c" />
## 快速上手
- 系统设置-选择输出格式，如powershell。  
  <img width="672" height="460" alt="image" src="https://github.com/user-attachments/assets/7722f302-1d1e-42f0-95b1-022a872d5dd4" />
- 执行即可上线  
  <img width="712" height="430" alt="image" src="https://github.com/user-attachments/assets/ab4c61c2-4799-4156-b8e9-ba5c253554b4" />
## 常用场景
- 场景1：asmx/soap上线->提权->抓Hash  
低权限shell，绕过某数字杀软，提权到SYSTEM，抓Hash,全程不用创建任何新的进程，[观看完整演示视频](https://gnetfairy.github.io/pangolin/videos/20251112_221615.mp4)  
![ezgif-42300a3a03279f4f - 副本](https://github.com/user-attachments/assets/ed307076-e149-41c3-9d3e-91a785373777)
- 场景2：攻防演练钓鱼上线->抓密码->内存加载fscan扫描，鼠标右键维权  
HVV场景下钓鱼上线，内存加载fscan，frp等避免安全软件告警，[观看完整演示视频](https://gnetfairy.github.io/pangolin/videos/20251112_231302.mp4)  
 ![ezgif-598e9b262b8f1039](https://github.com/user-attachments/assets/da8625e5-1bba-43ea-9dd4-cf7ca0c00e42)
- 场景3：默认IP TCP上线，可配置域名上线冗余，如IP被被封，可自动切换域名上线（如云函数）  
  默认TCP
  <img width="1268 " height="602" alt="image" src="https://github.com/user-attachments/assets/84398f6d-0023-41f6-a4b8-b23c53eb8007" />
  IP被拉黑后，自动切换云函数上线
  <img width="2540" height="1210" alt="image" src="https://github.com/user-attachments/assets/85289fe1-50c0-4533-a440-6c2d37c3f42a" />

## 更新
### V1.0.1.0
首个Community版本(无免杀模块、团队协作、jsp/asmx/soap上线等部分功能)发布，Team和Enterprise版本不公开发布。
## 免责声明
本工具仅限用于授权的安全测试、教育目的和合法研究。任何未经授权使用本工具对系统或网络进行测试的行为均属非法。使用者应对其行为负全部责任，开发者不对任何误用或损害承担法律责任。



