※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※※

![immwrt界面](https://github.com/user-attachments/assets/75de3677-d51d-405d-998a-31eb02665788)

创建甲骨文账号尝试一年了，终于成功了，但是呢还有一步就是要创建虚拟机，成功了才能创建节点或者其他，由于本人当初选主区域选了是芝加哥，所以资源一直短缺，于是就想在电脑本地创建个脚本代替手动创建实例；脚本内容用文档修改里面的个人信息，然后保存，直接复制粘贴到带管理员的powershell或者管理员的终端运行即可，需要安装的插件，按照脚本报错的地址安装即可或者直接下载我已提供的（这里只在Windows测试运行，win10和win11，mac的还没测试）


♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥  ♥ ♥ 
![immwrt界面](https://github.com/user-attachments/assets/aae929f0-0028-4ceb-a6b1-0e4b02afc123)

！！！！前提准备工作：
①、登录oracle账号，点击右上角账号信息，把用户名（注册的邮箱）、用户名的OCID（SUBNET_OCID）和详细信息的OCID（TENANT_OCID），两者不一样，主区域（REGION）

②、在控制台-网络-创建VCN，名称随便填，主要是复制VCN的UCID

！！！以上的信息要打开脚本，然后把里面的信息填写


![immwrt界面](https://github.com/user-attachments/assets/c196f381-65d0-45cd-b5d5-0cd3caf6696d)

![immwrt界面](https://github.com/user-attachments/assets/31e2d177-2f49-4428-9425-0ad185c81859)

......................................................................................................................

![immwrt界面](https://github.com/user-attachments/assets/2e290aa5-d25e-4567-ad09-2c94024600d8)


脚本运行到创建API密钥的时候，需要你:

📌 配置步骤1：控制台 → 右上角头像 → 我的个人资料 → API密钥


📌 配置步骤2：点击「添加API密钥」→ 选择「粘贴公共密钥」→ 复制下方公钥粘贴

![immwrt界面](https://github.com/user-attachments/assets/08f716b1-b39c-49b8-8628-e1d7143cea61)


📌 配置步骤3：点击「添加」，配置完成后回到本窗口按【回车】继续

![immwrt界面](https://github.com/user-attachments/assets/ba17a3e7-c46a-4add-8444-43d539fe7b1c)
