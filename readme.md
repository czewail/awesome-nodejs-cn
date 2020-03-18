**此项目是 [awesome-nodejs](https://raw.githubusercontent.com/sindresorhus/awesome-nodejs/master/readme.md) 中文版，每天定时同步（上次同步时间：2020-03-18 12:06:55）**

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

- [webtorrent](https://github.com/feross/webtorrent) - 可在 Node.js 和浏览器使用的流式 Torrent 客户端
- [peerflix](https://github.com/mafintosh/peerflix) - 流式 Torrent 客户端
- [dat](https://github.com/datproject/dat-node) - 数据集的实时复制和版本控制
- [ipfs](https://github.com/ipfs/js-ipfs) - 分布式文件系统，用于将所有计算设备与同一文件系统连接起来
- [stackgl](https://github.com/stackgl) - 基于 browserify 和 npm 的 WebGL 开放软件生态系统
- [peerwiki](https://github.com/mafintosh/peerwiki) - 建立在在 BitTorrent 上的维基百科
- [peercast](https://github.com/mafintosh/peercast) - 将种子视频流式传输到 Chromecast
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - 干净、可读比特币库
- [Bitcore](https://github.com/bitpay/bitcore) - 纯净、强大的比特币库
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF 生成库
- [turf](https://github.com/Turfjs/turf) - 模块化地理空间处理和分析引擎
- [webcat](https://github.com/mafintosh/webcat) - 使用 WebRTC 跨 web 的 p2p 管道，它使用 GitHub 私有/公共密钥进行身份验证
- [NodeOS](https://github.com/NodeOS/NodeOS) - 第一个由 npm 驱动的操作系统
- [YodaOS](https://github.com/yodaos-project/yodaos) - 人工智能操作系统
- [Brain.js](https://github.com/BrainJS/brain.js) - 机器学习框架
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - 图论(又称网络)建模与分析
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia 分布式哈希表
- [seedshot](https://github.com/twobucks/seedshot) - 从浏览器共享临时 P2P 截图
- [js-git](https://github.com/creationix/js-git) - Git的 JavaScript 实现
- [skale](https://github.com/skale-me/skale-engine) - 高性能分布式数据处理引擎
- [xlsx](https://github.com/sheetjs/js-xlsx) - 纯 js 实现的 Excel 电子表格读写器
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - 纯 JavaScript 实现的 Git

### 命令行程序
*翻译出错了? 试试 [英文版](readme_en.md#Command-line%20apps) 吧~*

- [np](https://github.com/sindresorhus/np) - 更好的 'npm publish'
- [npm-name](https://github.com/sindresorhus/npm-name) - 检查 npm 上的包名是否可用
- [gh-home](https://github.com/sindresorhus/gh-home) - 在当前目录中打开 GitHub 的仓库页面
- [npm-home](https://github.com/sindresorhus/npm-home) - 打开 npm 包的页面
- [trash](https://github.com/sindresorhus/trash) - 更安全的 rm 命令替代品
- [speed-test](https://github.com/sindresorhus/speed-test) - 测试互联网连接速度和 ping
- [emoj](https://github.com/sindresorhus/emoj) - 从命令行文本中找到相关的表情符号
- [pageres](https://github.com/sindresorhus/pageres) - 捕获网站截图
- [cpy](https://github.com/sindresorhus/cpy) - 复制文件
- [vtop](https://github.com/MrRio/vtop) - 带图表的 top 命令
- [empty-trash](https://github.com/sindresorhus/empty-trash) - 清理垃圾
- [is-up](https://github.com/sindresorhus/is-up) - 检查网站是否正常
- [is-online](https://github.com/sindresorhus/is-online) - 检查网络连接是否正常
- [public-ip](https://github.com/sindresorhus/public-ip) - 获取你的公共IP地址
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 在终端上复制粘贴
- [XO](https://github.com/xojs/xo) - 使用 Javascript happiness style 进行严格编码
- [Standard](https://github.com/feross/standard) - Javascript 标准风格 - 一种风格规范
- [ESLint](https://github.com/eslint/eslint) - JavaScript 的可插入 linting 实用程序
- [dev-time](https://github.com/samverschueren/dev-time-cli) - 获取 GitHub 用户当前的本地时间
- [David](https://github.com/alanshaw/david) - 告诉你包的 npm 依赖项何时过期
- [http-server](https://github.com/indexzero/http-server) - 简单的零配置 http 服务器命令行工具
- [Live Server](https://github.com/tapio/live-server) - 具有热重载功能的 HTTP-server
- [bcat](https://github.com/kessler/node-bcat) - 管道命令输出到 web 浏览器
- [normit](https://github.com/pawurb/normit) - 谷歌翻译与语音合成的终端工具
- [fkill](https://github.com/sindresorhus/fkill-cli) - 跨平台的进程杀死工具
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript从终端快速筛选、映射和缩减
- [license-checker](https://github.com/davglass/license-checker) - 检查应用程序依赖项的许可
- [browser-run](https://github.com/juliangruber/browser-run) - 在浏览器环境中轻松运行代码
- [tmpin](https://github.com/sindresorhus/tmpin) - 将stdin支持添加到任何接受文件输入的CLI应用程序
- [wifi-password](https://github.com/kevva/wifi-password-cli) - 获取当前wifi密码
- [wallpaper](https://github.com/sindresorhus/wallpaper) - 更换桌面壁纸
- [brightness](https://github.com/kevva/brightness-cli) - 改变屏幕亮度
- [torrent](https://github.com/maxogden/torrent) - 下载种子
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - 关闭所有Chrome选项卡，以提高性能，减少电池使用，并节省内存
- [alex](https://github.com/wooorm/alex) - 捕获不敏感、不体谅他人的编写
- [pen](https://github.com/noraesae/pen) - 从喜爱的编辑器在浏览器中实时预览 Markdown
- [subdownloader](https://github.com/beatfreaker/subdownloader) - 电影和电视剧的字幕下载程序
- [dark-mode](https://github.com/sindresorhus/dark-mode) - 切换 macOS 黑暗模式
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP 定位程序
- [Jsome](https://github.com/Javascipt/Jsome) - 漂亮的打印json，带有可配置的颜色和缩进
- [itunes-remote](https://github.com/mischah/itunes-remote) - 可交互的方式控制 iTunes
- [mobicon](https://github.com/samverschueren/mobicon-cli) - 移动应用图标生成器
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - 移动应用程序启动屏幕生成器
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - 相当不错的 git diff 到 HTML 的生成器
- [Cash](https://github.com/dthree/cash) - 纯JavaScript中的跨平台Unix shell命令
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - 在终端试用npm包
- [jscpd](https://github.com/kucherenko/jscpd) - 源代码的复制/粘贴检测器
- [atmo](https://github.com/Raathigesh/Atmo) - 服务器端 api 模拟工具
- [auto-install](https://github.com/siddharthkp/auto-install) - 在编写代码时自动安装依赖项
- [lessmd](https://github.com/linuxenko/lessmd) - 终端使用的 Markdown
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - 找出哪些依赖在拖慢速度
- [localtunnel](https://github.com/localtunnel/localtunnel) - 向外界公开本地主机
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - 通过 SVG 共享终端会话
- [gtop](https://github.com/aksakalli/gtop) - 终端系统监控仪表板
- [themer](https://github.com/mjswensen/themer) - 为编辑器、终端、墙纸、Slack等生成主题
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 一款生成代码展示图片的终端工具
- [cash-cli](https://github.com/xxczaki/cash-cli) - 转换170种货币
- [taskbook](https://github.com/klauscfhq/taskbook) - 命令行栖息地的任务、板子和注释
- [discharge](https://github.com/brandonweiss/discharge) - 轻松地将静态站点部署到Amazon S3
- [npkill](https://github.com/voidcosmos/npkill) - 轻松找到并删除旧的和沉重的node_modules文件夹

### 函数式编程
*翻译出错了? 试试 [英文版](readme_en.md#Functional%20programming) 吧~*

- [lodash](https://github.com/lodash/lodash) - 提供一致性、自定义、性能和附加功能的实用程序库一个更好更快的Underscore.js
- [immutable](https://github.com/facebook/immutable-js) - 不可变数据集合
- [Ramda](https://github.com/ramda/ramda) - 实用工具库，侧重于灵活的功能组合，通过自动套用和反转参数顺序启用避免变异数据
- [Folktale](https://github.com/origamitower/folktale) - 用JavaScript编写通用函数式编程的库套件，允许编写优雅的模块化应用程序，减少bug，提高重用性
- [Mout](https://github.com/mout/mout) - 实用工具库与其他现有解决方案最大的区别在于，您可以选择只加载您需要的模块/函数，而不需要额外的开销
- [Bacon.js](https://github.com/baconjs/bacon.js) - 响应式函数编程
- [RxJS](https://github.com/reactivex/rxjs) - 用于转换、组合和查询各种数据的响应式函数编程库
- [Lazy.js](https://github.com/dtao/lazy.js) - 类似于 lodash/Underscore 的工具库，但具有延迟计算，这在许多情况下可以转化为优越的性能
- [Kefir.js](https://github.com/kefirjs/kefir) - 响应式，专注于高性能和低内存使用

### HTTP
*翻译出错了? 试试 [英文版](readme_en.md#HTTP) 吧~*

- [got](https://github.com/sindresorhus/got) - 更好的内置“http”模块接口
- [gh-got](https://github.com/sindresorhus/gh-got) - “got”与github api交互的简单封装
- [axios](https://github.com/mzabriskie/axios) - 基于 Promise 的HTTP客户端(也适用于浏览器)
- [wreck](https://github.com/hapijs/wreck) - HTTP客户端工具
- [download](https://github.com/kevva/download) - 轻松下载和解压文件
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理
- [superagent](https://github.com/visionmedia/superagent) - HTTP请求库
- [node-fetch](https://github.com/bitinn/node-fetch) - node.js 版的 `window.fetch`
- [flashheart](https://github.com/bbc/flashheart) - REST 客户端
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置路由提供JSON文件或JavaScript对象的内容，构建一个伪后端
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - 支持符合RFC的缓存的HTTP请求封装
- [gotql](https://github.com/khaosdoctor/gotql) - 构建于[got]之上(https://github.com/sindresorhus/got)的GraphQL请求库
- [global-agent](https://github.com/gajus/global-agent) - 可使用环境变量配置的全局HTTP/HTTPS代理代理。

### 调试
*翻译出错了? 试试 [英文版](readme_en.md#Debugging%20) 吧~*

- [ndb](https://github.com/GoogleChromeLabs/ndb) - 通过chrome devtools改进了调试体验
- [ironNode](https://github.com/s-a/iron-node) - 开箱即用的js调试器，支持ES2015
- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink开发工具的调试器
- [debug](https://github.com/visionmedia/debug) - 微小的调试工具
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - js正在运行，但你不知道为什么?
- [njsTrace](https://github.com/valyouw/njstrace) - 测试并跟踪代码，查看所有函数调用、参数、返回值以及每个函数中花费的时间
- [vstream](https://github.com/joyent/node-vstream) - 用于检测管道流
- [stackman](https://github.com/watson/stackman) - 使用代码摘要和其他好东西增强错误堆栈跟踪
- [locus](https://github.com/alidavut/locus) - 在运行时启动一个可以访问所有变量的REPL
- [0x](https://github.com/davidmarkclements/0x) - 火焰图分析
- [ctrace](https://github.com/automation-stack/ctrace) - 用于跟踪系统调用和信号，格式良好并且经过改进
- [leakage](https://github.com/andywer/leakage) - 编写内存泄漏测试
- [llnode](https://github.com/nodejs/llnode) - 后期分析工具，允许检查对象，并从崩溃的Node.js进程中获取细节
- [thetool](https://github.com/sfninja/thetool) - 以Chrome DevTools的格式为应用程序捕获不同的CPU、内存和其他配置文件
- [swagger-stats](https://github.com/slanatech/swagger-stats) - 跟踪API调用并监视API性能、健康状况和使用指标
- [NiM](https://github.com/june07/nim) - 管理DevTools调试工作流程。

### 日志
*翻译出错了? 试试 [英文版](readme_en.md#Logging) 吧~*

- [pino](https://github.com/pinojs/pino) - 非常快的日志工具，灵感来自Bunyan
- [winston](https://github.com/winstonjs/winston) - 多通道异步日志库
- [console-log-level](https://github.com/watson/console-log-level) - 最简单的日志程序，支持日志级别和自定义前缀
- [storyboard](https://github.com/guigrpa/storyboard) - 端到端的、分层的、实时的、丰富多彩的日志和故事
- [signale](https://github.com/klauscfhq/signale) - 控制台记录器。
- [consola](https://github.com/nuxt/consola) - 控制台记录器。

### 命令行实用工具
*翻译出错了? 试试 [英文版](readme_en.md#Command-line%20utilities) 吧~*

- [chalk](https://github.com/chalk/chalk) - 终端字符串样式设置
- [meow](https://github.com/sindresorhus/meow) - CLI应用助手
- [yargs](https://github.com/yargs/yargs) - 自动生成优雅用户界面的命令行解析器
- [ora](https://github.com/sindresorhus/ora) - 优雅的终端 spinner
- [get-stdin](https://github.com/sindresorhus/get-stdin) - 简单的 stdin
- [log-update](https://github.com/sindresorhus/log-update) - 通过覆盖终端中的前一个输出来记录日志用于绘制进度条、动画等
- [Ink](https://github.com/vadimdemedes/ink) - 对交互式命令行应用程序作出反应
- [listr](https://github.com/samverschueren/listr) - 终端任务列表
- [conf](https://github.com/sindresorhus/conf) - 简单的配置处理应用程序或模块
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - 用于操作终端的ANSI转义码
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 不同日志级别的彩色符号
- [figures](https://github.com/sindresorhus/figures) - 带有Windows CMD回退的Unicode符号
- [boxen](https://github.com/sindresorhus/boxen) - 在终端中创建框
- [terminal-link](https://github.com/sindresorhus/terminal-link) - 在终端中创建可单击链接
- [terminal-image](https://github.com/sindresorhus/terminal-image) - 在终端显示图像
- [string-width](https://github.com/sindresorhus/string-width) - 获取字符串的可视宽度——显示它所需的列数
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - 在终端中将字符串截断到特定宽度
- [first-run](https://github.com/sindresorhus/first-run) - 检查这是否是第一次运行流程
- [blessed](https://github.com/chjj/blessed) - Curses-like 库
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 交互式命令行提示符
- [yn](https://github.com/sindresorhus/yn) - 解析yes/no 类似的值
- [cli-table3](https://github.com/cli-table/cli-table3) - 漂亮的unicode表
- [drawille](https://github.com/madbence/node-drawille) - 用unicode字符在终端上绘制
- [update-notifier](https://github.com/yeoman/update-notifier) - 更新CLI应用程序的通知
- [ascii-charts](https://github.com/jstrace/chart) - 终端中的ASCII条形图
- [progress](https://github.com/tj/node-progress) - 灵活的ascii进度条
- [insight](https://github.com/yeoman/insight) - 帮助了解匿名向Google Analytics报告使用指标时如何使用您的工具
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - 切换CLI游标
- [columnify](https://github.com/timoxley/columnify) - 创建适合控制台输出的基于文本的列，支持单元格包装
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - 列式unicode和ansi安全的文本列表
- [cfonts](https://github.com/dominikwilkowski/cfonts) - 性感的ASCII字体控制台
- [multispinner](https://github.com/codekirei/node-multispinner) - 多个，同时，单独控制的CLI spinners
- [omelette](https://github.com/f/omelette) - shell自动完成帮助程序
- [cross-env](https://github.com/kentcdodds/cross-env) - 设置跨平台的环境变量
- [shelljs](https://github.com/shelljs/shelljs) - 可移植的Unix shell命令
- [sudo-block](https://github.com/sindresorhus/sudo-block) - 阻止用户使用根权限运行应用程序
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - 使用未处理的promise rejections错误代替默认错误
- [sparkly](https://github.com/sindresorhus/sparkly) - 生成波形图 “▁▂▃▅▂▇”
- [Bit](https://github.com/teambit/bit) - 跨存储库创建、维护、查找和使用小模块和组件
- [gradient-string](https://github.com/bokub/gradient-string) - 终端输出中漂亮的颜色渐变
- [oclif](https://github.com/oclif/oclif) - 包含解析器、自动文档、测试和插件的CLI框架
- [term-size](https://github.com/sindresorhus/term-size) - 可靠地获取终端窗口大小
- [Cliffy](https://github.com/drew-y/cliffy) - 交互式CLIs框架

### 构建工具
*翻译出错了? 试试 [英文版](readme_en.md#Build%20tools) 吧~*

- [parcel](https://github.com/parcel-bundler/parcel) - 速度极快，零配置web应用程序打包工具
- [webpack](https://github.com/webpack/webpack) - 为浏览器打包模块和资源
- [rollup](https://github.com/rollup/rollup) - 下一代ES2015模块打包工具
- [gulp](https://github.com/gulpjs/gulp) - 流式和快速构建系统，更喜欢代码而不是配置
- [Broccoli](https://github.com/broccolijs/broccoli) - 快速、可靠的资源管道，支持固定时间的重新构建和紧凑的构建定义
- [Brunch](https://github.com/brunch/brunch) - 前端web应用程序构建工具，具有简单的声明性配置、快速增量编译和自定义工作流
- [Start](https://github.com/deepsweet/start) - 带有共享预置的功能任务运行器
- [ygor](https://github.com/shannonmoeller/ygor) - 当“npm运行”是不够的，其他的都太多的时候，有前途的任务运行器
- [FuseBox](https://github.com/fuse-box/fuse-box) - 快速构建系统，结合了webpack、JSPM和SystemJS的强大功能，并提供一流的TypeScript支持
- [pkg](https://github.com/zeit/pkg) - 将Node.js项目打包成可执行文件

### 硬件
*翻译出错了? 试试 [英文版](readme_en.md#Hardware) 吧~*

- [johnny-five](https://github.com/rwaldron/johnny-five) - 基于Firmata的Arduino框架
- [serialport](https://github.com/voodootikigod/node-serialport) - 访问串行端口进行读写
- [usb](https://github.com/nonolith/node-usb) - USB接口库
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C串行总线访问
- [onoff](https://github.com/fivdi/onoff) - GPIO访问和中断检测
- [spi-device](https://github.com/fivdi/spi-device) - SPI串行总线访问
- [pigpio](https://github.com/fivdi/pigpio) - 快速GPIO, PWM，伺服控制，状态变化通知，中断处理对树莓派
- [gps](https://github.com/infusion/GPS.js) - 用于处理GPS接收器的NMEA解析器

### 模板
*翻译出错了? 试试 [英文版](readme_en.md#Templating) 吧~*

- [marko](https://github.com/marko-js/marko) - 基于html的模板引擎，它将模板编译到CommonJS模块，并支持流、异步呈现和自定义标记
- [nunjucks](https://github.com/mozilla/nunjucks) - 带有继承、异步控制等功能的模板引擎(受jinja2的启发)
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache 模板的超集，添加了强大的功能，如帮助程序和更高级的块
- [EJS](https://github.com/mde/ejs) - 简单的未绑定模板语言
- [Pug](https://github.com/pugjs/pug) - 高性能模板引擎深受Haml的影响

### Web 框架
*翻译出错了? 试试 [英文版](readme_en.md#Web%20frameworks) 吧~*

- [Hapi](https://github.com/hapijs/hapi) - 用于构建应用程序和服务的框架
- [Koa](https://github.com/koajs/koa) - Express背后的团队设计的框架，其目标是为web应用程序和api提供一个更小、更富表现力和更健壮的基础
- [Express](https://github.com/expressjs/express) - Web应用程序框架，为构建单页、多页和混合Web应用程序提供了一组健壮的特性
- [Feathers](https://github.com/feathersjs/feathers) - 基于Express精神构建的微服务框架
- [LoopBack](https://github.com/strongloop/loopback) - 用于创建REST api和轻松连接到后端数据源的强大框架
- [Meteor](https://github.com/meteor/meteor) - 一个超简单的、无处不在的数据库、在线数据、纯javascript web框架*(你可能会喜欢[awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](https://github.com/restify/node-restify) - 使您能够构建正确的REST web服务
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 框架与ES2015+支持，WebSockets, REST API
- [ActionHero](https://github.com/actionhero/actionhero) - 为TCP套接字、WebSockets和HTTP客户机创建可重用和可伸缩api的框架
- [Next.js](https://github.com/zeit/next.js) - 服务器渲染的通用JavaScript web应用程序的最小化框架
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - 服务器渲染的Vue.js应用程序的最小化框架
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包
- [AdonisJs](http://adonisjs.com) - 一个真正的Node.js MVC框架，建立在依赖注入和IoC容器的坚实基础上
- [Hemera](https://github.com/hemerajs/hemera) - 使用[NATS](https://nats.io)编写可靠且容错的微服务
- [Micro](https://github.com/zeit/micro) - 带有异步方法的最小化微服务框架
- [Moleculer](https://moleculer.services) - 快速强大的微服务框架
- [Fastify](https://github.com/fastify/fastify) - 高速、地开销的 Web 框架
- [Nest](https://github.com/nestjs/nest) - 用于构建高效且可伸缩的服务器端应用程序, 受 Angular 启发
- [Zeronode](https://github.com/sfast/zeronode) - 可靠和容错的微服务的最小构建块
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - 基于 TypeScript 使用类和装饰器创建 GraphQL api的现代框架

### 文档
*翻译出错了? 试试 [英文版](readme_en.md#Documentation) 吧~*

- [documentation.js](https://github.com/documentationjs/documentation) - 支持ES2015+和 flow 注释的 API 文档生成器
- [ESDoc](https://github.com/esdoc/esdoc) - 以ES2015为目标的文档生成器，附加测试代码并测量文档覆盖率
- [Docco](https://github.com/jashkenas/docco) - 文档生成器，它生成HTML文档，显示与代码混合的注释
- [JSDoc](https://github.com/jsdoc3/jsdoc) - 类似JavaDoc或PHPDoc的API文档生成器

### 文件系统
*翻译出错了? 试试 [英文版](readme_en.md#Filesystem) 吧~*

- [del](https://github.com/sindresorhus/del) - 使用全局变量删除文件/文件夹
- [globby](https://github.com/sindresorhus/globby) - 支持多种模式的Glob文件
- [cpy](https://github.com/sindresorhus/cpy) - 复制文件
- [rimraf](https://github.com/isaacs/rimraf) - 递归删除文件，如' rm -rf '
- [make-dir](https://github.com/sindresorhus/make-dir) - 递归地创建像' mkdir -p '这样的目录
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - 以各种改进替代' fs '模块
- [chokidar](https://github.com/paulmillr/chokidar) - 文件系统监视程序，它稳定来自' fs的事件看”和“fs以及在macOS上使用本地的“fsevents”
- [find-up](https://github.com/sindresorhus/find-up) - 通过遍历父目录找到一个文件
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - 进程间和机器间的锁文件实用程序
- [load-json-file](https://github.com/sindresorhus/load-json-file) - 读取和解析JSON文件
- [write-json-file](https://github.com/sindresorhus/write-json-file) - 将JSON原子化并写入文件
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - 比如' fs.createWriteStream() '，但是原子的
- [filenamify](https://github.com/sindresorhus/filenamify) - 将字符串转换为有效的文件名
- [lnfs](https://github.com/kevva/lnfs) - 强制创建符号链接，如' ln -fs '
- [istextorbinary](https://github.com/bevry/istextorbinary) - 检查文件是文本还是二进制文件
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - 完全重新设计的文件系统API，方便在日常使用
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - ' fs '模块的额外方法
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - 查找npm包的根目录
- [filehound](https://github.com/nspragg/filehound) - 灵活流畅的文件系统搜索界面
- [move-file](https://github.com/sindresorhus/move-file) - 移动文件，甚至可以跨设备工作
- [tempy](https://github.com/sindresorhus/tempy) - 获取随机临时文件或目录路径

### 控制流
*翻译出错了? 试试 [英文版](readme_en.md#Control%20flow) 吧~*

- Promises
- [Bluebird](https://github.com/petkaantonov/bluebird) - 承诺库专注于创新功能和性能
- [pify](https://github.com/sindresorhus/pify) - 承诺一个回调样式的函数
- [delay](https://github.com/sindresorhus/delay) - 将承诺延迟一定的时间
- [promise-memoize](https://github.com/nodeca/promise-memoize) - 使用过期和预取来记忆承诺返回函数
- [valvelet](https://github.com/lpinca/valvelet) - 限制承诺返回函数的执行速度
- [p-map](https://github.com/sindresorhus/p-map) - 同时映射承诺
	- [More…](https://github.com/sindresorhus/promise-fun)
- Observables
- [zen-observable](https://github.com/zenparsing/zen-observable) - 可见的实现
- [RxJS](https://github.com/ReactiveX/RxJS) - 反应性编程
- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - 将可观察到的转化为承诺
	- [More…](https://github.com/sindresorhus/awesome-observables)
- Streams
- [Highland.js](https://github.com/caolan/highland) - 使用标准JavaScript和类似节点的流，轻松管理同步和异步代码
- Callbacks
- [each-async](https://github.com/sindresorhus/each-async) - 异步并发迭代器，如forEach
- [async](https://github.com/caolan/async) - 为处理异步性提供了直接、强大的函数
- Channels
- [js-csp](https://github.com/ubolonton/js-csp) - 为JavaScript通信顺序进程(如Clojurescript core)异步,或者去)

### 流
*翻译出错了? 试试 [英文版](readme_en.md#Streams) 吧~*

- [through2](https://github.com/rvagg/through2) - streams2转换周围的小包装器，以避免显式子类化噪声
- [from2](https://github.com/hughsk/from2) - ReadableStream的方便包装器，灵感来自“through2”
- [get-stream](https://github.com/sindresorhus/get-stream) - 获取一个流作为字符串或缓冲区
- [into-stream](https://github.com/sindresorhus/into-stream) - 将缓冲区/字符串/数组/对象转换为流
- [duplexify](https://github.com/mafintosh/duplexify) - 将可写和可读的流转换为单个流s2双工流
- [pumpify](https://github.com/mafintosh/pumpify) - 将一个流数组组合成一个双工流
- [peek-stream](https://github.com/mafintosh/peek-stream) - 转换流，它允许您在决定如何解析第一行之前先查看第一行
- [binary-split](https://github.com/maxogden/binary-split) - 换行(或任何分隔符)拆分器流
- [byline](https://github.com/jahewson/node-byline) - 超简单的逐行流阅读器
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - 转换流中的第一个块
- [pad-stream](https://github.com/sindresorhus/pad-stream) - 将每一行填充到一个流中
- [multistream](https://github.com/feross/multistream) - 将多个流合并到一个流中
- [stream-combiner2](https://github.com/substack/stream-combiner2) - 将管道转换为单个流
- [readable-stream](https://github.com/nodejs/readable-stream) - 核心中Streams2和Streams3实现的镜像
- [through2-concurrent](https://github.com/almost/through2-concurrent) - 同时转换对象流

### 实时
*翻译出错了? 试试 [英文版](readme_en.md#Real-time) 吧~*

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - 高度可伸缩的WebSocket服务器和客户端库
- [Socket.io](https://github.com/socketio/socket.io) - 支持实时双向基于事件的通信
- [Faye](https://github.com/faye/faye) - 实时客户端-服务器消息总线，基于Bayeux协议
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - 可伸缩的HTTP + WebSocket引擎，可以运行在多个CPU核心
- [Primus](https://github.com/primus/primus) - 实时框架的抽象层，以防止模块锁定
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - 可伸缩的实时微服务框架
- [Kalm](https://github.com/kalm/kalm.js) - 底层套接字路由器和中间件框架
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - 基于MQTT的消息传递协议的客户机，用于TCP/IP之上
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 通过WebSockets实现JSON-RPC 2.0
- [Aedes](https://github.com/mcollina/aedes) - 可以在任何流服务器上运行的Barebone MQTT服务器

### 图像
*翻译出错了? 试试 [英文版](readme_en.md#Image) 吧~*

- [sharp](https://github.com/lovell/sharp) - 用于调整JPEG、PNG、WebP和TIFF图像大小的最快模块
- [image-type](https://github.com/sindresorhus/image-type) - 检测缓冲区/ uint8数组的图像类型
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick和ImageMagick包装器
- [lwip](https://github.com/EyalAr/lwip) - 轻量级图像处理器，不需要ImageMagick
- [pica](https://github.com/nodeca/pica) - 高品质和快速调整大小(lanczos3)在纯JS替代画布drawImage()，当不允许像素化时
- [jimp](https://github.com/oliver-moran/jimp) - 图像处理在纯JavaScript
- [probe-image-size](https://github.com/nodeca/probe-image-size) - 获得大多数图像格式的大小，而不完全下载
- [qrcode](https://github.com/soldair/node-qrcode) - 二维码和条形码发生器

### 文本
*翻译出错了? 试试 [英文版](readme_en.md#Text) 吧~*

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码
- [string-length](https://github.com/sindresorhus/string-length) - 通过正确计算星体符号和忽略ansi转义码来获得字符串的实际长度
- [camelcase](https://github.com/sindresorhus/camelcase) - 将以破折号/点/下划线/空格分隔的字符串转换为camelCase: foo-bar→fooBar
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义RegExp特殊字符
- [execall](https://github.com/sindresorhus/execall) - 在一个字符串中查找多个RegExp匹配项
- [splice-string](https://github.com/sindresorhus/splice-string) - 删除或替换字符串的一部分，如' Array#splice '
- [indent-string](https://github.com/sindresorhus/indent-string) - 缩进字符串中的每一行
- [strip-indent](https://github.com/sindresorhus/strip-indent) - 从字符串中的每一行中去除前导空格
- [detect-indent](https://github.com/sindresorhus/detect-indent) - 检测代码的缩进
- [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器
- [i18n-node](https://github.com/mashpie/i18n-node) - 简单的翻译模块与动态JSON存储
- [babelfish](https://github.com/nodeca/babelfish) - i18n非常简单的复数语法
- [matcher](https://github.com/sindresorhus/matcher) - 简单的通配符匹配
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 在视觉上规范化相似的unicode字符
- [i18next](https://github.com/i18next/i18next) - 国际化框架
- [nanoid](https://github.com/ai/nanoid) - 微小，安全，url友好，唯一的字符串ID生成器

### 数量
*翻译出错了? 试试 [英文版](readme_en.md#Number) 吧~*

- [random-int](https://github.com/sindresorhus/random-int) - 生成一个随机整数
- [random-float](https://github.com/sindresorhus/random-float) - 生成一个随机浮点数
- [unique-random](https://github.com/sindresorhus/unique-random) - 生成连续惟一的随机数
- [round-to](https://github.com/sindresorhus/round-to) - 将一个数字四舍五入到一个特定的小数位数:' 1.234 '→' 1.2 '

### 数学
*翻译出错了? 试试 [英文版](readme_en.md#Math) 吧~*

- [ndarray](https://github.com/scijs/ndarray) - 多维数组
- [mathjs](https://github.com/josdejong/mathjs) - 一个广泛的数学图书馆
- [math-clamp](https://github.com/sindresorhus/math-clamp) - 夹一个数字
- [algebra](https://github.com/fibo/algebra) - 代数结构
- [multimath](https://github.com/nodeca/multimath) - 核心创建快速图像数学在WebAssembly和JS

### 日期
*翻译出错了? 试试 [英文版](readme_en.md#Date) 吧~*

- [Luxon](https://github.com/moment/luxon) - 用于处理日期和时间的库
- [date-fns](https://github.com/date-fns/date-fns) - 现代实用程序
- [Moment.js](http://momentjs.com) - 解析、验证、操作和显示日期
- [Day.js](https://github.com/iamkun/dayjs) - 不可变日期库替代Moment.js
- [dateformat](https://github.com/felixge/node-dateformat) - 日期格式
- [tz-format](https://github.com/samverschueren/tz-format) - 使用时区设置日期:“2015-11-30T10:40:35+01:00”
- [cctz](https://github.com/floatdrop/node-cctz) - 用于日期的快速解析、格式化和时区对话

### URL
*翻译出错了? 试试 [英文版](readme_en.md#URL) 吧~*

- [normalize-url](https://github.com/sindresorhus/normalize-url) - 正常一个URL
- [humanize-url](https://github.com/sindresorhus/humanize-url) - 将URL人性化:http://sindresorhus.com→sindresorhus.com
- [url-unshort](https://github.com/nodeca/url-unshort) - 扩大缩短url
- [speakingurl](https://github.com/pid/speakingurl) - 从具有音译的字符串生成段塞
- [linkify-it](https://github.com/markdown-it/linkify-it) - 链接模式检测器与完整的unicode支持
- [url-pattern](https://github.com/snd/url-pattern) - 比正则表达式字符串更容易匹配url和其他字符串的模式
- [embedza](https://github.com/nodeca/embedza) - 使用来自oEmbed, Open Graph, meta标签的信息从url创建HTML片段/嵌入

### 数据验证
*翻译出错了? 试试 [英文版](readme_en.md#Data%20validation) 吧~*

- [joi](https://github.com/hapijs/joi) - 对象模式描述语言和JavaScript对象的验证器
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 使用代码生成的JSON模式验证器非常快
- [property-validator](https://github.com/nettofarah/property-validator) - 方便快捷的属性验证
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API的清理和验证
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON模式验证器支持v5、v6和v7提案

### 解析
*翻译出错了? 试试 [英文版](readme_en.md#Parsing) 吧~*

- [remark](https://github.com/wooorm/remark) - 插件驱动的降价处理器
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown解析器具有100%的公共标记支持、扩展和语法插件
- [parse5](https://github.com/inikulin/parse5) - 快速功能齐全的符合规范的HTML解析器
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - 从JSON中删除注释
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - 去掉CSS中的注释
- [parse-json](https://github.com/sindresorhus/parse-json) - 解析带有更多有用错误的JSON
- [URI.js](https://github.com/medialize/URI.js) - URL突变
- [PostCSS](https://github.com/postcss/postcss) - CSS解析器/ stringifier
- [JSONStream](https://github.com/dominictarr/JSONStream) - 流JSON解析函数,把
- [neat-csv](https://github.com/sindresorhus/neat-csv) - 快CSV解析器上面的回调接口
- [csv-parser](https://github.com/mafintosh/csv-parser) - 流CSV解析器，旨在比其他人更快
- [PEG.js](https://github.com/pegjs/pegjs) - 简单的解析器生成器，生成具有出色错误报告的快速解析器
- [x-ray](https://github.com/lapwinglabs/x-ray) - 网页抓取工具
- [nearley](https://github.com/Hardmath123/nearley) - 简单、快速、强大的JavaScript解析
- [binary-extract](https://github.com/juliangruber/binary-extract) - 从JSON缓冲区中提取一个值，而不需要解析整个内容
- [Stylecow](https://github.com/stylecow/stylecow) - 解析、操作和转换现代CSS，使其与所有浏览器兼容可扩展的插件
- [js-yaml](https://github.com/nodeca/js-yaml) - 非常快的YAML解析器
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML到JavaScript对象转换器
- [Jison](https://github.com/zaach/jison) - 友好的JavaScript解析器生成器它与野牛、Yacc和家族有共同的基因
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - 解析、格式化、存储和验证电话号码
- [ref](https://github.com/TooTallNate/ref) - 读取/写入缓冲区中的结构化二进制数据
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - 读/写Excel XLSX
- [Chevrotain](https://github.com/SAP/chevrotain) - 非常快，功能丰富的JavaScript解析器构建工具包
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 验证和解析XML

### 人性化
*翻译出错了? 试试 [英文版](readme_en.md#Humanize) 吧~*

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - 将字节转换为人类可读的字符串:' 1337 '→' 1.34 kB '
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - 将毫秒转换为人类可读的字符串:“1337000000”→“15d 11h 23m 20s”
- [ms](https://github.com/rauchg/ms.js) - 微小的毫秒转换实用程序
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - 错误和更少的混乱
- [read-art](https://github.com/Tjatse/node-readability) - 从任何页面中提取可读内容

### 压缩
*翻译出错了? 试试 [英文版](readme_en.md#Compression) 吧~*

- [yazl](https://github.com/thejoshwolfe/yazl) - 邮政编码
- [yauzl](https://github.com/thejoshwolfe/yauzl) - 解压缩
- [Archiver](https://github.com/archiverjs/node-archiver) - 流接口的存档生成，支持ZIP和TAR
- [pako](https://github.com/nodeca/pako) - 高速zlib端口到纯js(放气，充气，gzip)
- [tar-stream](https://github.com/mafintosh/tar-stream) - 流tar解析器和生成器也看到(tar-fs) (https://github.com/mafintosh/tar-fs)
- [decompress](https://github.com/kevva/decompress) - 解压模块，支持“tar”、“tar”gz '和' zip '文件开箱

### 网络
*翻译出错了? 试试 [英文版](readme_en.md#Network) 吧~*

- [get-port](https://github.com/sindresorhus/get-port) - 获得一个可用的端口
- [ipify](https://github.com/sindresorhus/ipify) - 获取你的公共IP地址
- [getmac](https://github.com/bevry/getmac) - 获取计算机MAC地址
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP客户端和服务器
- [netcat](https://github.com/roccomuso/netcat) - Netcat端口在纯JS

### 数据库
*翻译出错了? 试试 [英文版](readme_en.md#Database) 吧~*

- Drivers
- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL客户机纯JavaScript和本地libpq绑定
- [Redis](https://github.com/luin/ioredis) - 复述,客户机
- [LevelUP](https://github.com/Level/levelup) - LevelDB
- [MySQL](https://github.com/mysqljs/mysql) - MySQL客户端
- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB客户机
- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - 喷管和钟客户机
- [Couchbase](https://github.com/couchbase/couchnode) - 他的客户
- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB的司机
- ODM / ORM
- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM支持PostgreSQL, SQLite, MySQL
- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM用于PostgreSQL、MySQL和SQLite3，风格为Backbone.js
- [Massive](https://github.com/robconery/massive-js) - PostgreSQL数据访问工具
- [Mongoose](https://github.com/Automattic/mongoose) - 优雅的MongoDB对象建模
- [Waterline](https://github.com/balderdashy/waterline) - 与数据存储无关的工具，极大地简化了与一个或多个数据库的交互
- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM用于PostgreSQL、MySQL、SQLite3和RESTful数据存储ActiveRecord相似
- [pg-promise](https://github.com/vitaly-t/pg-promise) - 使用promise的PostgreSQL本地SQL框架
- [slonik](https://github.com/gajus/slonik) - 具有严格类型、详细日志记录和断言的PostgreSQL客户机
- [Objection.js](https://github.com/Vincit/objection.js) - 轻量级ORM构建于SQL查询生成器Knex之上
- [TypeORM](https://github.com/typeorm/typeorm) - ORM用于PostgreSQL、MariaDB、MySQL、SQLite等
- [MikroORM](https://github.com/mikro-orm/mikro-orm) - 基于数据映射器、工作单元和标识映射模式的TypeScript ORM。支持MongoDB, PostgreSQL, MySQL和SQLite。
- Query builder
- [Knex](https://github.com/tgriesser/knex) - 用于PostgreSQL、MySQL和SQLite3的查询生成器，设计为灵活、可移植且使用有趣
- Other
- [NeDB](https://github.com/louischatriot/nedb) - 用JavaScript编写的嵌入式持久数据库
- [Lowdb](https://github.com/typicode/lowdb) - Lodash支持的小型JavaScript数据库
- [Keyv](https://github.com/lukechilds/keyv) - 简单的键值存储，支持多个后端
- [Finale](https://github.com/tommybananas/finale) - 用于Sequelize模型的RESTful端点生成器
- [database-js](https://github.com/mlaanderson/database-js) - 用于具有类似jdbc连接的多个数据库的包装器
- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - 用JavaScript和JSON文件填充MongoDB数据库
- [@databases](https://github.com/ForbesLindesay/atdatabases) - 查询 PostgreSQL, MySQL 和 SQLite3 与普通SQL - 没有风险的SQL注入。

### 测试
*翻译出错了? 试试 [英文版](readme_en.md#Testing) 吧~*

- [AVA](https://github.com/avajs/ava) - 未来的测试运行器
- [Mocha](https://github.com/mochajs/mocha) - 功能丰富的测试框架，使异步测试简单而有趣
- [nyc](https://github.com/bcoe/nyc) - 代码覆盖工具建立在伊斯坦布尔，与子进程一起工作
- [tap](https://github.com/isaacs/node-tap) - 开发测试框架
- [tape](https://github.com/substack/tape) - TAP-producing测试工具
- [power-assert](https://github.com/power-assert-js/power-assert) - 通过标准断言接口提供描述性断言消息
- [Mochify](https://github.com/mantoni/mochify.js) - TDD与Browserify, Mocha, PhantomJS和WebDriver
- [trevor](https://github.com/vdemedes/trevor) - 运行多个版本的Node.js测试，不需要手动切换版本或推送到Travis CI
- [loadtest](https://github.com/alexfernandez/loadtest) - 使用用于自动化的API为web应用程序运行负载测试
- [Sinon.JS](https://github.com/sinonjs/sinon) - 测试间谍，存根和嘲笑
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS包装器，用于简化浏览器测试脚本
- [Nock](https://github.com/pgte/nock) - HTTP模拟和期望
- [intern](https://github.com/theintern/intern) - 代码测试堆栈
- [toxy](https://github.com/h2non/toxy) - 可编程HTTP代理，用于模拟故障场景和网络条件
- [hook-std](https://github.com/sindresorhus/hook-std) - 挂钩和修改stdout/stderr
- [testen](https://github.com/egoist/testen) - 使用NVM在本地运行Node.js的多个版本的测试
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于Selenium WebDriver的自动化UI测试框架
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - 基于WebDriver协议的自动化测试
- [Jest](https://github.com/facebook/jest) - 无痛的JavaScript测试
- [TestCafe](https://github.com/DevExpress/testcafe) - 浏览器自动化测试
- [abstruse](https://github.com/bleenco/abstruse) - 持续集成服务器
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - 端到端测试
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome
- [Playwright](https://github.com/microsoft/playwright) - Headless Chromium，WebKit，和 Firefox 使用单一的 API。
- [nve](https://github.com/ehmicky/nve) - 在Node.js的多个版本上本地运行任何命令。

### 安全
*翻译出错了? 试试 [英文版](readme_en.md#Security) 吧~*

- [upash](https://github.com/simonepri/upash) - 统一的API为所有密码哈希算法
- [themis](https://github.com/cossacklabs/themis) - 使典型加密方案易于使用的多语言框架:静态数据、经过身份验证的数据交换、传输保护、身份验证等等
- [GuardRails](https://github.com/apps/guardrails) - 在拉请求中提供安全反馈的GitHub应用程序
- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - 暴力和DDoS攻击保护
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - 异步非阻塞散列
- [jose-simple](https://github.com/davesag/jose-simple) - 使用JOSE (JSON对象签名和加密)标准对数据进行加密和解密。

### 基准测试
*翻译出错了? 试试 [英文版](readme_en.md#Benchmarking) 吧~*

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - 基准库，支持高分辨率定时器，并返回统计上显著的结果
- [matcha](https://github.com/logicalparadox/matcha) - 基准测试的简单方法

### 代码压缩
*翻译出错了? 试试 [英文版](readme_en.md#Minifiers) 吧~*

- [babili](https://github.com/babel/babili) - 基于Babel工具链的ES2015+感知缩小器
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript缩小镜
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS缩小镜
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
- [imagemin](https://github.com/imagemin/imagemin) - 图像缩小镜

### 身份验证
*翻译出错了? 试试 [英文版](readme_en.md#Authentication) 吧~*

- [Passport](https://github.com/jaredhanson/passport) - 简单、低调的身份验证
- [Grant](https://github.com/simov/grant) - 用于Express、Koa和Hapi的OAuth中间件

### 授权
*翻译出错了? 试试 [英文版](readme_en.md#Authorization) 吧~*

- [CASL](https://github.com/stalniy/casl) - UI和API的同构授权
- [node-casbin](https://github.com/casbin/node-casbin) - 支持ACL、RBAC和ABAC等访问控制模型的授权库

### 邮件
*翻译出错了? 试试 [英文版](readme_en.md#Email) 吧~*

- [Nodemailer](https://github.com/andris9/Nodemailer) - 处理电子邮件的最快方式
- [emailjs](https://github.com/eleith/emailjs) - 发送带有附件的文本/HTML电子邮件到任何SMTP服务器
- [email-templates](https://github.com/niftylettuce/email-templates) - 创建、预览和发送自定义电子邮件模板
- [MJML](https://github.com/mjmlio/mjml) - 标记语言，旨在减少创建响应电子邮件的痛苦

### 工作队列
*翻译出错了? 试试 [英文版](readme_en.md#Job%20queues) 吧~*

- [bull](https://github.com/OptimalBits/bull) - 持久作业和消息队列
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed工作调度
- [idoit](https://github.com/nodeca/idoit) - 具有高级作业控制的redis支持的作业队列引擎
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed工作队列
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed消息队列
- [bee-queue](https://github.com/bee-queue/bee-queue) - 高性能redis支持的作业队列
- [RedisSMQ](https://github.com/weyoss/redis-smq) - 简单的高性能Redis消息队列与实时监控
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - 构建基于Amazon Simple Queue Service (SQS)的应用程序，不使用样板
- [better-queue](https://github.com/diamondio/better-queue) - 当您不能使用Redis时，可以使用简单而高效的作业队列

### Node.js 管理
*翻译出错了? 试试 [英文版](readme_en.md#Node.js%20management) 吧~*

- [n](https://github.com/tj/n) - Node.js 版本管理
- [nave](https://github.com/isaacs/nave) - Node.js 的虚拟环境
- [nodeenv](https://github.com/ekalinin/nodeenv) - js虚拟环境兼容Python的 virtualenv
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Windows 版本管理
- [nodenv](https://github.com/nodenv/nodenv) - 类似于Ruby的rbenv的版本管理器它支持自动版本切换

### 自然语言处理
*翻译出错了? 试试 [英文版](readme_en.md#Natural%20language%20processing) 吧~*

- [retext](https://github.com/wooorm/retext) - 一个可扩展的自然语言系统
- [franc](https://github.com/wooorm/franc) - 检测文本的语言
- [leven](https://github.com/sindresorhus/leven) - 使用Levenshtein距离算法测量两个字符串之间的差异
- [natural](https://github.com/NaturalNode/natural) - 自然语言工具
- [nlp.js](https://github.com/axa-group/nlp.js) - 构建机器人，具有实体提取、情感分析、自动语言识别等功能

### 流程管理
*翻译出错了? 试试 [英文版](readme_en.md#Process%20management) 吧~*

- [PM2](https://github.com/Unitech/pm2) - 先进的流程管理
- [nodemon](https://github.com/remy/nodemon) - 监视应用程序中的更改并自动重启服务器
- [node-mac](https://github.com/coreybutler/node-mac) - 以本机Mac守护进程的身份运行脚本，并登录到控制台应用程序
- [node-linux](https://github.com/coreybutler/node-linux) - 将脚本作为本地系统服务运行，并将日志记录到syslog
- [node-windows](https://github.com/coreybutler/node-windows) - 将脚本作为本机Windows服务运行，并记录到事件查看器
- [supervisor](https://github.com/petruisfan/node-supervisor) - 当脚本崩溃或' *时重新启动脚本js文件的更改
- [Phusion Passenger](https://github.com/phusion/passenger) - 友好的过程管理器，直接集成到Nginx

### 自动化
*翻译出错了? 试试 [英文版](readme_en.md#Automation) 吧~*

- [robotjs](https://github.com/octalmage/robotjs) - 桌面自动化:控制鼠标、键盘和阅读屏幕

### AST
*翻译出错了? 试试 [英文版](readme_en.md#AST) 吧~*

- [Acorn](https://github.com/ternjs/acorn) - 小巧、快速的JavaScript解析器
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - Babel中使用的JavaScript解析器
- [cherow](https://github.com/cherow/cherow) - 专注于性能和稳定性的JavaScript解析器

### 静态网站生成器
*翻译出错了? 试试 [英文版](readme_en.md#Static%20site%20generators) 吧~*

- [Wintersmith](https://github.com/jnordberg/wintersmith) - 灵活，简约，多平台静态站点生成器
- [Assemble](https://github.com/assemble/assemble/) - 节点的静态站点生成器js,咕哝着说js和自耕农
- [DocPad](https://github.com/docpad/docpad) - 静态站点生成器具有强大的动态功能和强大的插件生态系统
- [Phenomic](https://github.com/phenomic/phenomic) - 基于React和Webpack生态系统的现代静态网站生成器
- [docsify](https://github.com/QingWei-Li/docsify) - 标记文件网站生成器，没有静态构建的HTML文件
- [Charge](https://github.com/brandonweiss/charge) - 使用JSX和MDX的固执己见的零配置静态站点生成器

### 内容管理系统
*翻译出错了? 试试 [英文版](readme_en.md#Content%20management%20systems) 吧~*

- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS和基于Express和MongoDB的web应用平台
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - 内容管理系统，强调直观的前端内容编辑和管理建立在Express和MongoDB上
- [Strapi](https://github.com/strapi/strapi) - 内容管理框架(headless-CMS)来构建强大的api
- [Tipe](https://github.com/tipeio/tipe) - 开发人员优先的内容管理系统，包含来自模式文件的GraphQL和REST API

### 论坛
*翻译出错了? 试试 [英文版](readme_en.md#Forum) 吧~*

- [nodeBB](https://github.com/NodeBB/NodeBB) - 现代网络论坛平台

### 写博客
*翻译出错了? 试试 [英文版](readme_en.md#Blogging) 吧~*

- [Ghost](https://github.com/TryGhost/Ghost) - 简单、强大的发布平台
- [Hexo](https://github.com/hexojs/hexo) - 快速，简单和强大的博客框架

### 奇怪的
*翻译出错了? 试试 [英文版](readme_en.md#Weird) 吧~*

- [cows](https://github.com/sindresorhus/cows) - ASCII奶牛
- [superb](https://github.com/sindresorhus/superb) - 获得一流的喜欢的话
- [cat-names](https://github.com/sindresorhus/cat-names) - 给猫取个流行的名字
- [dog-names](https://github.com/sindresorhus/dog-names) - 给狗取个流行的名字
- [superheroes](https://github.com/sindresorhus/superheroes) - 得到超级英雄的名字
- [supervillains](https://github.com/sindresorhus/supervillains) - 让信心满满的名字
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - 得到一些很酷的ascii面
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - “₍˄·͈༝·͈˄₎◞̑̑ෆ⃛(=ↀωↀ=)✧(^･o･^)ﾉ”
- [nerds](https://github.com/SkyHacks/nerds) - 从《哈利波特》、《星球大战》和《精灵宝可梦》等书呆子题材中获取数据

### 序列化
*翻译出错了? 试试 [英文版](readme_en.md#Serialization) 吧~*

- [snappy](https://github.com/kesla/node-snappy) - 用于谷歌的快速压缩库的本机绑定
- [protobuf](https://github.com/dcodeIO/protobuf.js) - 协议缓冲区的实现
- [compactr](https://github.com/compactr/compactr.js) - 实现Compactr协议

### 杂项
*翻译出错了? 试试 [英文版](readme_en.md#Miscellaneous) 吧~*

- [execa](https://github.com/sindresorhus/execa) - 更好的“child_process”
- [cheerio](https://github.com/cheeriojs/cheerio) - 快速、灵活、精益地实现了专门为服务器设计的核心jQuery
- [Electron](https://github.com/atom/electron) - 使用web技术构建跨平台的桌面应用程序*(你可能会喜欢[awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [open](https://github.com/sindresorhus/open) - 打开网站、文件、可执行文件等
- [hasha](https://github.com/sindresorhus/hasha) - 散列法简单获取缓冲区/字符串/流/文件的散列
- [dot-prop](https://github.com/sindresorhus/dot-prop) - 使用点路径从嵌套对象中获取属性
- [onetime](https://github.com/sindresorhus/onetime) - 只运行一个函数一次
- [mem](https://github.com/sindresorhus/mem) - 记忆函数——一种优化技术，通过缓存具有相同输入的调用的结果来加速连续的函数调用
- [import-fresh](https://github.com/sindresorhus/import-fresh) - 绕过缓存导入模块
- [strip-bom](https://github.com/sindresorhus/strip-bom) - 从字符串/缓冲区/流中剥离UTF-8字节顺序标记(BOM)
- [os-locale](https://github.com/sindresorhus/os-locale) - 获取系统区域设置
- [ssh2](https://github.com/mscdex/ssh2) - SSH2客户端和服务器模块
- [adit](https://github.com/markelog/adit) - SSH隧道简化
- [import-lazy](https://github.com/sindresorhus/import-lazy) - 延迟导入模块
- [file-type](https://github.com/sindresorhus/file-type) - 检测缓冲区的文件类型
- [Bottleneck](https://github.com/SGrondin/bottleneck) - 使节流容易的速率限制器
- [ow](https://github.com/sindresorhus/ow) - 用于人的函数参数验证
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - 使用本机线程实现轻量级Web工作者API
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 访问系统剪贴板(复制/粘贴)
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - 使从二进制文件发布和安装Node.js c++插件变得容易
- [opencv](https://github.com/peterbraden/node-opencv) - 绑定OpenCV事实上的计算机视觉库
- [dotenv](https://github.com/motdotla/dotenv) - 从.env文件中加载环境变量
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - 从远程git repo获取标记
- [semver](https://github.com/npm/node-semver) - 语义版本解析器
- [Faker.js](https://github.com/Marak/Faker.js) - 生成大量的假数据
- [nodegit](https://github.com/nodegit/nodegit) - 到Git的本机绑定
- [json-strictify](https://github.com/pigulla/json-strictify) - 安全地将值序列化为JSON，而不会丢失数据或进入无限循环
- [resolve-from](https://github.com/sindresorhus/resolve-from) - 解析模块的路径，比如“require.resolve()”，但要从给定的路径解析
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 事件驱动的web爬虫程序
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript实现的HTML和DOM
- [hypernova](https://github.com/airbnb/hypernova) - 服务器端呈现JavaScript视图
- [@sindresorhus/is](https://github.com/sindresorhus/is) - 类型检查值
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - 获取、设置或删除进程的嵌套属性使用点路径的env
- [emittery](https://github.com/sindresorhus/emittery) - 简单而现代的异步事件发射器
- [node-video-lib](https://github.com/gkozlenko/node-video-lib) - 纯JavaScript库，用于处理MP4和FLV视频文件，并为HLS流媒体创建MPEG-TS块
- [basic-ftp](https://github.com/patrickjuchli/basic-ftp) – FTP/FTPS client.
- [cashify](https://github.com/xxczaki/cashify) - 货币转换。
- [genepi](https://github.com/Geode-solutions/genepi) - 从c++代码自动生成一个本机Node.js插件。

## 资源

### 教程
*翻译出错了? 试试 [英文版](readme_en.md#Tutorials) 吧~*

- [Node.js Best Practices](https://github.com/i0natan/nodebestpractices) - 对Node.js最佳实践的顶级内容进行总结和整理，可使用多种语言
- [Nodeschool](https://github.com/nodeschool) - 通过交互式课程学习Node.js
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - 介绍Node.js
- [stream-handbook](https://github.com/substack/stream-handbook) - 如何使用流编写Node.js程序
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - 编写新的npm模块时的一些良好实践
- [The Node Way](http://thenodeway.io) - 对于编写可维护的模块、可伸缩的应用程序和实际上易于阅读的代码，有一整套Node.js最佳实践和指导原则
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - 介绍Node.js的核心特性和异步JavaScript
- [Portable Node.js guide](https://github.com/ehmicky/portable-node-guide) - 如何编写可移植/跨平台Node.js代码的实用指南
- [Build a real web app with no frameworks](https://frameworkless.js.org/course) - 一组视频教程/流媒体，帮助您构建和部署一个真实的，实时的web应用程序，使用一些简单的库和核心Node.js模块

### 发现
*翻译出错了? 试试 [英文版](readme_en.md#Discovery) 吧~*

- [npms](https://npms.io) - 出色的包搜索与深入分析包质量使用[无数的指标](https://npms.io/about)
- [npm addict](https://npmaddict.com) - 您每天注射的npm包
- [npmcompare.com](https://npmcompare.com) - 比较和发现npm包

### 文章
*翻译出错了? 试试 [英文版](readme_en.md#Articles) 吧~*

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README](https://github.com/noffle/art-of-readme) - 学习写作高质量读物的艺术
- [Using Express to Quickly Build a GraphQL Server](https://snipcart.com/blog/graphql-nodejs-express-tutorial)

### 时事新闻
*翻译出错了? 试试 [英文版](readme_en.md#Newsletters) 吧~*

- [Node Weekly](http://nodeweekly.com) - 每周通过电子邮件收集Node.js的新闻和文章
- [Node Module Of The Week!](https://nmotw.in) - 每周人工采摘的节点模块剂量

### 视频
*翻译出错了? 试试 [英文版](readme_en.md#Videos) 吧~*

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/hands-on-with-node.js/preface)
- [Nodetuts](http://nodetuts.com) - 系列讲座，包括TCP和HTTP API服务器，异步编程，等等
- [V8 Garbage Collector](https://v8.dev/blog/trash-talk) - 谈论V8垃圾收集器
- [10 Things I Regret About Node.js by Ryan Dahl](https://www.youtube.com/watch?v=M3BM9TB-8yA) - 由Node.js的创建者关于它的一些limitions的见解。

### 书
*翻译出错了? 试试 [英文版](readme_en.md#Books) 吧~*

- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building JavaScript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)
- [Practical Modern JavaScript](https://www.amazon.com/Practical-Modern-JavaScript-Dive-Future/dp/149194353X)
- [Mastering Modular JavaScript](https://www.amazon.com/Mastering-Modular-JavaScript-Nicolas-Bevacqua/dp/1491955686/)
- [Get Programming with Node.js](https://www.manning.com/books/get-programming-with-node-js)

### 博客
*翻译出错了? 试试 [英文版](readme_en.md#Blogs) 吧~*

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - 来自实用Node.js和Pro Express.js Azat Mardan的作者关于Node.js和JavaScript的博客文章

### 课程
*翻译出错了? 试试 [英文版](readme_en.md#Courses) 吧~*

- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - 视频课程由韦斯博斯
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### 备忘单
*翻译出错了? 试试 [英文版](readme_en.md#Cheatsheets) 吧~*

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - 回答关于流的常见问题，包括分页、事件等等
- [Strong Node.js](https://github.com/jesusprubio/strong-node) - 用于Node.js web服务的源代码安全分析的检查表

### 工具
*翻译出错了? 试试 [英文版](readme_en.md#Tools) 吧~*

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - 连接包中的依赖项的Chrome扩展GitHub上的json、.js、.jsx、.coffee和.md文件
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome扩展，以显示npm依赖关系的底部回购的自述
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - 在任何网站上嵌入Node.js环境
- [RequireBin](http://requirebin.com) - 可共享的JavaScript程序支持npm和browserify
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome扩展，显示在GitHub上的npm下载统计数据
- [npm semver calculator](https://semver.npmjs.com) - 直观地探索semver范围匹配的包的版本
- [CodeSandbox](https://codesandbox.io/s/node-http-server-node) - 在线IDE和原型。

### 社区
*翻译出错了? 试试 [英文版](readme_en.md#Community) 吧~*

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)
- [Discord](https://discordapp.com/invite/96WGtJt)

### 杂项
*翻译出错了? 试试 [英文版](readme_en.md#Miscellaneous) 吧~*

- [nodebots](http://nodebots.io) - 由JavaScript驱动的机器人
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - 开始创建节点模块的样板文件
- [modern-node](https://github.com/sheerun/modern-node) - 用于创建具有Jest、Prettier、ESLint和Standard的节点模块的工具包
- [generator-nm](https://github.com/sindresorhus/generator-nm) - 构建一个节点模块
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - 在微软平台上使用Node.js的技巧和资源
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - 请求一个您希望存在的JavaScript模块，或者获取模块的想法

## 相关的列表

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - 使用npm的资源和技巧
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - 用于编写和测试跨平台代码的资源

