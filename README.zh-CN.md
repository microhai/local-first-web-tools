<div align="center">

# ⚡ MicroHai — 纯本地浏览器在线工具箱

**70+ 款免费、极速、隐私优先的在线工具：100% 浏览器本地运行，数据绝不上传服务器。**

[English](./README.md) · **简体中文** · [Español](./README.es.md) · [Français](./README.fr.md) · [Português](./README.pt.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md)

[![Website](https://img.shields.io/badge/Website-microhai.com-4f46e5?style=for-the-badge)](https://www.microhai.com/zh) [![Tools](https://img.shields.io/badge/Tools-71%2B-10b981?style=for-the-badge)](https://www.microhai.com/zh) [![Privacy](https://img.shields.io/badge/Privacy-100%25_Local-0ea5e9?style=for-the-badge)](https://www.microhai.com/zh) [![Languages](https://img.shields.io/badge/Languages-7-f59e0b?style=for-the-badge)](https://www.microhai.com/zh)

### 👉 [立即使用 MicroHai 在线工具箱 (https://www.microhai.com/zh)](https://www.microhai.com/zh)

[![MicroHai — 纯本地浏览器在线工具箱](./assets/og-cover.png)](https://www.microhai.com/zh)

</div>

---

## 🔒 为什么选择纯本地（Local-First）？

- **100% 浏览器本地隐私保护**：PDF 合同、超大服务器日志、照片、视频与加解密密钥全部在本地内存处理，绝不上传至任何服务器。
- **免登录、无水印、断网可用**：打开网页即用，无队列等待、无使用次数限制，大文件支持流式零拷贝处理。
- **一站式 71+ 款高频工具**：覆盖开发者调试、文本与 PDF 文档、图片与音视频处理、安全加解密、硬件检测与日常效率计算。
- **原生 7 国语言界面**：支持 English、简体中文、Español、Français、Português、日本語、한국어。

---

## 🧰 全站工具目录 (71)

### 开发者与代码 (16)

> JSON 格式化/对比/加密/转Excel/生成实体、正则、HTTP/WebSocket 调试、UUID/ULID 生成及格式/进制转换 — [查看该分类全部工具 →](https://www.microhai.com/zh/category/dev)

| 工具名称 | 功能简介 |
| :--- | :--- |
| [**JSON 在线解析 / 视图 / 着色 / 压缩**](https://www.microhai.com/zh/tools/json-formatter) | JSON 在线编辑器、语法着色、可折叠树形视图、一键压缩成一行、Key 排序及转义去转义 |
| [**JSON 字段加密 / 解密 / 脱敏**](https://www.microhai.com/zh/tools/json-crypto) | 保留 JSON 结构仅对 Value 进行 AES/Base64 加密解密，或对手机号/邮箱等敏感字段脱敏 |
| [**JSON 混淆与还原工具**](https://www.microhai.com/zh/tools/json-obfuscator) | 对 JSON 配置进行键名映射混淆（_0x...）与全量 Unicode 编码混淆，支持凭映射表一键还原 |
| [**JS 代码混淆与反混淆工具（高级版）**](https://www.microhai.com/zh/tools/js-obfuscator) | 支持字符串数组提取位移、Base64/Hex/Unicode 编码、变量重命名、数字/布尔混淆、死代码注入、域名锁定与反调试 |
| [**JSON 在线对比 (Diff)**](https://www.microhai.com/zh/tools/json-diff) | 深度结构化对比两份 JSON 数据，精准高亮新增、删除与变更的字段及 JSONPath 路径 |
| [**JSON 生成实体类 (TS/Java/Go/Py/C#)**](https://www.microhai.com/zh/tools/json-to-entity) | 根据嵌套 JSON 一键生成 TypeScript 接口、Java 实体类、Go Struct、Python Dataclass 与 C# 类 |
| [**JSON 转 Excel / CSV 表格导出**](https://www.microhai.com/zh/tools/json-to-excel) | 将 JSON 数组实时预览为表格（支持嵌套对象展开），并一键导出为 Excel (.xls) 或 CSV 文件 |
| [**JSON / YAML / CSV / XML / TS 互转**](https://www.microhai.com/zh/tools/data-converter) | 在 JSON、YAML 配置、CSV 表格数据、XML 节点与 TypeScript Interface 类型定义之间无缝转换 |
| [**Unix 时间戳与整数进制转换**](https://www.microhai.com/zh/tools/dev-converter) | 集成 Unix 秒/毫秒时间戳与日期互转、2/8/10/16/36 任意大数进制互转 |
| [**在线颜色转换器 (HEX / RGB / HSL)**](https://www.microhai.com/zh/tools/color-converter) | 可视化调色盘、透明度调节、RGB 通道编辑、HEX/RGBA/HSL/CSS 变量一键复制与对比度预览 |
| [**正则表达式在线测试器**](https://www.microhai.com/zh/tools/regex-tester) | 实时正则匹配高亮、捕获组 ($1/$2) 解析、常用正则预设一键填入与正则替换预览 |
| [**WebSocket 在线测试工具**](https://www.microhai.com/zh/tools/websocket-tester) | 支持 ws:// 与 wss:// 连接测试、Text/JSON/Hex/Base64 发送、自动心跳与实时消息日志分析 |
| [**HTTP 接口在线测试工具**](https://www.microhai.com/zh/tools/http-tester) | 支持 GET/POST/PUT/DELETE 请求调试、Params/Headers/鉴权/JSON 请求体配置、响应美化与 cURL 导出 |
| [**在线端口扫描器**](https://www.microhai.com/zh/tools/port-scanner) | 通过 HTTP/HTTPS 并发探测本机与局域网开放端口，内置常见端口服务字典与 nmap / PowerShell 扫描命令生成 |
| [**字符串 ⇄ 进制转换 (Hex/二进制/八进制/十进制)**](https://www.microhai.com/zh/tools/string-base-converter) | 支持双向编辑的 UTF-8 字符串与 16/2/8/10 进制互转，可选 0x/0b/0o 前缀、空格隔开与字母大小写 |
| [**UUID v4 / v7 与 ULID 批量生成器**](https://www.microhai.com/zh/tools/uuid-ulid-generator) | 支持批量生成 1–1000 个 UUID v7（时间有序）、UUID v4 与单调递增 ULID，支持 JSON/SQL/CSV 格式与时间戳反解析 |

### 文本与排版 (12)

> Markdown 转 HTML/图片/PDF、全能 PDF 合并拆分与格式互转、文本对比 Diff、去重排序与字数统计 — [查看该分类全部工具 →](https://www.microhai.com/zh/category/text)

| 工具名称 | 功能简介 |
| :--- | :--- |
| [**Markdown 在线编辑与转 HTML**](https://www.microhai.com/zh/tools/markdown-converter) | 实时双栏预览 Markdown 文档，支持一键复制排版样式、导出纯净 HTML 代码或完整网页文件 |
| [**Markdown 转图片 / 转 PDF**](https://www.microhai.com/zh/tools/markdown-to-image-pdf) | 将 Markdown 一键渲染为 2 倍高清长图（PNG/JPG，支持直接复制图片）或矢量排版 A4 PDF 文档 |
| [**PDF 合并 / 拆分 / 删页工具**](https://www.microhai.com/zh/tools/pdf-toolkit) | 100% 浏览器本地合并多个 PDF、按页码区间或每 N 页拆分、可视化删页/排序与旋转页面 |
| [**转换为 PDF（Word / Excel / PPTX / EPUB / HTML / PNG / JPG）**](https://www.microhai.com/zh/tools/convert-to-pdf) | 支持 Word(.docx)、Excel(.xlsx/.xls)、PPTX、EPUB、HTML、PNG、JPG、Markdown 等常用格式 100% 本地转 PDF |
| [**PDF 转换器（转 Word / PNG / JPG / EPUB / Excel / PPTX / HTML / TXT）**](https://www.microhai.com/zh/tools/pdf-converter) | 100% 浏览器本地将 PDF 转换为 Word(.docx)、PNG、JPG、EPUB、Excel(.xlsx)、PPTX、HTML 与 TXT |
| [**文本对比 Diff / 去重 / 统计工具**](https://www.microhai.com/zh/tools/text-processor) | 多行文本去重排序、空白清理、前后缀批量添加、正则提取、中英文字数统计与行级差异对比 |
| [**在线电子手写签名板（透明背景 PNG / 矢量 SVG）**](https://www.microhai.com/zh/tools/signature-pad) | 支持鼠标、手机触屏与压感笔流畅手写签名（含钢笔笔锋效果），自动裁剪空白边距，一键导出高清透明 PNG 或矢量 SVG 插入 Word / PDF |
| [**PDF 敏感信息永久涂黑 / 抹除器（真·物理脱敏）**](https://www.microhai.com/zh/tools/pdf-redactor) | 纯本地永久涂黑/抹除合同、简历、流水 PDF 中的敏感信息：支持手动框选与全篇自动识别手机号/身份证/银行卡/关键词，栅格化压平彻底销毁底层文字 |
| [**PDF 批量加防盗 / 作废水印工具（支持中文与 Logo）**](https://www.microhai.com/zh/tools/pdf-watermark) | 纯本地批量给多份 PDF 加全屏防盗平铺水印、红色「已作废 VOID / 内部机密」双框印章或透明 PNG Logo：无损保留原矢量清晰度，一键 ZIP 打包下载 |
| [**超大纯文本 / 日志文件本地切分与合并器**](https://www.microhai.com/zh/tools/text-log-splitter) | 纯本地流式切分百 MB 至 GB 级 TXT/LOG/CSV/JSONL/SQL 大文件（按大小、行数、N 份或正则标记），支持 CSV 自动保留表头、关键词筛选及多文件无损合并 |
| [**表情符号、特殊符号与花体字生成器**](https://www.microhai.com/zh/tools/fancy-text-symbols) | 实时生成 24+ 种 Unicode 英文花体字/哥特体/圆圈体/倒立字并一键加花边，内置全分类特殊符号大全、双语搜索 Emoji 与经典颜文字，支持单击复制或拼接组合 |
| [**在线文字云 / 词云图生成器（高清 PNG / 矢量 SVG）**](https://www.microhai.com/zh/tools/word-cloud-generator) | 粘贴文章自动中英文分词统计或自定义词频权重，一键生成云朵、爱心、圆形、五角星等异形文字云，支持 8 套配色、透明背景高清 PNG 与矢量 SVG 导出 |

### 多媒体与图片 (16)

> 图片压缩/打码/水印/拼图/去EXIF、格式与Base64转换/取色配盘、以及在线录屏/摄像头录制、视频转GIF与高清抽帧 — [查看该分类全部工具 →](https://www.microhai.com/zh/category/media)

| 工具名称 | 功能简介 |
| :--- | :--- |
| [**图片压缩与格式转换 (WebP/PNG/JPG)**](https://www.microhai.com/zh/tools/image-compressor) | 纯浏览器本地调整压缩质量与目标格式，直观对比压缩前后体积与省流百分比，绝不上传图片 |
| [**图片加水印与尺寸调整**](https://www.microhai.com/zh/tools/image-watermark) | 为证件照或作品图添加全屏斜向平铺防盗文字水印或角落签名水印，支持自定义颜色、透明度与间距 |
| [**图片与 Base64 编码互转**](https://www.microhai.com/zh/tools/image-base64) | 将图片转为 DataURL Base64 字符串、HTML img 标签或 CSS 背景代码；或将 Base64 还原为图片下载 |
| [**图片格式转换器 (PNG/JPG/WebP/ICO/BMP)**](https://www.microhai.com/zh/tools/image-converter) | 支持 PNG、JPG、WebP、SVG、GIF、BMP、AVIF 与 ICO 图标本地批量互转，支持画质与尺寸自定义 |
| [**图片 EXIF 元数据查看与清除器**](https://www.microhai.com/zh/tools/exif-tool) | 本地查看照片相机型号、拍摄参数、GPS 定位与 AI 生成信息，并支持 JPEG 无损擦除全部隐私元数据 |
| [**图片取色器与主色调色板提取**](https://www.microhai.com/zh/tools/image-color-picker) | 点击图片任意像素精准获取 HEX/RGB/HSL 色值，自动提取 5–16 种主色调色板并支持导出 CSS/JSON/色卡图 |
| [**视频抽帧提取器 (Video Frame Extractor)**](https://www.microhai.com/zh/tools/video-frame-extractor) | 纯本地从 MP4/WebM/MOV 视频逐帧截取或批量抽取高清 PNG/JPG/WebP 图片，支持一键打包 ZIP 下载 |
| [**图片合并器与社交拼图工具**](https://www.microhai.com/zh/tools/image-merger) | 23 种国内外爆款拼图模板（IG 碎片/油管 VS/Pinterest 情绪板/复古报纸/便当盒/拍立得/35mm胶片）+ 全平台画幅一键适配 |
| [**视频转 GIF 动图生成器 (MP4 / WebM / MOV)**](https://www.microhai.com/zh/tools/video-to-gif) | 纯浏览器本地将 MP4/WebM/MOV 转为无水印高清 GIF：支持时间截取、FPS/尺寸/倍速、倒放与往返鬼畜循环、抖动优化及表情包配字 |
| [**图片局部马赛克 / 高斯模糊打码器**](https://www.microhai.com/zh/tools/image-mosaic-blur) | 纯浏览器本地给图片打码：支持矩形框选与画笔涂抹、像素马赛克/高斯模糊/纯色涂黑、Ctrl+V 粘贴截图及原图无损分辨率导出 |
| [**在线屏幕录制 / 本地摄像头录屏小工具**](https://www.microhai.com/zh/tools/screen-recorder) | 纯浏览器本地无水印录屏：支持纯录屏、纯摄像头录像与「录屏+摄像头画中画」、系统音+麦克风混音、30/60fps、暂停续录与一键导出 |
| [**音频频谱 / 声波图艺术海报生成器**](https://www.microhai.com/zh/tools/audio-soundwave-poster) | 把 MP3/WAV 音乐或现场语音录音变成高颜值声波海报：5 种声波样式、8 套美学配色、4 种海报比例，纯本地导出高清 PNG 与矢量 SVG |
| [**视频静音 / 去除音轨工具（无损 MP4 / MOV / WebM）**](https://www.microhai.com/zh/tools/video-mute-remover) | 纯浏览器本地一键消除视频原声：MP4/MOV 毫秒级无损直切剥离音轨（不降画质），并支持 WebM 兼容重编码去音轨与片段裁剪 |
| [**图片叠加 / 多图层合成与双重曝光工具**](https://www.microhai.com/zh/tools/image-overlay) | 纯本地给底图叠加多张 Logo/PNG 贴纸/印章/照片：支持画布直接拖拽、缩放旋转、圆角/圆形裁切、投影与 10 种 PS 混合模式（滤色/正片叠底） |
| [**图片 ASCII 字符画生成器（全彩 / 黑客终端 / 导出 PNG）**](https://www.microhai.com/zh/tools/image-to-ascii) | 把任意照片或截图转成高颜值 ASCII 字符画：支持全彩 RGB、黑客绿/琥珀终端、6 种字符集预设与自定义字符，一键导出 TXT/HTML/高清 PNG |
| [**图片像素化 / 马赛克艺术化转换器（8-bit / 拼豆 / 积木画）**](https://www.microhai.com/zh/tools/pixel-art-converter) | 把照片秒变 8-bit 复古像素画、拼豆圆珠图纸、乐高积木凸点、钻石画或十字绣：内置 8 套游戏色板、抖动算法、10×10 计数网格与高清/1:1 导出 |

### 安全与加解密 (5)

> AES/DES/RC4 对称加解密、MD5/SHA256/HMAC 哈希、JWT 解析签发验签、强密码生成及 Base64/URL/Hex 编解码 — [查看该分类全部工具 →](https://www.microhai.com/zh/category/security)

| 工具名称 | 功能简介 |
| :--- | :--- |
| [**AES / DES / RC4 在线加密解密**](https://www.microhai.com/zh/tools/symmetric-crypto) | 支持 AES、DES、TripleDES、RC4 对称加密，可选 CBC/ECB 模式、PKCS7 填充与 Base64/Hex 输出 |
| [**多算法哈希生成与文件防篡改校验**](https://www.microhai.com/zh/tools/hash-generator) | 支持 MD5/SHA1/SHA256/SHA512/SHA3/CRC16/CRC32/Adler32/RIPEMD-160/MD4/NTLM 共 16 种算法，支持本地文件拖入与校验值比对防篡改 |
| [**Base64 / URL / Hex / Unicode 编码转换**](https://www.microhai.com/zh/tools/codec-converter) | 完美支持 UTF-8 中文的 Base64 编解码、URL 编码、Hex 十六进制、Unicode 与 HTML 实体互转 |
| [**随机密码生成器**](https://www.microhai.com/zh/tools/password-generator) | 基于 Web Crypto API 本地安全生成随机强密码与易记词组密码，支持自定义字符、批量生成与强度熵值评估 |
| [**JWT 全能工具箱（解码 / 生成 / 验签 / JWS 分析 / 推荐库）**](https://www.microhai.com/zh/tools/jwt-suite) | 集成 JWT 解码、HS/RS/ES 签名生成、签名验证、JWS 安全审计分析与主流语言 JWT 库速查 |

### 日常实用效率 (22)

> 二维码/条形码生成与识别、单位换算、幸运大转盘抽签、秒表倒计时多任务计时、反应速度测试及可视化族谱生成器 — [查看该分类全部工具 →](https://www.microhai.com/zh/category/utilities)

| 工具名称 | 功能简介 |
| :--- | :--- |
| [**二维码生成器（支持 Logo 与配色）**](https://www.microhai.com/zh/tools/qrcode-generator) | 在线生成高清 PNG/SVG 二维码，支持嵌入中心 Logo 图片、自定义前景色/背景色与容错级别 |
| [**二维码在线识别与解码器**](https://www.microhai.com/zh/tools/qrcode-reader) | 上传二维码图片、拖拽文件或直接 Ctrl+V 粘贴截图，毫秒级在本地解析出二维码原始文本或链接 |
| [**全能单位换算器 & 计算器 (15合1)**](https://www.microhai.com/zh/tools/unit-converter) | 支持面积、热量、功率、体积、长度、压力、温度、密度、力、时间、速度、数据存储、角度、子网掩码与科学计算器 |
| [**条形码生成器与识别解码**](https://www.microhai.com/zh/tools/barcode-tool) | 支持 CODE128、EAN-13、EAN-8、UPC-A、CODE39、ITF-14、Codabar 生成高清 PNG/SVG 与截图识别 |
| [**随机大转盘与列表打乱器 (Random Picker Wheel)**](https://www.microhai.com/zh/tools/random-picker-wheel) | 自定义幸运抽奖大转盘、支持抽中移除不重复抽奖、列表随机打乱、多人抽签与随机分组 |
| [**高精度秒表 / 倒计时 / 多组计时器**](https://www.microhai.com/zh/tools/timer-suite) | 集成高精度计圈秒表、带圆环进度与铃声的倒计时/番茄钟，以及支持同时运行的并行多组计时器 |
| [**反应时间测试 (Reaction Time Test)**](https://www.microhai.com/zh/tools/reaction-time-test) | 毫秒级视觉反应速度测试，支持鼠标/触屏点击与空格键，统计 5 轮平均成绩与历史最佳纪录 |
| [**族谱生成器与家庭树构建工具**](https://www.microhai.com/zh/tools/family-tree-builder) | 可视化构建多代际族谱树，支持成员头像、国家地区、在世/已故状态、简介备注、拖拽缩放及导出 PNG/SVG/JSON |
| [**在线尺子与屏幕像素标尺**](https://www.microhai.com/zh/tools/online-ruler) | 实物 1:1 厘米/毫米/英寸在线直尺与 CSS 像素标尺，支持银行卡精准 PPI 校准、横竖切换与 A/B 游标测距 |
| [**在线键盘与鼠标综合测试器（全键无冲 / 微动双击 / 回报率 / CPS）**](https://www.microhai.com/zh/tools/keyboard-mouse-tester) | 支持 104/87/60% 键盘按键检测、NKRO 全键无冲、机械轴连击警告、鼠标五键与滚轮、微动双击故障、Hz 回报率及 CPS 手速测试 |
| [**在线摄像头测试器（分辨率 / 帧率 FPS / 镜像拍照）**](https://www.microhai.com/zh/tools/webcam-tester) | 纯本地检测笔记本/USB摄像头：实测真实分辨率（480p~4K）、实时帧率 FPS、光线亮度评估、镜像九宫格构图与高清截图 |
| [**屏幕坏点、漏光与色彩纯度检测器**](https://www.microhai.com/zh/tools/screen-test) | 全屏检测显示器/手机屏幕坏点暗点、IPS 漏光、阴阳屏、OLED 烧屏抹布屏、32 阶灰阶断层、动态拖影、刷新率 Hz 与亮点修复 |
| [**BMI、BMR 基础代谢与每日热量消耗（TDEE）计算器**](https://www.microhai.com/zh/tools/bmi-tdee-calculator) | 一站式计算 BMI（中国/WHO双标准）、BMR 基础代谢、TDEE 每日总热量消耗、建议饮水量及减脂/增肌三大营养素（蛋白质/碳水/脂肪）克数 |
| [**麦克风录音测试与音量波形检测器**](https://www.microhai.com/zh/tools/microphone-tester) | 纯本地检测电脑/耳机/USB麦克风：实时声波波形与频谱柱状图、dBFS 分贝电平与爆音警告、实时耳返监听及录音回放下载 |
| [**在线打印测试页工具（CMYK 彩打 / 黑白 / 喷头清堵 / 对齐）**](https://www.microhai.com/zh/tools/printer-test-page) | 一键打印标准 A4 / Letter 打印机测试页：支持 CMYK 四色与喷嘴检查、黑白激光碳粉测试、喷墨洗头清堵、单色省墨清洗及对齐校准网格 |
| [**在线标签设计与打印工具（热敏标签 / A4 批量拼版 / 条码二维码）**](https://www.microhai.com/zh/tools/label-designer) | 在线设计并打印商品价签、固定资产二维码贴、快递面单与收纳贴：支持热敏机精准毫米尺寸、A4 纸多份拼版、CODE128 条码与 300 DPI 导出 |
| [**在线番茄钟与白噪音专注器（雨声 / 海浪 / 篝火 / 棕噪音）**](https://www.microhai.com/zh/tools/pomodoro-white-noise) | 25/5/15 分钟自定义番茄工作法计时器 + 6 轨纯本地合成白噪音混音台（细雨/海浪/篝火/微风/棕噪音/粉红噪音）与专注任务清单 |
| [**精确年龄与倒数日计算器（周岁 / 纪念日 / 工作日间隔）**](https://www.microhai.com/zh/tools/age-countdown-calculator) | 精准计算周岁（年月日与实时秒数）、星座生肖、人生万天里程碑、多事件倒数日/恋爱纪念日及两日期间工作日天数与日期加减 |
| [**在线提词器 & 手持应援弹幕灯牌**](https://www.microhai.com/zh/tools/online-teleprompter) | 60fps 丝滑全屏滚屏提词器（镜像/视线引导/摄像头自检）+ 演唱会手持 LED 应援弹幕（霓虹发光/点阵/爆闪/七彩流光/90°横屏） |
| [**宠物年龄折算人类年龄计算器（猫/狗/兔/仓鼠/鹦鹉）**](https://www.microhai.com/zh/tools/pet-age-calculator) | 科学换算狗狗（按小/中/大/巨型犬 + UCSD DNA公式）、猫咪、兔子、仓鼠、豚鼠与鹦鹉的人类年龄，附生命阶段养护建议与完整对照表 |
| [**时间块（Time Blocking）日/周计划表**](https://www.microhai.com/zh/tools/time-blocking-planner) | 支持日视图、7 天周视图与周度统计复盘：内置跨天待办任务池、工作日批量重复排程、单块专注倒计时、今日 3 大目标与整周 .ics/Markdown 导出 |
| [**免费房贷 / 车贷提前还款计算器**](https://www.microhai.com/zh/tools/loan-prepayment-calculator) | 精算房贷、车贷与消费贷提前还款：支持等额本息/等额本金、单次大额提前还+每月多还、缩短年限 vs 减少月供对比、违约金扣除与明细表 CSV 导出 |

---

## 💬 需求建议与问题反馈

如果你希望新增某款纯本地浏览器工具，或发现了任何 Bug，欢迎在本仓库提交 Issue！

- 🐛 [提交新工具需求 / 反馈问题](https://github.com/microhai/local-first-web-tools/issues)
- 🌐 [https://www.microhai.com/zh](https://www.microhai.com/zh)
- 🤖 [llms.txt](https://www.microhai.com/llms.txt)

---

*本仓库为 [MicroHai.com](https://www.microhai.com/zh) 官方工具导航与展示主页，所有工具均可在浏览器免费直接使用。*
