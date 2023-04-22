<!-- markdownlint-disable MD033 -->

# BlackBEQuery

**插件已停止开发，请移步[LLBlackBEEx](https://github.com/lgc-LLSEDev/LLBlackBEEx)**

Version: 1.0.2

Author: [student_2333](https://github.com/lgc2333)

BlackBE 站长：NyanCatda [云黑官网](https://blackbe.xyz) [赞助云黑](https://afdian.net/@BlackBE)

## 插件介绍

插件对接 BlackBE OpenAPI 3.0 实现插件所有功能

本插件是本人写的[BlackBE](https://github.com/lgc2333/BDSPyRunnerPlugins/tree/main/BlackBE)插件的查询功能在 LLSE 的复刻，可以实现在服务器内查询公有库~~或你的私有库~~的违规记录

_注：LLSE 暂不支持 GET 请求带 Headers，因安全性考虑，暂不实现查询私有库._

使用方法：`/blackbe [XboxID/QQ号/XUID]` ，如不带参数则打开输入查询内容表单

## 图骗欣赏

![1](https://media.githubusercontent.com/media/lgc-LLSEDev/readme/main/BlackBEQuery/1.jpg)

![2](https://media.githubusercontent.com/media/lgc-LLSEDev/readme/main/BlackBEQuery/2.jpg)

## 安装方法

- 将 `BlackBEQuery.lxl.js` 文件放入 `BDS根目录/plugins` 文件夹内

## 联系我

QQ：3076823485  
吹水群：[1105946125](https://jq.qq.com/?_wv=1027&k=Z3n1MpEp)  
邮箱：<lgc2333@126.com>

## 赞助

感谢大家的赞助！你们的赞助将是我继续创作的动力！

- [爱发电](https://afdian.net/@lgc2333)
- <details>
    <summary>赞助二维码（点击展开）</summary>

  ![讨饭](https://raw.githubusercontent.com/lgc2333/ShigureBotMenu/master/src/imgs/sponsor.png)

  </details>

## 更新日志

- 2022.2.17
  - 首次发布
- 2022.2.18
  - 重新格式化代码
  - 一些小修改
- 2022.2.25
  - 引入 ESLint 规范代码（以前 Python 写多了现在变量老忘声明，这波属于 ESLint 直接教我做人）
  - 修改了插件加载时输出 Log 的代码（Object.prototype 没有 entries 函数……我学的假 ES6？）
