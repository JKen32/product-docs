# 发布自动化项目
发布自动化项目允许您将编辑成功的自动化流程发布到控制台或流程市场中，以便后续机器人执行或共享流程。

自动化项目发布到控制台后，将存储在流程包管理页面，以便分配给指定机器人执行。而发布到流程市场后，将存储在您指定的流程市场中，以便实现共享。

要实现发布流程，从工具栏的设计->发布中选择您想要发布的位置，然后单击它。

![发布项目](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/choosePosition.PNG)

## 发布流程
1. 创建一个自动化项目。项目示例参看[创建自动化项目](./CreateProject.md)
2. 在工具栏的设计->发布选择发布的位置：
    * 发布到控制台
    
        ![发布到控制台](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishToConsole.PNG)
    a. 流程包名称默认情况下为项目名称，可进行更改。
    b. 将最新版本号添加至项目中。若更改版本号信息，需注意的是最新版本号要大于当前版本号。
    c.(可选)备注主要用于对当前发布的流程进行简单介绍。

    * 发布到流程市场
    
        ![发布到流程市场](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishToFlowmarket.PNG)
    a. 选择流程市场，以作为自动化项目最终的存储位置。首次发布需通过“管理流程市场”配置您的市场，具体步骤请参考[管理流程市场](../Market.md)。
    b. 流程包名称默认情况下为项目名称，可进行更改。
    c.将最新版本号添加至项目中。若更改版本号信息，需注意的是最新版本号要大于当前版本号。
    d. (可选)图标主要用于对当前发布的流程进行标识。
    e.输入描述信息，以介绍此流程具体的作用。
    f.(可选)标签用于定义当前流程。

3. 单击“发布”，该项目将会发布到指定位置。
4. 发布成功后，将显示一个信息提示框，显示：
    * 发布成功的项目名称
    * 该项目的版本号

        ![发布成功](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishSuccess.PNG)