## 最近更新

#### [v0.0.6] - 2022-02-15

**更新**  

- 修复xray不运行的bug



#### [v0.0.5] - 2022-02-09

**更新**  

- 修复宿主机更改nuclei配置后docker使用不生效的bug，扫描器镜像bywalkss/darkangel更新到v0.0.4
- 更新nuclei_config.yaml、nuclei_new_temp_config.yaml文件



#### [v0.0.4] - 2022-02-07

**更新**  

- 更新xray到1.9.4版本，并更新配置文件
- 更新nuclei到2.8.8版本，并更新配置文件
- 添加遗漏的httpx、naabu、crawlergo、whatweb



#### [v0.0.3] - 2022-01-17

**更新**  

- 增加只添加hackerone和bugcrowd资产模块 - --add-new-domain
- 增加以时间间隔为条件，对es库中pdomain进行漏洞扫描 - --scan-domain-by-time



#### [v0.0.2] - 2022-12-27

**更新**  

- ES-IP填写错误后进行错误提示
- 改正tools目录下nuclei、xray等文件的执行权限为777



#### [v0.0.1] - 2022-12-12

**功能**  

- hackerone资产监听
- bugcrowd资产监听
- 自定义资产添加
- 子域名扫描
- 网站指纹识别
- 漏洞扫描
- 漏洞报告自动生成
- 企业微信通知扫描结果
- 前端显示扫描结果

## 待上线功能

- 漏洞结果截图
- 优化漏洞报告template
- 添加通知tg/slack/email的api
