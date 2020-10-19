
[Awesome]: icons/awesome.svg "star > 2000"
[Green]: icons/Green.svg "最近一周有更新"
[Yellow]: icons/Yellow.svg "最近一年没有更新"
[Archived]: icons/archived.svg "项目已归档"
      
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<p>
		<p>
			<sup>
				<a href="https://github.com/sponsors/sindresorhus">My open source work is supported by the community</a>
			</sup>
		</p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://standardresume.co">
			<img src="https://sindresorhus.com/assets/thanks/standard-resume-logo.svg" width="160"/>
		</a>
	</p>
	<br>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Just type <a href="https://node.cool"><code>node.cool</code></a> to go here. Follow me on <a href="https://twitter.com/sindresorhus">Twitter</a>.</sub>
	</p>
	<br>
	<p>
		<a href="https://en.wikipedia.org/wiki/Node.js">Node.js</a> is an open-source, cross-platform, JavaScript runtime for writing servers and command-line tools.
	</p>
	<br>
</div>

**此项目是 [awesome-nodejs](https://raw.githubusercontent.com/sindresorhus/awesome-nodejs/master/readme.md) 中文版，每天定时同步（上次同步时间：2020-10-19 08:08:53）**

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

- [webtorrent](https://github.com/feross/webtorrent) - **star:22727** 可在 Node.js 和浏览器使用的流式 Torrent 客户端 ![star > 2000][Awesome] 
- [peerflix](https://github.com/mafintosh/peerflix) - **star:5496** 流式 Torrent 客户端 ![star > 2000][Awesome] 
- [dat](https://github.com/datproject/dat-node) - **star:499** 数据集的实时复制和版本控制
- [ipfs](https://github.com/ipfs/js-ipfs) - **star:4763** 分布式文件系统，用于将所有计算设备与同一文件系统连接起来 ![star > 2000][Awesome] 
- [stackgl](https://github.com/stackgl) - 基于 browserify 和 npm 的 WebGL 开放软件生态系统
- [peerwiki](https://github.com/mafintosh/peerwiki) - **star:298** 建立在在 BitTorrent 上的维基百科
- [peercast](https://github.com/mafintosh/peercast) - **star:465** 将种子视频流式传输到 Chromecast
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - **star:3958** 干净、可读比特币库 ![star > 2000][Awesome] 
- [Bitcore](https://github.com/bitpay/bitcore) - **star:3744** 纯净、强大的比特币库 ![star > 2000][Awesome] 
- [PDFKit](https://github.com/devongovett/pdfkit) - **star:6549** PDF 生成库 ![star > 2000][Awesome] 
- [turf](https://github.com/Turfjs/turf) - **star:5571** 模块化地理空间处理和分析引擎 ![star > 2000][Awesome] 
- [webcat](https://github.com/mafintosh/webcat) - **star:411** 使用 WebRTC 跨 web 的 p2p 管道，它使用 GitHub 私有/公共密钥进行身份验证
- [NodeOS](https://github.com/NodeOS/NodeOS) - **star:6278** 第一个由 npm 驱动的操作系统 ![star > 2000][Awesome] 
- [YodaOS](https://github.com/yodaos-project/yodaos) - **star:1034** 人工智能操作系统
- [Brain.js](https://github.com/BrainJS/brain.js) - **star:11418** 机器学习框架 ![star > 2000][Awesome] 
