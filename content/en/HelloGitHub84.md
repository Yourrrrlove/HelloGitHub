# HelloGitHub Vol.84
> Passion is the best teacher. **HelloGitHub** inspires your interest in programming!
<p align="center">
    <img src='https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/cover.jpg' style="max-width:100%;"></img>
</p>

## Table of Contents

Click the **「Table of Contents」** icon at the top-right corner to open the navigation and enjoy a better reading experience.

![](https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/catalog.png)

## Content
> **The content of this issue is as follows**｜Updated on the **28th** of each month

### C
1、[linked-list-good-taste](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/mkirchner/linked-list-good-taste)：Linus Torvalds Explains the Argument for Good Coding Taste. In a 2016 TED interview, Linus Torvalds discussed what he considers good coding taste, using an example of two implementations for removing an item from a singly linked list. To remove the first item from a list, one implementation required handling special cases, whereas the other did not, and Linus favored the latter.

2、[rpi4-osdev](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/babbleberry/rpi4-osdev)：A Tutorial for Writing an Operating System for Raspberry Pi 4. This is a tutorial by the CTO of RealVNC on writing an operating system for the bare metal Raspberry Pi 4. The content is divided into 15 chapters, each completing a part of the operating system, with source code and explanations provided.来自 [@刘三非](https://hellogithub.com/user/VhrXCAs7cMxL08W) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/279028703.jpg' style="max-width:80%; max-height=80%;"></img></p>

3、[xdotool](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/jordansissel/xdotool)：Command-line Tool for Simulating Keyboard and Mouse Operations. This project offers the ability to simulate keyboard input, mouse clicks, as well as operations like moving, focusing, and resizing windows through command-line commands, which can be combined with shell to create a DIY input automation tool. It supports systems like Ubuntu, macOS, and FreeBSD.
```
// 打字
xdotool type "HelloGitHub"
// 组合键
xdotool key ctrl+l
// 移动鼠标
xdotool mousemove x y
// 关闭窗口
xdotool selectwindow windowclose
```

### C#
4、[DnsServer](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/TechnitiumSoftware/DnsServer)：A Multi-Platform DNS Service. This is a ready-to-use, zero-configuration, self-hosted DNS server that easily achieves ad-blocking in DNS. It offers a friendly web interface and monitoring, and supports deployment via Docker as well as operating systems such as Windows, Linux, macOS, and Raspberry Pi.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/108726321.png' style="max-width:80%; max-height=80%;"></img></p>

5、[Flow.Launcher](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Flow-Launcher/Flow.Launcher)：A Quick File and Program Launcher for Windows. This is a tool that can make your workflow smoother, similar to Alfred on Mac. It can quickly launch applications, conveniently search for files, bookmarks, and other content, and supports plugin extensions, file previews, system commands, gaming mode, and other features.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/257526212.gif' style="max-width:80%; max-height=80%;"></img></p>

6、[Playnite](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/JosefNemec/Playnite)：Open-source PC Game Management Tool. This is an open-source management and launcher for PC games, supporting synchronization with platforms such as Steam, Epic, GOG, and Battle.net. After importing, the tool automatically fetches game information from IGDB, providing a unified interface for your games. Its code is completely open-source to ensure the safety of your account, and it supports multiple languages, including Chinese, and is compatible with Windows 7 and above operating systems.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/86182490.jpg' style="max-width:80%; max-height=80%;"></img></p>

### C++
7、[dragonfly](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/dragonflydb/dragonfly)：A Memory Database Designed to Replace Redis. It is fully compatible with the APIs of the two most popular in-memory databases, Redis and Memcached, allowing for code-unchanged migration. In terms of performance, it is explosive, with the official claim that a single instance can support tens of millions of QPS, and its throughput is 25 times that of Redis, capable of handling TB-level memory datasets.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/437245741.png' style="max-width:80%; max-height=80%;"></img></p>

8、[moonlight-qt](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/moonlight-stream/moonlight-qt)：A tool that lets you play PC games on almost any device. This project is based on NVIDIA GameStream technology, allowing PC gamers to play 3A titles on iOS, Android, TVs, and more devices through streaming. The process does not require the game to be downloaded and run on the mobile device; it merely receives the game's visuals and sends back control commands. Although the installation process is a bit complex and time-consuming, it is all worthwhile for the sake of playing PC games while lying down. Those who are interested should get started with the setup!

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/131449222.jpg' style="max-width:80%; max-height=80%;"></img></p>

9、[oceanbase](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/oceanbase/oceanbase)：An Indigenous Chinese Distributed Database. This is an enterprise-level distributed relational database from Ant Group, based on the Paxos protocol and distributed architecture. It supports hybrid loads of OLTP and OLAP, featuring high availability, high performance, horizontal scaling, and SQL syntax compatibility.来自 [@lijiayun123](https://hellogithub.com/user/licrT58f763QMR0) 的分享
```
# 下载
bash -c "$(curl -s https://obbusiness-private.oss-cn-shanghai.aliyuncs.com/download-center/opensource/oceanbase-all-in-one/installer.sh)"

# 执行
source ~/.oceanbase-all-in-one/bin/env.sh && obd demo
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/372536760.jpg' style="max-width:80%; max-height=80%;"></img></p>

10、[rr](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/rr-debugger/rr)：Lightweight C/C++ Debugging Tool for Linux. This is a lightweight tool for debugging C/C++ code on Linux, supporting operations such as recording, replaying, and reverse execution, providing an environment for repeated debugging and greatly enhancing debugging efficiency.

### Go
11、[alist](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/AlistGo/alist)：A File Listing Program Supporting Multiple Storage Options. This is a file listing program that supports one-click installation, making it easy to aggregate files scattered everywhere and provide an online file viewing service with ease. It supports various storage methods, including local storage, Alibaba Cloud Drive, Baidu Netdisk, OneDrive, WebDAV, and more.来自 [@孤胆枪手](https://hellogithub.com/user/i1wAIyo6P3NXkxm) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/323965659.png' style="max-width:80%; max-height=80%;"></img></p>

12、[gorss](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Lallassu/gorss)：A Command Line RSS Reader Written in Go. It is simple and easy to use with strong concealment capabilities, supporting features such as content preview, opening links in the browser, custom shortcut keys, themes, and word highlighting.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/209380442.gif' style="max-width:80%; max-height=80%;"></img></p>

13、[gosec](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/securego/gosec)：Go Language Source Code Security Inspection Tool. This project scans the Abstract Syntax Tree (AST) of Go code to check for security issues in the source code, capable of identifying hard-coded passwords, XSS (Cross-Site Scripting), and SQL injection problems, among others.

14、[skopeo](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/containers/skopeo)：Tool for Managing Container Images in Remote Repositories. This tool allows users to view information about container images in remote repositories and perform operations such as copying, synchronization, and deletion. It supports platforms like docker.io, quay.io, and private repositories.
```
$ skopeo inspect docker://registry.fedoraproject.org/fedora:latest
{
    ...
    "Architecture": "amd64",
    "Os": "linux",
    "Layers": [
        "sha256:2a0fc6bf62e155737f0ace6142ee686f3c471c1aab4241dc3128904db46288f0"
    ],
    "LayersData": [
        {
            "MIMEType": "application/vnd.docker.image.rootfs.diff.tar.gzip",
            "Digest": "sha256:2a0fc6bf62e155737f0ace6142ee686f3c471c1aab4241dc3128904db46288f0",
            "Size": 71355009,
            "Annotations": null
        }
    ],
    "Env": [
        "DISTTAG=f37container",
        "FGC=f37",
        "container=oci"
    ]
}
```

15、[yaegi](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/traefik/yaegi)：An Elegant Go Language Interpreter. It is a pure Go interpreter implemented with only the standard library, offering a simple and easy-to-use API. It fully supports the Go programming language specification, as well as the Go 1.18 and 1.19 versions.
```go
package main

import (
	"github.com/traefik/yaegi/interp"
	"github.com/traefik/yaegi/stdlib"
)

func main() {
	i := interp.New(interp.Options{})

	i.Use(stdlib.Symbols)

	_, err := i.Eval(`import "fmt"`)
	if err != nil {
		panic(err)
	}

	_, err = i.Eval(`fmt.Println("Hello Yaegi")`)
	if err != nil {
		panic(err)
	}
}
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/116938442.png' style="max-width:80%; max-height=80%;"></img></p>

### Java
16、[AndroidBitmapMonitor](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/shixinzhang/AndroidBitmapMonitor)：Android Image Memory Analysis Tool. This tool assists developers in quickly identifying whether the images loaded within the app are appropriate, such as checking if the image sizes are suitable, if the cache is cleared in a timely manner, and whether unnecessary images are loaded at the time, it supports both offline and online usage.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/595711802.jpg' style="max-width:80%; max-height=80%;"></img></p>

17、[frostmourne](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/AutohomeCorp/frostmourne)：Auto Home's Open Source Monitoring Platform. A monitoring system constructed with SpringBoot, MyBatis, and XXL-JOB, supporting multiple data sources including ES, HTTP, Prometheus, MySQL/TiDB, as well as various alert message sending methods such as DingTalk, Lark, and SMS.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/228294148.png' style="max-width:80%; max-height=80%;"></img></p>

### JavaScript
18、[koishi](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/koishijs/koishi)：An Easily Extensible Chatbot Framework. It offers a convenient console and plugin marketplace, allowing users without programming knowledge to set up their own chatbot in just minutes, and supports chat platforms such as QQ, Telegram, Discord, and Feishu.来自 [@HBSpy](https://hellogithub.com/user/rIXCy0ZT2L49Ysj) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/225572038.jpg' style="max-width:80%; max-height=80%;"></img></p>

19、[nginx-proxy-manager](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/NginxProxyManager/nginx-proxy-manager)：A Powerful Visual Management Platform for Nginx. It is ready to use with Docker one-click deployment, allowing users to configure and manage the Nginx service online through a web interface, supporting features such as forwarding, redirection, SSL certificates, and advanced configurations.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/114938943.png' style="max-width:80%; max-height=80%;"></img></p>

20、[qinglong](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/whyour/qinglong)：Scheduling Task Management Platform Supporting Multiple Script Languages. This is a platform for executing scheduled scripts, offering online script management, environment variable configuration, log viewing, and millisecond-precision scheduling capabilities. It supports script languages such as Python3, JavaScript, and shell.来自 [@yanyuwangluo](https://hellogithub.com/user/LtSdACHwDTgO2ux) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/347404990.png' style="max-width:80%; max-height=80%;"></img></p>

21、[snk](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Platane/snk)：Eat Up All Your GitHub Contributions. Based on the contribution graph on GitHub, it automatically generates the snake's walking path, eating up all 'green squares' at once, supports generating gif or svg format animations.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/279995113.gif' style="max-width:80%; max-height=80%;"></img></p>

22、[uptime-kuma](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/louislam/uptime-kuma)：A Minimal Uptime Monitoring Tool. This project can be used to monitor the uptime of services. It features an aesthetically pleasing interface, supports one-click deployment via Docker, and includes practical features such as a Chinese user interface, notifications, and multi-status pages.来自 [@浮生若夢](https://hellogithub.com/user/hKmH64UjOdwgCEi) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/382496361.png' style="max-width:80%; max-height=80%;"></img></p>

### PHP
23、[dujiaoka](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/assimon/dujiaoka)：Open Source Vending Machine System Written in PHP. This platform for selling virtual products, such as vouchers or accounts, is implemented using Laravel and Bootstrap. After customers make a payment, the system can automatically dispatch the goods and has integrated multiple payment methods including WeChat, Alipay, and Paypal.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/129852395.png' style="max-width:80%; max-height=80%;"></img></p>

### Python
24、[bar_chart_race](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/dexplo/bar_chart_race)：Dynamic Bar Chart Based on Python. This project allows the creation of bar chart animation for competitions using Python, which dynamically displays data rankings, providing a visual representation of the data change process.来自 [@databook](https://hellogithub.com/user/1qC4w2Ey6bu0fgR) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/259213243.gif' style="max-width:80%; max-height=80%;"></img></p>

25、[dataset](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/pudo/dataset)：A Python Library for Operating Databases with Ease. Built on SQLAlchemy, this library creates a simple data layer that allows querying, writing, and updating data in the database as easily as reading and writing JSON files. It supports SQLite, PostgreSQL, and MySQL databases.
```python
import dataset

db = dataset.connect('sqlite:///:memory:')

table = db['sometable']
table.insert(dict(name='John Doe', age=37))
table.insert(dict(name='Jane Doe', age=34, gender='female'))

john = table.find_one(name='John Doe')
```

26、[GreaterWMS](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/GreaterWMS/GreaterWMS)：Commercial-Grade Open Source Warehouse Management System. This project is a warehouse management system that adopts the post-sales logistics and supply chain processes of Ford Asia Pacific. It provides modules for customer management, order management, inventory management, supplier management, and inventory checking, supporting various devices such as mobile phones and computers.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/266941405.png' style="max-width:80%; max-height=80%;"></img></p>

27、[secretflow](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/secretflow/secretflow)：Ant Financial's Open Source Framework for Privacy Computing. Privacy computing refers to the use of technology to ensure that data is usable by participants without being visible, allowing the data to be circulated and shared without compromising security and privacy. This project is written in Python and supports various mainstream privacy computing technologies including MPC (Multi-Party Computation), FL (Federated Learning), TEE (Trusted Execution Environment), HE (Homomorphic Encryption), and DP (Differential Privacy).来自 [@vector](https://hellogithub.com/user/UBnaedx6ch7KzF4) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/481901631.png' style="max-width:80%; max-height=80%;"></img></p>

28、[shynet](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/milesmcc/shynet)：Minimalist Web Analytics Platform. This is a web analytics platform built on Django that is small, functional, user-friendly, does not track cookies, supports multiple users, and its tracking script is less than 1KB.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/254441446.png' style="max-width:80%; max-height=80%;"></img></p>

### Rust
29、[carbonyl](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/fathyb/carbonyl)：Browser Running in the Terminal. This is a Chromium-based command-line browser that can access web pages in the terminal with a browser-like experience, supporting images, animated images, videos, audio, and other content.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/591273534.gif' style="max-width:80%; max-height=80%;"></img></p>

30、[lsd](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/lsd-rs/lsd)：The Next-Generation ls Command. This project is a tool for viewing directory listings, similar to the ls command, rewritten in Rust, and enhanced with features such as color and icons for a more pleasing visual experience.来自 [@pujianquan](https://hellogithub.com/user/pSBMNFK9ldZLgsa) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/158927812.png' style="max-width:80%; max-height=80%;"></img></p>

31、[typst](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/typst/typst)：A Markup Language Easier to Learn Than LaTeX. This is a new typesetting system based on a markup language. It's more concise and effortless to learn than the well-known LaTeX, and it produces beautiful formulas with the capability of switching various fonts.来自 [@databook](https://hellogithub.com/user/1qC4w2Ey6bu0fgR) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/210702427.png' style="max-width:80%; max-height=80%;"></img></p>

### Swift
32、[DevToysMac](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/DevToys-app/DevToysMac)：Swiss Army Knife for Developers on macOS. This project is the macOS version of DevToys, which can be used immediately after downloading and unzipping without the need for installation. It also implements functions that developers will use daily during development, such as timestamp conversion, Base64 encoding/decoding, and JSON formatting.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/453642201.png' style="max-width:80%; max-height=80%;"></img></p>

33、[wikipedia-ios](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/wikimedia/wikipedia-ios)：Wikipedia's Official Open-Source iOS Client. Wikipedia is an online encyclopedia, and this is its iOS client which supports features such as searching for materials, viewing popular articles, saving articles, multilingual support, and night reading mode.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/13863130.png' style="max-width:80%; max-height=80%;"></img></p>

### AI
34、[Bringing-Old-Photos-Back-to-Life](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)：A Deep Learning Tool for Restoring Old Photos. An open-source deep learning project by Microsoft, which can be used to restore damaged old photos with significant effects.来自 [@lastone](https://hellogithub.com/user/y6WLMKXlxiH1b74) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/274594200.jpg' style="max-width:80%; max-height=80%;"></img></p>

35、[ChatGLM-6B](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/THUDM/ChatGLM-6B)：Tsinghua KEG Open-Source Bilingual Conversational Language Model. This is a Chinese-English bilingual conversational language model based on the GLM architecture with 6.2 billion parameters, which supports inference on a single 2080Ti GPU.
```python
>>> from transformers import AutoTokenizer, AutoModel
>>> tokenizer = AutoTokenizer.from_pretrained("THUDM/chatglm-6b", trust_remote_code=True)
>>> model = AutoModel.from_pretrained("THUDM/chatglm-6b", trust_remote_code=True).half().cuda()
>>> model = model.eval()
>>> response, history = model.chat(tokenizer, "你好", history=[])
>>> print(response)
你好👋!我是人工智能助手 ChatGLM-6B,很高兴见到你,欢迎问我任何问题。
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/613349035.gif' style="max-width:80%; max-height=80%;"></img></p>

36、[DI-engine](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/opendilab/DI-engine)：OpenDILab Open Source Decision AI Platform. This is a general decision-making intelligent engine based on PyTorch, providing developers with over 60 types of algorithms and 40+ types of environments. It supports a variety of customized training and practical decision-making intelligent applications, such as game AI, autonomous driving, and biological sequence prediction.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/382787545.png' style="max-width:80%; max-height=80%;"></img></p>

37、[llama.cpp](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/ggerganov/llama.cpp)：Running LLaMA Big Models on Notebooks. This project achieves smooth operation of LLaMA models on the CPU, supporting macOS, Linux, and Windows operating systems.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/612354784.png' style="max-width:80%; max-height=80%;"></img></p>

### Other
38、[.tmux](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/gpakosz/.tmux)：A Stylish and Universal Tmux Configuration File. Tmux is a terminal multiplexer. This project includes a configuration file that can make Tmux more aesthetically pleasing and user-friendly, along with detailed installation steps.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/5526729.gif' style="max-width:80%; max-height=80%;"></img></p>

39、[ark-pixel-font](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/TakWolf/ark-pixel-font)：Open-source Pan-East Asian Pixel Font. Provides a set of pixel fonts that can be used for the main text in game development, currently completing around 10,000 Chinese characters (12px).

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/366474401.png' style="max-width:80%; max-height=80%;"></img></p>

40、[bpf-developer-tutorial](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/eunomia-bpf/bpf-developer-tutorial)：A Comprehensive Guide to eBPF for Beginners and Intermediate Developers. This tutorial is based on libbpf and CO-RE (Compile Once, Run Everywhere) principles, covering eBPF fundamentals, code examples, and practical applications. It aims to help developers quickly master eBPF through 20 small tools designed for this purpose.

41、[ENGAGE](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/TUDSSL/ENGAGE)：Self-made Battery-less GameBoy. This project achieves a GameBoy that operates without batteries, powered solely by solar energy and game play. It is capable of running Tetris and can save the game's progress when the power runs out, meaning that upon restarting the game, the falling block will be in the same position. Doesn't that sound cool? Everything needed to make this device is included, so interested students can give it a try.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/281764334.png' style="max-width:80%; max-height=80%;"></img></p>

42、[GameDevMind](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/gonglei007/GameDevMind)：Comprehensive Game Development Technology Map. This project presents the skills required for game development through a mind map, including technology stacks, methods, tools, processes, management, and operations.来自 [@gonglei007](https://hellogithub.com/user/dl593RYb28vQBki) 的分享

43、[immersive-translate](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/immersive-translate/immersive-translate)：Immersive Bilingual Web Page Translation Extension. This is a free, non-open-source translation plugin that can display translated text while preserving the original text. It supports more than 10 translation services and is compatible with Chromium, Firefox, Safari, and other browsers. This project was later acquired and is no longer open-source.来自 [@浮生若夢](https://hellogithub.com/user/hKmH64UjOdwgCEi) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/575401013.gif' style="max-width:80%; max-height=80%;"></img></p>

### Book
44、[PPHC](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/johnlui/PPHC)：The Philosophical Principles of High-Concurrent Computing. This book discusses the high-concurrency issues in web services, covering technologies and solutions such as Apache, Nginx, epoll, switches, k8s, databases, distributed systems, and microservice architecture to tackle high-concurrency problems, with content that progresses from simple to complex.来自 [@吕文翰](https://hellogithub.com/user/QkntmXFwR5yS7pr) 的分享

45、[py_regular_expressions](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/learnbyexample/py_regular_expressions)：Mastering Python Regular Expressions: From Beginner to Expert. This book includes hundreds of examples and exercises, covering the use of Python regular expressions from basic to advanced levels.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/84/165224631.png' style="max-width:80%; max-height=80%;"></img></p>



<p align="center">
    <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub83.md">『Previous』</a> | <a href='https://github.com/521xueweihan/HelloGitHub/issues/899'>Feedback</a> | <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub85.md">『Next』</a>
</p>

---
<p align="center">
    👉 <a href='https://hellogithub.com/en/periodical'>Come and recommend an open-source project!</a> 👈<br>
    Search **HelloGitHub** in WeChat to follow our account.<br>
    Stay updated with the latest news and enjoy exclusive giveaways for our fans!
</p>

## Sponsor


<table>
  <thead>
    <tr>
      <th align="center" style="width: 80px;">
        <a href="https://www.compshare.cn/?utm_term=logo&utm_campaign=hellogithub&utm_source=otherdsp&utm_medium=display&ytag=logo_hellogithub_otherdsp_display">          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/ucloud.png" width="60px"><br>
          <sub>UCloud</sub><br>
          <sub>超值的GPU云服务</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://www.upyun.com/?from=hellogithub">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/upyun.png" width="60px"><br>
          <sub>CDN</sub><br>
          <sub>开启全网加速</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://github.com/OpenIMSDK/Open-IM-Server">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/im.png" width="60px"><br>
          <sub>OpenIM</sub><br>
          <sub>开源IM力争No.1</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://apifox.cn/a103hello">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/apifox.png" width="60px"><br>
          <sub>Apifox</sub><br>
          <sub>比 Postman 更强大</sub>
        </a>
      </th>
    </tr>
  </thead>
</table>


## Disclaimer
<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width: 0" src="https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png"></a><br>
This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
