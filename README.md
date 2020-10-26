## run the project in the local:  
1.clone the project:  
```
git clone https://gitee.com/quxiaoming/taro-mall.git 
```
2.open the project in the VScode;  
### 3. install the node and build the project into the nodev 12.16.0   
1.install the node:  
```
source ~/.bash_profile  
nvm install v12.16.0
```
2.change the project into the node 12.16.0 :
```
nvm use v12.16.0
```
### 4.install the @tarojs/cli@1.3.27:  
```
npm install -g @tarojs/cli@1.3.27
```
### 5.npm install the dependece:  
```
npm install 
```
### 6.开启本地静态资源服务:
```
npm run assetsServe
```
### run the project in the h5 or wechat miniprogram:  
open a new window, put the code into the below
```
source ~/.bash_profile  
nvm use v12.16.0 
npm run dev:h5 
```
[Taro 多版本共存问题](https://nervjs.github.io/taro/docs/GETTING-STARTED/)   
[使用nvm管理node与npm版本](https://juejin.im/post/6844903861157642247)   
## Learning Resouces:  
source code: 
[quxiaoming / taro-mall](https://gitee.com/quxiaoming/taro-mall)   
[mall-max 电商项目模版](http://taro-ext.jd.com/plugin/view/5de8754fbd239e2ab60fa8b2)   