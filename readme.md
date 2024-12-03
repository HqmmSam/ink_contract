该程序用于在ink测试网上面部署智能合约，支持多钱包一键脚本部署

## 前提
* 系统 windows、linux、mac
* 运行环境node
* 钱包地址得有ink sepolia测试水


## 部署步骤

下载脚本
```
git clone https://github.com/HqmmSam/ink_contract.git
```

安装依赖
````
cd ink_contract
npm install
```

在.env文件中放入自己的私钥
```
PRIVATE_KEY1=0xffa121045239a42b44e6
PRIVATE_KEY2=0xbcef3399aedff2f9e8b2
```

运行
```
node deploy_ink.js
```
