# ueditor-web
This is a ueditor web project.

抽空完成了ueditor的集成，疑问最近问问题的博友太多，我又没空一一协助解答，所以还是附上源码比较好办事；

项目检下来之后，注意两点：
  1.由于是demo，很多模块都没有加到项目中来，只集成了必须的，所以/static/ueditor/ueditor.config.js 中的serverUrl 请根据后端项目的情况，进行调整；
    最好是做成环境区分的参数；
  2.后端项目检下来之后，里面具体与文件服务器对接的部分，需要大家自己对接完成，因为每家公司用的文件存储不尽相同，所以此处只提供思路。
  
  npm run dev 
  项目跑起来之后，访问地址：http://localhost:8080/#/ueditor
