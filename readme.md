
[Awesome]: icons/awesome.svg "star > 2000"
[Green]: icons/Green.svg "最近一周有更新"
[Yellow]: icons/Yellow.svg "最近一年没有更新"
[Archived]: icons/archived.svg "项目已归档"
      
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<hr>
	<p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://github.com/botpress/botpress">
			<img src="https://sindresorhus.com/assets/thanks/botpress-logo.svg" width="180" alt="Botpress">
		</a>
		<br>
		<sub><b>Botpress is an open-source conversational assistant creation platform.</b></sub>
		<br>
		<sub>They <a href="https://github.com/botpress/botpress/blob/master/.github/CONTRIBUTING.md">welcome contributions</a> from anyone, whether you're into machine learning,<br>want to get started in open-source, or just have an improvement idea.</sub>
		<br>
		<br>
		<br>
		<a href="https://segment.com">
			<img src="media/segment-logo.svg" width="180" alt="Segment">
		</a>
		<br>
		<sup>
			Save time setting up analytics with Segment. <a href="https://segment.com/jobs">We're hiring!</a>
		</sup>
	</p>
	<hr>
	<br>
	<br>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Just type <a href="https://node.cool"><code>node.cool</code></a> to go here. Check out my <a href="https://blog.sindresorhus.com">blog</a> and follow me on <a href="https://twitter.com/sindresorhus">Twitter</a>.</sub>
	</p>
	<br>
</div>

**此项目是 [awesome-nodejs](https://raw.githubusercontent.com/sindresorhus/awesome-nodejs/master/readme.md) 中文版，每天定时同步（上次同步时间：2020-04-24 16:09:56）**

顺便推荐一个 Go 的中文列表 [awesome-go-cn](https://github.com/yinggaozhen/awesome-go-cn/)

**小图标说明** :


小图标 | 说明  
:-:|-
![awesome][Awesome] | star > 2000
![最近一个周有更新][Green] | 最近一周有更新。可以基本判断当前库处于积极维护状态。
![最近一年未更新][Yellow] | 最近一年没有更新。反应了此库的维护积极性不高，使用时需谨慎。
![归档项目][Archived] | 此项目已归档，不再更新，使用时需谨慎。
              
## 内容

- [包](#%E5%8C%85)
	- [黑科技](#%E9%BB%91%E7%A7%91%E6%8A%80)
	- [命令行程序](#%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%A8%8B%E5%BA%8F)
	- [函数式编程](#%E5%87%BD%E6%95%B0%E5%BC%8F%E7%BC%96%E7%A8%8B)
	- [HTTP](#HTTP)
	- [调试/分析](#%E8%B0%83%E8%AF%95%2F%E5%88%86%E6%9E%90)
	- [日志](#%E6%97%A5%E5%BF%97)
	- [命令行实用工具](#%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%AE%9E%E7%94%A8%E5%B7%A5%E5%85%B7)
	- [构建工具](#%E6%9E%84%E5%BB%BA%E5%B7%A5%E5%85%B7)
	- [硬件](#%E7%A1%AC%E4%BB%B6)
	- [模板](#%E6%A8%A1%E6%9D%BF)
	- [Web 框架](#Web%20%E6%A1%86%E6%9E%B6)
	- [文档](#%E6%96%87%E6%A1%A3)
	- [文件系统](#%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F)
	- [控制流](#%E6%8E%A7%E5%88%B6%E6%B5%81)
	- [流](#%E6%B5%81)
	- [实时](#%E5%AE%9E%E6%97%B6)
	- [图像](#%E5%9B%BE%E5%83%8F)
	- [文本](#%E6%96%87%E6%9C%AC)
	- [数量](#%E6%95%B0%E9%87%8F)
	- [数学](#%E6%95%B0%E5%AD%A6)
	- [日期](#%E6%97%A5%E6%9C%9F)
	- [URL](#URL)
	- [数据验证](#%E6%95%B0%E6%8D%AE%E9%AA%8C%E8%AF%81)
	- [解析](#%E8%A7%A3%E6%9E%90)
	- [人性化](#%E4%BA%BA%E6%80%A7%E5%8C%96)
	- [压缩](#%E5%8E%8B%E7%BC%A9)
	- [网络](#%E7%BD%91%E7%BB%9C)
	- [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93)
	- [测试](#%E6%B5%8B%E8%AF%95)
	- [安全](#%E5%AE%89%E5%85%A8)
	- [基准测试](#%E5%9F%BA%E5%87%86%E6%B5%8B%E8%AF%95)
	- [代码压缩](#%E4%BB%A3%E7%A0%81%E5%8E%8B%E7%BC%A9)
	- [身份验证](#%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81)
	- [授权](#%E6%8E%88%E6%9D%83)
	- [邮件](#%E9%82%AE%E4%BB%B6)
	- [工作队列](#%E5%B7%A5%E4%BD%9C%E9%98%9F%E5%88%97)
	- [Node.js 管理](#Node.js%20%E7%AE%A1%E7%90%86)
	- [自然语言处理](#%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86)
	- [流程管理](#%E6%B5%81%E7%A8%8B%E7%AE%A1%E7%90%86)
	- [自动化](#%E8%87%AA%E5%8A%A8%E5%8C%96)
	- [AST](#AST)
	- [静态网站生成器](#%E9%9D%99%E6%80%81%E7%BD%91%E7%AB%99%E7%94%9F%E6%88%90%E5%99%A8)
	- [内容管理系统](#%E5%86%85%E5%AE%B9%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F)
	- [论坛](#%E8%AE%BA%E5%9D%9B)
	- [写博客](#%E5%86%99%E5%8D%9A%E5%AE%A2)
	- [奇怪的](#%E5%A5%87%E6%80%AA%E7%9A%84)
	- [序列化](#%E5%BA%8F%E5%88%97%E5%8C%96)
	- [杂项](#%E6%9D%82%E9%A1%B9)
- [资源](#%E8%B5%84%E6%BA%90)
	- [教程](#%E6%95%99%E7%A8%8B)
	- [发现](#%E5%8F%91%E7%8E%B0)
	- [文章](#%E6%96%87%E7%AB%A0)
	- [时事新闻](#%E6%97%B6%E4%BA%8B%E6%96%B0%E9%97%BB)
	- [视频](#%E8%A7%86%E9%A2%91)
	- [书](#%E4%B9%A6)
	- [博客](#%E5%8D%9A%E5%AE%A2)
	- [课程](#%E8%AF%BE%E7%A8%8B)
	- [备忘单](#%E5%A4%87%E5%BF%98%E5%8D%95)
	- [工具](#%E5%B7%A5%E5%85%B7)
	- [社区](#%E7%A4%BE%E5%8C%BA)
	- [杂项](#%E6%9D%82%E9%A1%B9)
- [相关的列表](#%E7%9B%B8%E5%85%B3%E7%9A%84%E5%88%97%E8%A1%A8)

## 包

### 黑科技
*翻译出错了? 试试 [英文版](readme_en.md#Mad%20science) 吧~*

- [webtorrent](https://github.com/feross/webtorrent) - **star:21725** 可在 Node.js 和浏览器使用的流式 Torrent 客户端 ![star > 2000][Awesome] 
- [peerflix](https://github.com/mafintosh/peerflix) - **star:5397** 流式 Torrent 客户端 ![star > 2000][Awesome] 
- [dat](https://github.com/datproject/dat-node) - **star:496** 数据集的实时复制和版本控制
- [ipfs](https://github.com/ipfs/js-ipfs) - **star:4353** 分布式文件系统，用于将所有计算设备与同一文件系统连接起来 ![star > 2000][Awesome] 
- [stackgl](https://github.com/stackgl) - 基于 browserify 和 npm 的 WebGL 开放软件生态系统
- [peerwiki](https://github.com/mafintosh/peerwiki) - **star:299** 建立在在 BitTorrent 上的维基百科
- [peercast](https://github.com/mafintosh/peercast) - **star:450** 将种子视频流式传输到 Chromecast
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - **star:3830** 干净、可读比特币库 ![star > 2000][Awesome] 
- [Bitcore](https://github.com/bitpay/bitcore) - **star:3601** 纯净、强大的比特币库 ![star > 2000][Awesome] 
- [PDFKit](https://github.com/devongovett/pdfkit) - **star:6091** PDF 生成库 ![star > 2000][Awesome] 
- [turf](https://github.com/Turfjs/turf) - **star:5176** 模块化地理空间处理和分析引擎 ![star > 2000][Awesome] 
- [webcat](https://github.com/mafintosh/webcat) - **star:405** 使用 WebRTC 跨 web 的 p2p 管道，它使用 GitHub 私有/公共密钥进行身份验证
- [NodeOS](https://github.com/NodeOS/NodeOS) - **star:6192** 第一个由 npm 驱动的操作系统 ![star > 2000][Awesome] 
- [YodaOS](https://github.com/yodaos-project/yodaos) - **star:1011** 人工智能操作系统
- [Brain.js](https://github.com/BrainJS/brain.js) - **star:10920** 机器学习框架 ![star > 2000][Awesome] 
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - **star:6578** 图论(又称网络)建模与分析 ![star > 2000][Awesome] 
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia 分布式哈希表
- [seedshot](https://github.com/twobucks/seedshot) - **star:179** 从浏览器共享临时 P2P 截图 ![项目已归档][Archived] 
- [js-git](https://github.com/creationix/js-git) - **star:3640** Git的 JavaScript 实现 ![star > 2000][Awesome] 
- [skale](https://github.com/skale-me/skale-engine) - **star:374** 高性能分布式数据处理引擎
- [xlsx](https://github.com/sheetjs/js-xlsx) - **star:20707** 纯 js 实现的 Excel 电子表格读写器 ![star > 2000][Awesome] 
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - **star:4675** 纯 JavaScript 实现的 Git ![star > 2000][Awesome] 

### 命令行程序
*翻译出错了? 试试 [英文版](readme_en.md#Command-line%20apps) 吧~*

- [np](https://github.com/sindresorhus/np) - **star:5149** 更好的 'npm publish' ![star > 2000][Awesome] 
- [npm-name](https://github.com/sindresorhus/npm-name) - **star:119** 检查 npm 上的包名是否可用
- [gh-home](https://github.com/sindresorhus/gh-home) - **star:156** 在当前目录中打开 GitHub 的仓库页面
- [npm-home](https://github.com/sindresorhus/npm-home) - **star:169** 打开 npm 包的页面
- [trash](https://github.com/sindresorhus/trash) - **star:1975** 更安全的 rm 命令替代品
- [speed-test](https://github.com/sindresorhus/speed-test) - **star:3321** 测试互联网连接速度和 ping ![star > 2000][Awesome] 
- [emoj](https://github.com/sindresorhus/emoj) - **star:1976** 从命令行文本中找到相关的表情符号
- [pageres](https://github.com/sindresorhus/pageres) - **star:9000** 捕获网站截图 ![star > 2000][Awesome] 
- [cpy](https://github.com/sindresorhus/cpy) - **star:260** 复制文件
- [vtop](https://github.com/MrRio/vtop) - **star:3559** 带图表的 top 命令 ![star > 2000][Awesome] 
- [empty-trash](https://github.com/sindresorhus/empty-trash) - **star:103** 清理垃圾
- [is-up](https://github.com/sindresorhus/is-up) - **star:332** 检查网站是否正常
- [is-online](https://github.com/sindresorhus/is-online) - **star:832** 检查网络连接是否正常
- [public-ip](https://github.com/sindresorhus/public-ip) - **star:555** 获取你的公共IP地址
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - **star:354** 在终端上复制粘贴
- [XO](https://github.com/xojs/xo) - **star:5040** 使用 Javascript happiness style 进行严格编码 ![star > 2000][Awesome] 
- [Standard](https://github.com/feross/standard) - **star:23593** Javascript 标准风格 - 一种风格规范 ![star > 2000][Awesome] 
- [ESLint](https://github.com/eslint/eslint) - **star:16218** JavaScript 的可插入 linting 实用程序 ![star > 2000][Awesome] 
- [dev-time](https://github.com/samverschueren/dev-time-cli) - **star:169** 获取 GitHub 用户当前的本地时间
- [David](https://github.com/alanshaw/david) - **star:916** 告诉你包的 npm 依赖项何时过期
- [http-server](https://github.com/indexzero/http-server) - **star:9369** 简单的零配置 http 服务器命令行工具 ![star > 2000][Awesome] 
- [Live Server](https://github.com/tapio/live-server) - **star:3136** 具有热重载功能的 HTTP-server ![star > 2000][Awesome] 
- [bcat](https://github.com/kessler/node-bcat) - **star:300** 管道命令输出到 web 浏览器
- [normit](https://github.com/pawurb/normit) - **star:206** 谷歌翻译与语音合成的终端工具
- [fkill](https://github.com/sindresorhus/fkill-cli) - **star:6074** 跨平台的进程杀死工具 ![star > 2000][Awesome] 
- [pjs](https://github.com/danielstjules/pjs) - **star:374** Pipeable JavaScript从终端快速筛选、映射和缩减
- [license-checker](https://github.com/davglass/license-checker) - **star:1031** 检查应用程序依赖项的许可
- [browser-run](https://github.com/juliangruber/browser-run) - **star:364** 在浏览器环境中轻松运行代码
- [tmpin](https://github.com/sindresorhus/tmpin) - **star:112** 将stdin支持添加到任何接受文件输入的CLI应用程序
- [wifi-password](https://github.com/kevva/wifi-password-cli) - **star:214** 获取当前wifi密码
- [wallpaper](https://github.com/sindresorhus/wallpaper) - **star:688** 更换桌面壁纸
- [brightness](https://github.com/kevva/brightness-cli) - **star:173** 改变屏幕亮度
- [torrent](https://github.com/maxogden/torrent) - **star:573** 下载种子
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - **star:255** 关闭所有Chrome选项卡，以提高性能，减少电池使用，并节省内存
- [alex](https://github.com/wooorm/alex) - **star:3449** 捕获不敏感、不体谅他人的编写 ![star > 2000][Awesome] 
- [pen](https://github.com/noraesae/pen) - **star:302** 从喜爱的编辑器在浏览器中实时预览 Markdown
- [subdownloader](https://github.com/beatfreaker/subdownloader) - **star:128** 电影和电视剧的字幕下载程序
- [dark-mode](https://github.com/sindresorhus/dark-mode) - **star:484** 切换 macOS 黑暗模式
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - **star:237** IP 定位程序
- [Jsome](https://github.com/Javascipt/Jsome) - **star:170** 漂亮的打印json，带有可配置的颜色和缩进
- [itunes-remote](https://github.com/mischah/itunes-remote) - **star:394** 可交互的方式控制 iTunes
- [mobicon](https://github.com/samverschueren/mobicon-cli) - **star:81** 移动应用图标生成器
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - **star:44** 移动应用程序启动屏幕生成器
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - **star:241** 相当不错的 git diff 到 HTML 的生成器
- [Cash](https://github.com/dthree/cash) - **star:7689** 纯JavaScript中的跨平台Unix shell命令 ![star > 2000][Awesome] 
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - **star:1110** 在终端试用npm包
- [jscpd](https://github.com/kucherenko/jscpd) - **star:1625** 源代码的复制/粘贴检测器
- [atmo](https://github.com/Raathigesh/Atmo) - **star:793** 服务器端 api 模拟工具
- [auto-install](https://github.com/siddharthkp/auto-install) - **star:1074** 在编写代码时自动安装依赖项
- [lessmd](https://github.com/linuxenko/lessmd) - **star:115** 终端使用的 Markdown
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - **star:2521** 找出哪些依赖在拖慢速度 ![star > 2000][Awesome] 
- [localtunnel](https://github.com/localtunnel/localtunnel) - **star:9787** 向外界公开本地主机 ![star > 2000][Awesome] 
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - **star:1835** 通过 SVG 共享终端会话
- [gtop](https://github.com/aksakalli/gtop) - **star:8106** 终端系统监控仪表板 ![star > 2000][Awesome] 
- [themer](https://github.com/mjswensen/themer) - **star:3308** 为编辑器、终端、墙纸、Slack等生成主题 ![star > 2000][Awesome] 
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - **star:4533** 一款生成代码展示图片的终端工具 ![star > 2000][Awesome] 
- [cash-cli](https://github.com/xxczaki/cash-cli) - **star:139** 转换170种货币
- [taskbook](https://github.com/klauscfhq/taskbook) - **star:7543** 命令行栖息地的任务、板子和注释 ![star > 2000][Awesome] 
- [discharge](https://github.com/brandonweiss/discharge) - **star:437** 轻松地将静态站点部署到Amazon S3
- [npkill](https://github.com/voidcosmos/npkill) - **star:3054** 轻松找到并删除旧的和沉重的node_modules文件夹 ![star > 2000][Awesome] 

### 函数式编程
*翻译出错了? 试试 [英文版](readme_en.md#Functional%20programming) 吧~*

- [lodash](https://github.com/lodash/lodash) - **star:44438** 提供一致性、自定义、性能和附加功能的实用程序库一个更好更快的Underscore.js ![star > 2000][Awesome] 
- [immutable](https://github.com/facebook/immutable-js) - **star:29551** 不可变数据集合 ![star > 2000][Awesome] 
- [Ramda](https://github.com/ramda/ramda) - **star:18687** 实用工具库，侧重于灵活的功能组合，通过自动套用和反转参数顺序启用避免变异数据 ![star > 2000][Awesome] 
- [Folktale](https://github.com/origamitower/folktale) - **star:1774** 用JavaScript编写通用函数式编程的库套件，允许编写优雅的模块化应用程序，减少bug，提高重用性
- [Mout](https://github.com/mout/mout) - **star:1191** 实用工具库与其他现有解决方案最大的区别在于，您可以选择只加载您需要的模块/函数，而不需要额外的开销
- [Bacon.js](https://github.com/baconjs/bacon.js) - **star:6230** 响应式函数编程 ![star > 2000][Awesome] 
- [RxJS](https://github.com/reactivex/rxjs) - **star:21696** 用于转换、组合和查询各种数据的响应式函数编程库 ![star > 2000][Awesome] 
- [Lazy.js](https://github.com/dtao/lazy.js) - **star:5892** 类似于 lodash/Underscore 的工具库，但具有延迟计算，这在许多情况下可以转化为优越的性能 ![star > 2000][Awesome] 
- [Kefir.js](https://github.com/kefirjs/kefir) - **star:1663** 响应式，专注于高性能和低内存使用

### HTTP
*翻译出错了? 试试 [英文版](readme_en.md#HTTP) 吧~*

- [got](https://github.com/sindresorhus/got) - **star:7330** 更好的内置“http”模块接口 ![star > 2000][Awesome] 
- [gh-got](https://github.com/sindresorhus/gh-got) - **star:150** “got”与github api交互的简单封装
- [axios](https://github.com/mzabriskie/axios) - **star:72336** 基于 Promise 的HTTP客户端(也适用于浏览器) ![star > 2000][Awesome] 
- [wreck](https://github.com/hapijs/wreck) - **star:373** HTTP客户端工具
- [download](https://github.com/kevva/download) - **star:959** 轻松下载和解压文件
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - **star:11086** HTTP代理 ![star > 2000][Awesome] 
- [superagent](https://github.com/visionmedia/superagent) - **star:15031** HTTP请求库 ![star > 2000][Awesome] 
- [node-fetch](https://github.com/bitinn/node-fetch) - **star:4925** node.js 版的 `window.fetch` ![star > 2000][Awesome] 
- [flashheart](https://github.com/bbc/flashheart) - **star:110** REST 客户端
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - **star:226** 通过可配置路由提供JSON文件或JavaScript对象的内容，构建一个伪后端
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - **star:198** 支持符合RFC的缓存的HTTP请求封装
- [gotql](https://github.com/khaosdoctor/gotql) - **star:253** 构建于[got]之上(https://github.com/sindresorhus/got)的GraphQL请求库
- [global-agent](https://github.com/gajus/global-agent) - **star:85** 可使用环境变量配置的全局HTTP/HTTPS代理代理。

### 调试
*翻译出错了? 试试 [英文版](readme_en.md#Debugging%20) 吧~*

- [ndb](https://github.com/GoogleChromeLabs/ndb) - **star:9962** 通过chrome devtools改进了调试体验 ![star > 2000][Awesome] 
- [ironNode](https://github.com/s-a/iron-node) - **star:2368** 开箱即用的js调试器，支持ES2015 ![star > 2000][Awesome] 
- [node-inspector](https://github.com/node-inspector/node-inspector) - **star:12495** 基于Blink开发工具的调试器 ![star > 2000][Awesome] 
- [debug](https://github.com/visionmedia/debug) - **star:8668** 微小的调试工具 ![star > 2000][Awesome] 
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - **star:1075** js正在运行，但你不知道为什么?
- [njsTrace](https://github.com/valyouw/njstrace) - **star:279** 测试并跟踪代码，查看所有函数调用、参数、返回值以及每个函数中花费的时间
- [vstream](https://github.com/joyent/node-vstream) - **star:57** 用于检测管道流
- [stackman](https://github.com/watson/stackman) - **star:220** 使用代码摘要和其他好东西增强错误堆栈跟踪
- [locus](https://github.com/alidavut/locus) - **star:278** 在运行时启动一个可以访问所有变量的REPL
- [0x](https://github.com/davidmarkclements/0x) - **star:1803** 火焰图分析
- [ctrace](https://github.com/automation-stack/ctrace) - **star:109** 用于跟踪系统调用和信号，格式良好并且经过改进
- [leakage](https://github.com/andywer/leakage) - **star:1439** 编写内存泄漏测试
- [llnode](https://github.com/nodejs/llnode) - **star:838** 后期分析工具，允许检查对象，并从崩溃的Node.js进程中获取细节
- [thetool](https://github.com/sfninja/thetool) - **star:153** 以Chrome DevTools的格式为应用程序捕获不同的CPU、内存和其他配置文件
- [swagger-stats](https://github.com/slanatech/swagger-stats) - **star:424** 跟踪API调用并监视API性能、健康状况和使用指标
- [NiM](https://github.com/june07/nim) - **star:154** 管理DevTools调试工作流程。

### 日志
*翻译出错了? 试试 [英文版](readme_en.md#Logging) 吧~*

- [pino](https://github.com/pinojs/pino) - **star:5348** 非常快的日志工具，灵感来自Bunyan ![star > 2000][Awesome] 
- [winston](https://github.com/winstonjs/winston) - **star:15238** 多通道异步日志库 ![star > 2000][Awesome] 
- [console-log-level](https://github.com/watson/console-log-level) - **star:59** 最简单的日志程序，支持日志级别和自定义前缀
- [storyboard](https://github.com/guigrpa/storyboard) - **star:613** 端到端的、分层的、实时的、丰富多彩的日志和故事
- [signale](https://github.com/klauscfhq/signale) - **star:8079** 控制台记录器。 ![star > 2000][Awesome] 
- [consola](https://github.com/nuxt/consola) - **star:2781** 控制台记录器。 ![star > 2000][Awesome] 

### 命令行实用工具
*翻译出错了? 试试 [英文版](readme_en.md#Command-line%20utilities) 吧~*

- [chalk](https://github.com/chalk/chalk) - **star:14331** 终端字符串样式设置 ![star > 2000][Awesome] 
- [meow](https://github.com/sindresorhus/meow) - **star:2147** CLI应用助手 ![star > 2000][Awesome] 
- [yargs](https://github.com/yargs/yargs) - **star:7570** 自动生成优雅用户界面的命令行解析器 ![star > 2000][Awesome] 
- [ora](https://github.com/sindresorhus/ora) - **star:5905** 优雅的终端 spinner ![star > 2000][Awesome] 
- [get-stdin](https://github.com/sindresorhus/get-stdin) - **star:250** 简单的 stdin
- [log-update](https://github.com/sindresorhus/log-update) - **star:776** 通过覆盖终端中的前一个输出来记录日志用于绘制进度条、动画等
- [Ink](https://github.com/vadimdemedes/ink) - **star:13095** 对交互式命令行应用程序作出反应 ![star > 2000][Awesome] 
- [listr](https://github.com/samverschueren/listr) - **star:2476** 终端任务列表 ![star > 2000][Awesome] 
- [conf](https://github.com/sindresorhus/conf) - **star:561** 简单的配置处理应用程序或模块
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - **star:299** 用于操作终端的ANSI转义码
- [log-symbols](https://github.com/sindresorhus/log-symbols) - **star:511** 不同日志级别的彩色符号
- [figures](https://github.com/sindresorhus/figures) - **star:395** 带有Windows CMD回退的Unicode符号
- [boxen](https://github.com/sindresorhus/boxen) - **star:729** 在终端中创建框
- [terminal-link](https://github.com/sindresorhus/terminal-link) - **star:279** 在终端中创建可单击链接
- [terminal-image](https://github.com/sindresorhus/terminal-image) - **star:492** 在终端显示图像
- [string-width](https://github.com/sindresorhus/string-width) - **star:185** 获取字符串的可视宽度——显示它所需的列数
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - **star:52** 在终端中将字符串截断到特定宽度
- [first-run](https://github.com/sindresorhus/first-run) - **star:69** 检查这是否是第一次运行流程
- [blessed](https://github.com/chjj/blessed) - **star:9147** Curses-like 库 ![star > 2000][Awesome] 
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - **star:12351** 交互式命令行提示符 ![star > 2000][Awesome] 
- [yn](https://github.com/sindresorhus/yn) - **star:186** 解析yes/no 类似的值
- [cli-table3](https://github.com/cli-table/cli-table3) - **star:147** 漂亮的unicode表
- [drawille](https://github.com/madbence/node-drawille) - **star:869** 用unicode字符在终端上绘制
- [update-notifier](https://github.com/yeoman/update-notifier) - **star:1389** 更新CLI应用程序的通知
- [ascii-charts](https://github.com/jstrace/chart) - **star:224** 终端中的ASCII条形图
- [progress](https://github.com/tj/node-progress) - **star:2409** 灵活的ascii进度条 ![star > 2000][Awesome] 
- [insight](https://github.com/yeoman/insight) - **star:487** 帮助了解匿名向Google Analytics报告使用指标时如何使用您的工具
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - **star:66** 切换CLI游标
- [columnify](https://github.com/timoxley/columnify) - **star:373** 创建适合控制台输出的基于文本的列，支持单元格包装
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - **star:23** 列式unicode和ansi安全的文本列表
- [cfonts](https://github.com/dominikwilkowski/cfonts) - **star:556** 性感的ASCII字体控制台
- [multispinner](https://github.com/codekirei/node-multispinner) - **star:264** 多个，同时，单独控制的CLI spinners
- [omelette](https://github.com/f/omelette) - **star:921** shell自动完成帮助程序
- [cross-env](https://github.com/kentcdodds/cross-env) - **star:4669** 设置跨平台的环境变量 ![star > 2000][Awesome] 
- [shelljs](https://github.com/shelljs/shelljs) - **star:10940** 可移植的Unix shell命令 ![star > 2000][Awesome] 
- [sudo-block](https://github.com/sindresorhus/sudo-block) - **star:80** 阻止用户使用根权限运行应用程序
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - **star:262** 使用未处理的promise rejections错误代替默认错误
- [sparkly](https://github.com/sindresorhus/sparkly) - **star:350** 生成波形图 “▁▂▃▅▂▇”
- [Bit](https://github.com/teambit/bit) - **star:10762** 跨存储库创建、维护、查找和使用小模块和组件 ![star > 2000][Awesome] 
- [gradient-string](https://github.com/bokub/gradient-string) - **star:411** 终端输出中漂亮的颜色渐变
- [oclif](https://github.com/oclif/oclif) - **star:4801** 包含解析器、自动文档、测试和插件的CLI框架 ![star > 2000][Awesome] 
- [term-size](https://github.com/sindresorhus/term-size) - **star:110** 可靠地获取终端窗口大小
- [Cliffy](https://github.com/drew-y/cliffy) - **star:231** 交互式CLIs框架

### 构建工具
*翻译出错了? 试试 [英文版](readme_en.md#Build%20tools) 吧~*

- [parcel](https://github.com/parcel-bundler/parcel) - **star:35460** 速度极快，零配置web应用程序打包工具 ![star > 2000][Awesome] 
- [webpack](https://github.com/webpack/webpack) - **star:53877** 为浏览器打包模块和资源 ![star > 2000][Awesome] 
- [rollup](https://github.com/rollup/rollup) - **star:18018** 下一代ES2015模块打包工具 ![star > 2000][Awesome] 
- [gulp](https://github.com/gulpjs/gulp) - **star:31717** 流式和快速构建系统，更喜欢代码而不是配置 ![star > 2000][Awesome] 
- [Broccoli](https://github.com/broccolijs/broccoli) - **star:3284** 快速、可靠的资源管道，支持固定时间的重新构建和紧凑的构建定义 ![star > 2000][Awesome] 
- [Brunch](https://github.com/brunch/brunch) - **star:6667** 前端web应用程序构建工具，具有简单的声明性配置、快速增量编译和自定义工作流 ![star > 2000][Awesome] 
- [Start](https://github.com/deepsweet/start) - **star:481** 带有共享预置的功能任务运行器 ![项目已归档][Archived] 
- [ygor](https://github.com/shannonmoeller/ygor) - **star:70** 当“npm运行”是不够的，其他的都太多的时候，有前途的任务运行器
- [FuseBox](https://github.com/fuse-box/fuse-box) - **star:3975** 快速构建系统，结合了webpack、JSPM和SystemJS的强大功能，并提供一流的TypeScript支持 ![star > 2000][Awesome] 
- [pkg](https://github.com/zeit/pkg) - **star:15685** 将Node.js项目打包成可执行文件 ![star > 2000][Awesome] 

### 硬件
*翻译出错了? 试试 [英文版](readme_en.md#Hardware) 吧~*

- [johnny-five](https://github.com/rwaldron/johnny-five) - **star:11428** 基于Firmata的Arduino框架 ![star > 2000][Awesome] 
- [serialport](https://github.com/voodootikigod/node-serialport) - **star:4371** 访问串行端口进行读写 ![star > 2000][Awesome] 
- [usb](https://github.com/nonolith/node-usb) - **star:924** USB接口库
- [i2c-bus](https://github.com/fivdi/i2c-bus) - **star:221** I2C串行总线访问
- [onoff](https://github.com/fivdi/onoff) - **star:933** GPIO访问和中断检测
- [spi-device](https://github.com/fivdi/spi-device) - **star:77** SPI串行总线访问
- [pigpio](https://github.com/fivdi/pigpio) - **star:626** 快速GPIO, PWM，伺服控制，状态变化通知，中断处理对树莓派
- [gps](https://github.com/infusion/GPS.js) - **star:140** 用于处理GPS接收器的NMEA解析器

### 模板
*翻译出错了? 试试 [英文版](readme_en.md#Templating) 吧~*

- [marko](https://github.com/marko-js/marko) - **star:9481** 基于html的模板引擎，它将模板编译到CommonJS模块，并支持流、异步呈现和自定义标记 ![star > 2000][Awesome] 
- [nunjucks](https://github.com/mozilla/nunjucks) - **star:6655** 带有继承、异步控制等功能的模板引擎(受jinja2的启发) ![star > 2000][Awesome] 
- [handlebars.js](https://github.com/wycats/handlebars.js) - **star:15279** Superset of Mustache 模板的超集，添加了强大的功能，如帮助程序和更高级的块 ![star > 2000][Awesome] 
- [EJS](https://github.com/mde/ejs) - **star:4373** 简单的未绑定模板语言 ![star > 2000][Awesome] 
- [Pug](https://github.com/pugjs/pug) - **star:19158** 高性能模板引擎深受Haml的影响 ![star > 2000][Awesome] 

### Web 框架
*翻译出错了? 试试 [英文版](readme_en.md#Web%20frameworks) 吧~*

- [Hapi](https://github.com/hapijs/hapi) - **star:12302** 用于构建应用程序和服务的框架 ![star > 2000][Awesome] 
- [Koa](https://github.com/koajs/koa) - **star:28965** Express背后的团队设计的框架，其目标是为web应用程序和api提供一个更小、更富表现力和更健壮的基础 ![star > 2000][Awesome] 
- [Express](https://github.com/expressjs/express) - **star:48262** Web应用程序框架，为构建单页、多页和混合Web应用程序提供了一组健壮的特性 ![star > 2000][Awesome] 
- [Feathers](https://github.com/feathersjs/feathers) - **star:12364** 基于Express精神构建的微服务框架 ![star > 2000][Awesome] 
- [LoopBack](https://github.com/strongloop/loopback) - **star:13109** 用于创建REST api和轻松连接到后端数据源的强大框架 ![star > 2000][Awesome] 
- [Meteor](https://github.com/meteor/meteor) - **star:41735** 一个超简单的、无处不在的数据库、在线数据、纯javascript web框架*(你可能会喜欢[awesome-meteor](https://github.com/Urigo/awesome-meteor))* ![star > 2000][Awesome] 
- [Restify](https://github.com/restify/node-restify) - **star:9738** 使您能够构建正确的REST web服务 ![star > 2000][Awesome] 
- [ThinkJS](https://github.com/thinkjs/thinkjs) - **star:5103** 框架与ES2015+支持，WebSockets, REST API ![star > 2000][Awesome] 
- [ActionHero](https://github.com/actionhero/actionhero) - **star:2086** 为TCP套接字、WebSockets和HTTP客户机创建可重用和可伸缩api的框架 ![star > 2000][Awesome] 
- [Next.js](https://github.com/zeit/next.js) - **star:47287** 服务器渲染的通用JavaScript web应用程序的最小化框架 ![star > 2000][Awesome] 
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - **star:26660** 服务器渲染的Vue.js应用程序的最小化框架 ![star > 2000][Awesome] 
- [seneca](https://github.com/senecajs/seneca) - **star:3655** 编写微服务的工具包 ![star > 2000][Awesome] 
- [AdonisJs](http://adonisjs.com) - 一个真正的Node.js MVC框架，建立在依赖注入和IoC容器的坚实基础上
- [Hemera](https://github.com/hemerajs/hemera) - **star:735** 使用[NATS](https://nats.io)编写可靠且容错的微服务
- [Micro](https://github.com/zeit/micro) - **star:9237** 带有异步方法的最小化微服务框架 ![star > 2000][Awesome] 
- [Moleculer](https://moleculer.services) - 快速强大的微服务框架
- [Fastify](https://github.com/fastify/fastify) - **star:14177** 高速、地开销的 Web 框架 ![star > 2000][Awesome] 
- [Nest](https://github.com/nestjs/nest) - **star:26254** 用于构建高效且可伸缩的服务器端应用程序, 受 Angular 启发 ![star > 2000][Awesome] 
- [Zeronode](https://github.com/sfast/zeronode) - **star:106** 可靠和容错的微服务的最小构建块
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - **star:4228** 基于 TypeScript 使用类和装饰器创建 GraphQL api的现代框架 ![star > 2000][Awesome] 

### 文档
*翻译出错了? 试试 [英文版](readme_en.md#Documentation) 吧~*

- [documentation.js](https://github.com/documentationjs/documentation) - **star:5028** 支持ES2015+和 flow 注释的 API 文档生成器 ![star > 2000][Awesome] 
- [ESDoc](https://github.com/esdoc/esdoc) - **star:2580** 以ES2015为目标的文档生成器，附加测试代码并测量文档覆盖率 ![star > 2000][Awesome] 
- [Docco](https://github.com/jashkenas/docco) - **star:3424** 文档生成器，它生成HTML文档，显示与代码混合的注释 ![star > 2000][Awesome] 
- [JSDoc](https://github.com/jsdoc3/jsdoc) - **star:10560** 类似JavaDoc或PHPDoc的API文档生成器 ![star > 2000][Awesome] 
