# FE文库知识点落地项目
## 1.接口地址：http://newicafe.baidu.com/discussion/space/baiduwenku?discussId=5159&discussViewType=DISCUSS_VIEW_TYPE_TABLE&mode=TABLE_SHOW

## 2.icode地址：
     baidu/wenku/wenku-wapapp-kgview 模块

## 3.相关文档地址:
    http://agroup.baidu.com/wkkg/home

## 4.发布访问地址：https://wk.baidu.com/kgview/6465a700a6c30c2259019e7c

## 5.知识图谱项目负责：郝萌
      后端总负责数据 挂载：高志昌 
      后端接口负责：李锴   
      后端数据：东宇 
      pm总负责：方舟
      pm：胡爽

## 6.项目结构：
     启动命令： wenku-wapapp-kgview 模块  sh dev.sh  d 本地 
                             base 模块  npm run debug  
              wenku-wapapp-common 模块  sh  dev.sh d 


## 7.试题解析方案
![图片](https://bos.nj.bpc.baidu.com/v1/agroup/d9017bbba6dcd450e7ffc17f6e6a9d1e8968f76a)
## 8. 项目目录结构
```html
├─wenku-wapapp-kgview
│  ├─client                 # 前端代码
│  │  ├─page                # 前端页面
│  │  ├─static              # 前端非模块化静态资源
│  │  └─widget              # 前端组件
│  └─server                 # 后端代码
│      ├─action             # action是指MVC中的路由动作，处理页面请求
│      ├─lib                # 可以存放一些通用库
│      └─model              # 可以存放一些数据层代码，如后端API请求等
│      └─ router.js         # AppRouter路由，用于处理自动路由无法满足的需求
│  ├─fis-conf.js            # FIS编译配置

```
## 9.技术方案
1.入口node加载模块tpl

2.前端：doT js 模板引擎 渲染

3.文档，试题，视频，模板解析

![图片](http://bos.nj.bpc.baidu.com/v1/agroup/2cee32d25e6c3ee3dfc2b07cecb0fc41bd2fe0e5)

4.数据格式json 【试题解析bdjson格式模块化处理】


![图片](http://bos.nj.bpc.baidu.com/v1/agroup/6c92a9f5221752173849ddabaf041d4b6f04a0cf)







