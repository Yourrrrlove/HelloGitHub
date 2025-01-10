# HelloGitHub Vol.94
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
1、[genann](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/codeplea/genann)：A Minimal Neural Network Library Written in C Language. This is a lightweight, dependency-free, single-file C language neural network library, which includes a rich set of examples and tests. The code is concise and easy to read, making it suitable as an introductory project for beginners learning about neural networks.来自 [@ziming012](https://hellogithub.com/user/t7lxvuwPRDamU8p) 的分享
```c
#include "genann.h"

/* Not shown, loading your training and test data. */
double **training_data_input, **training_data_output, **test_data_input;

/* New network with 2 inputs,
 * 1 hidden layer of 3 neurons each,
 * and 2 outputs. */
genann *ann = genann_init(2, 1, 3, 2);

/* Learn on the training set. */
for (i = 0; i < 300; ++i) {
    for (j = 0; j < 100; ++j)
        genann_train(ann, training_data_input[j], training_data_output[j], 0.1);
}

/* Run the network and see what it predicts. */
double const *prediction = genann_run(ann, test_data_input[0]);
printf("Output for the first test data point is: %f, %f\n", prediction[0], prediction[1]);

genann_free(ann);
```

### C#
2、[FancyScrollView](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/setchi/FancyScrollView)：Unity Scroll List Plugin. This project utilizes Unity Engine's animation system to customize list slide effects, offering high flexibility. It can be used not only as a scroll list but also as a navigation bar. The project's code structure is well-organized, following standard conventions, and it has a low integration cost, making it easy to use and customize.来自 [@Wu Zheng](https://hellogithub.com/user/zwC03jng8kKhql6) 的分享
```csharp
using UnityEngine;
using UnityEngine.UI;
using FancyScrollView;

class MyCell : FancyCell<ItemData>
{
    [SerializeField] Text message = default;

    public override void UpdateContent(ItemData itemData)
    {
        // 更新内容
        message.text = itemData.Message;
    }

    public override void UpdatePosition(float position)
    {
        // position 是一个介于 0.0 到 1.0 之间的值
        // 可以根据 position 自由控制滚动的外观
    }
}
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/83178374.gif' style="max-width:80%; max-height=80%;"></img></p>

3、[MarkovJunior](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/mxgmn/MarkovJunior)：Markov Chain-based Image Generator. A Markov chain is a mathematical model that exhibits the 'memorylessness' property, meaning that the probability distribution of future states depends only on the present state and not on the sequence of events that preceded it. This project leverages the principle of the Markov chain to generate unique images by simulating state transitions of images, including buildings, mazes, and more.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/498726567.gif' style="max-width:80%; max-height=80%;"></img></p>

### C++
4、[abseil-cpp](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/abseil/abseil-cpp)：Google's Open Source C++ Basic Library. This is a widely used C++ public library within Google, providing a series of high-quality, reliable, and efficient basic modules, including string processing, concurrency, time, STL containers, testing, logging, and other practical functions.来自 [@张程林](https://hellogithub.com/user/PU5imApS4WqLeHZ) 的分享

5、[gpupixel](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/pixpark/gpupixel)：High-performance Cross-platform Real-time Beauty Filter Library. This is a high-performance image and video processing library written in C++11, with built-in GPU-based beauty effect filters that can meet commercial grade standards. It supports effects such as skin smoothing, whitening, face slimming, and eye enlarging, and is suitable for iOS, macOS, and Android platforms.来自 [@Zhaoyou Ge](https://hellogithub.com/user/s3GSnjBQb6X9zwh) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/508234417.gif' style="max-width:80%; max-height=80%;"></img></p>

6、[qtrvsim](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/cvut/qtrvsim)：RISC-V CPU Simulator for Education. This is a RISC-V CPU simulator implemented with Qt, developed by the School of Computing at the Czech Technical University.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/318563203.png' style="max-width:80%; max-height=80%;"></img></p>

### Go
7、[goploy](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/zhenorzz/goploy)：Easy-to-Use Code Publishing Platform. This is a web deployment platform built with Go + Vue.js, capable of one-click deployment, publishing, and rollback of projects. It supports role-based access control, monitoring, second-level timed tasks, Xterm, LDAP, and other features, providing a complete installation guide, making it easy for even beginners to get started.来自 [@zhenorzz](https://hellogithub.com/user/QASc7j3pUxHqgbC) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/161898203.gif' style="max-width:80%; max-height=80%;"></img></p>

8、[listmonk](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/knadh/listmonk)：Open Source Email List and Marketing Platform. This is a ready-to-use email marketing platform that helps you manage email subscribers, create and send emails, and analyze marketing data. It supports viewing email read rates, link click rates, etc., and is suitable for individuals and enterprises with self-hosting.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/193833307.png' style="max-width:80%; max-height=80%;"></img></p>

9、[restic](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/restic/restic)：A Powerful Open Source Backup Tool. This project offers a simple, fast, and secure open-source backup solution. It eliminates the need for complicated configurations, making the backup and recovery process straightforward. The tool adopts an incremental backup strategy, encrypts and compresses backup data to ensure security and save space, supports flexible storage options including local disks and cloud storage. Users can set automatic backup times to ensure that their data is periodically protected.
```
$ restic --repo /tmp/backup backup ~/work
enter password for repository:
scan [/home/user/work]
scanned 764 directories, 1816 files in 0:00
[0:29] 100.00%  54.732 MiB/s  1.582 GiB / 1.582 GiB  2580 / 2580 items  0 errors  ETA 0:00
duration: 0:29, 54.47MiB/s
snapshot 40dc1520 saved
```

10、[vfox](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/version-fox/vfox)：Seamless Tool for Managing Multiple Programming Languages and Versions. This is a cross-platform, universal version management tool that allows for the quick installation and switching of different versions of programming languages through the command line, and supports custom source addresses. Compared to independent version management tools for each language (such as nvm for Node.js, fvm for Flutter, gvm for Groovy, etc.), this project helps developers avoid the cumbersome process of learning and memorizing multiple tools, managing multiple programming language versions with just one tool and a single command.来自 [@Han Li](https://hellogithub.com/user/TV6tBSMzmZUWQqk) 的分享
```
$ vfox c
node -> v20.10.0
java -> v11.0.12
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/729446906.png' style="max-width:80%; max-height=80%;"></img></p>

### Java
11、[1brc](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/gunnarmorling/1brc)：Challenge Java to Achieve the Fastest Speed in Handling One Billion Lines of Text. This is an interesting Java programming challenge that requires developers to write a Java program to read a file containing the temperature values of multiple weather stations (one billion lines), then calculate the minimum, average, and maximum values for each station, and finally output them after sorting by station name. The current record for the fastest speed is under 2 seconds.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/736572328.png' style="max-width:80%; max-height=80%;"></img></p>

12、[automq](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/AutoMQ/automq)：A Truly Cloud-Native Kafka Solution. This project is a new generation of Kafka distribution redesigned based on cloud-native principles. While remaining 100% compatible with Apache Kafka, AutoMQ can provide users with a cost advantage up to 10 times and a hundred times more elasticity advantage. Additionally, it supports partition migration within seconds and automatic traffic rebalancing, solving operational pain points.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/679601811.jpg' style="max-width:80%; max-height=80%;"></img></p>

13、[spring-startup-analyzer](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/linyimin0812/spring-startup-analyzer)：Tool for Optimizing Spring Boot Application Startup Performance. This project collects data during the startup process of a Spring application and generates an interactive analysis report, providing developers with a tool for analyzing the startup performance of Spring applications. Its main features include analyzing startup bottlenecks, handling asynchronous initialization of Spring Beans, and displaying detailed information such as unactivated jar packages, method call counts, and time-consuming statistics.来自 [@linyimin](https://hellogithub.com/user/jfau31oBX46pr8O) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/634983681.png' style="max-width:80%; max-height=80%;"></img></p>

### JavaScript
14、[awesome-hands-control](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/RylanBot/awesome-hands-control)：Tool for Controlling Computer Programs with Gestures. This project enables custom control of computer programs based on gesture recognition, implemented using a pure front-end technology stack. It leverages a pre-trained model (MediaPipe) to recognize gestures, binds specific gestures to computer controls, and finally, allows users to specify the process to be operated, thereby achieving gesture control of computer programs.来自 [@Rylan](https://hellogithub.com/user/c3A7yEZFnvKMulI) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/719241997.png' style="max-width:80%; max-height=80%;"></img></p>

15、[bpmn-js](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/bpmn-io/bpmn-js)：Flowchart Visualization and Editing Component. This project offers an intuitive drag-and-drop interface for creating and editing flowcharts, suitable for building business process management, decision flow visualization, and low-code platforms.来自 [@塔咖](https://hellogithub.com/user/bzJpGyu0IanC6L7) 的分享
```javascript
const xml = '...'; // my BPMN 2.0 xml
const viewer = new BpmnJS({
  container: 'body'
});

try {
  const { warnings } = await viewer.importXML(xml);

  console.log('rendered');
} catch (err) {
  console.log('error rendering', err);
}
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/17592572.gif' style="max-width:80%; max-height=80%;"></img></p>

16、[dockge](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/louislam/dockge)：Aesthetically Pleasing and Easy-to-Use Docker Compose Management Platform. This project offers a web interface for managing docker-compose.yaml files. It is ready to use out of the box, featuring an exquisitely designed interface, and supports interactive editing of compose.yaml files, updating Docker images, as well as operations such as starting, stopping, restarting, and deleting Docker containers.来自 [@猎隼丶止戈reNo7](https://hellogithub.com/user/Ew59HqRWjPe0zZO) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/708775091.gif' style="max-width:80%; max-height=80%;"></img></p>

17、[theatre](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/theatre-js/theatre)：JavaScript Library for Creating Web Animations. This project is a Web animation editor with a graphical user interface that can animate any JavaScript variables. It not only supports animations for objects from three.js or other 3D libraries but also leverages libraries such as React to animate HTML/SVG.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/15393566.gif' style="max-width:80%; max-height=80%;"></img></p>

18、[tiny-rdm](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/tiny-craft/tiny-rdm)：A Lightweight Cross-platform Redis Desktop Client. This project is a Redis desktop client based on WebView2, featuring a compact size and an exquisite interface, while also supporting the Chinese language. It offers various connection methods, segmented loading, slow log viewing, and character encoding conversion display functions, and can be used on Windows, Linux, and macOS systems.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/659115218.png' style="max-width:80%; max-height=80%;"></img></p>

### Kotlin
19、[jingmo](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/hefengbao/jingmo)：An Ancient Chinese Poetry and Idiom Application. It's called 'JingMo', a free Android reading app that contains a wealth of traditional Chinese cultural content, including ancient poems, two-part allegorical sayings, idiom stories, Chinese traditional festivals, tongue twisters, etc. When you first install and open the app, you won't see any content; you need to manually synchronize the data in the settings.来自 [@贺丰宝](https://hellogithub.com/user/2K7jqBdMvyUrOEs) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/682370127.png' style="max-width:80%; max-height=80%;"></img></p>

### Objective-C
20、[Itsycal](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/sfsam/Itsycal)：Adorable Mac Menu Bar Calendar. This is a mini menu bar calendar tool with a cute interface and practical functionalities. It supports displaying/adding events from the system calendar, dark mode, week numbers, shortcuts, and is compatible with macOS 11+ systems.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/50525082.png' style="max-width:80%; max-height=80%;"></img></p>

21、[KeepingYouAwake](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/newmarcel/KeepingYouAwake)：Tool to Prevent Mac from Entering Sleep Mode. This is a small utility for the menu bar that can prevent your Mac from entering sleep mode for a preset period of time or indefinitely, compatible with macOS 10.13 or later.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/25431634.jpg' style="max-width:80%; max-height=80%;"></img></p>

### PHP
22、[akaunting](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/akaunting/akaunting)：Online Accounting Software Designed for Small Businesses and Individuals. This project is an accounting platform built on Laravel+Vue.js+Tailwind CSS+MySQL, providing users with comprehensive accounting and financial functions. It includes expense tracking, cash flow, reporting, and supports mobile adaptation as well as multilingual support.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/95011974.png' style="max-width:80%; max-height=80%;"></img></p>

### Python
23、[DouyinLiveRecorder](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/ihmily/DouyinLiveRecorder)：A Cross-Platform Live Streaming Recording Tool. This project is a multi-platform live stream recording tool implemented based on FFmpeg, which supports cycling live stream recording tasks (watchdog), live status pushing, multi-person recording, watermark removal, and quality selection among other features.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/667354736.png' style="max-width:80%; max-height=80%;"></img></p>

24、[harlequin](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/tconbeer/harlequin)：Simple, Fast, and Aesthetically Pleasing Terminal Database Client. This is a command-line database client with a graphical interface, offering functionalities like database and table navigation, a query editor, result display, and data export. It supports databases such as DuckDB, SQLite, Postgres, MySQL, and more.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/635393461.png' style="max-width:80%; max-height=80%;"></img></p>

25、[khal](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/pimutils/khal)：A Simple and Beautiful Terminal Calendar. This project is a command-line calendar tool written in Python, which supports quick and convenient browsing, adding, and editing of events, as well as synchronizing calendar data.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/12357974.png' style="max-width:80%; max-height=80%;"></img></p>

26、[pyupgrade](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/asottile/pyupgrade)：Tool for Automatically Upgrading Python Code. This is a tool for automatically upgrading Python code to adapt to the syntax of new versions. It supports upgrading to different versions of Python, offers a preview mode to view changes, and provides other related functionalities.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/83462592.png' style="max-width:80%; max-height=80%;"></img></p>

27、[text_blind_watermark](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/guofei9987/text_blind_watermark)：A Python Library for Text Steganography. This project allows embedding secret information into plain text without any changes to the text before and after embedding. Essentially, it's about applying hidden watermarks to text, suitable for scenarios like copyright protection, data leak tracing, and data security, and supports applications such as Chrome on macOS, Apple Notes, WeChat, and DingTalk on macOS and iPhone.
```python
from text_blind_watermark import TextBlindWatermark2

password = 'HelloGitHub'
text = '这句话中有盲水印，你能提取出来吗？'
watermark = 'HelloGitHub'

text_blind_wm = TextBlindWatermark2(password=password)

text_with_wm = text_blind_wm.embed(text=text, watermark=watermark)
print(text_with_wm)
```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/437797089.png' style="max-width:80%; max-height=80%;"></img></p>

### Rust
28、[cmd-wrapped](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/YiNNx/cmd-wrapped)：A Command Line History Analysis Tool Written in Rust. This is a command-line tool that can read your command-line operation history and generate a detailed analysis report. The report includes information such as the active periods of command line in any past year, commonly used commands, and supports shells like Zsh, Bash, and fish.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/737071068.png' style="max-width:80%; max-height=80%;"></img></p>

### AI
29、[AnimateDiff](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/guoyww/AnimateDiff)：Make AI-Generated Images Animated. This is a library designed to create animated images within Stable Diffusion, supporting the conversion of most open-source models into animation generators. It turns originally text-generated images into animated GIFs.来自 [@adoin](https://hellogithub.com/user/HJZMx5VeRfNDQ8z) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/654930782.gif' style="max-width:80%; max-height=80%;"></img></p>

30、[AnyText](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/tyxsspa/AnyText)：Easy DIY Image Text, Customize Your Creative Design. This project offers two modes: text generation and text editing. It can generate text-embedded images based on prompt words and ensure the accuracy of the text. It also supports editing text in uploaded images and regenerating new images. It supports multiple languages such as Chinese, English, Japanese, Korean, and is suitable for scenarios like poster design, logo design, creative doodle, and emoticons.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/692934702.jpg' style="max-width:80%; max-height=80%;"></img></p>

31、[pyvideotrans](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/jianchang512/pyvideotrans)：Open Source Video Translation and Dubbing Tool. This project is capable of translating videos from one language to another and automatically generates and adds subtitles and dubbing in the specified language.来自 [@okaymyworld](https://hellogithub.com/user/Gf8J0xolgYIMUT9) 的分享

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/699432836.png' style="max-width:80%; max-height=80%;"></img></p>

32、[StreamDiffusion](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/cumulo-autumn/StreamDiffusion)：Real-time Interactive AIGC Images. This project can generate AIGC images at an astonishing speed of up to 100 images per second with a single RTX4090 graphics card. It simplifies data handling through stream and batch processing, reduces computational redundancy with the Residual Classifier-Free Guidance (RCFG), improves GPU utilization with a stochastic similarity filter, and achieves parallel processing through optimized I/O queuing. Additionally, it utilizes a variety of model acceleration tools to explosively enhance the speed of AIGC images.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/724635656.gif' style="max-width:80%; max-height=80%;"></img></p>

### Other
33、[gdb-dashboard](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/cyrus-and/gdb-dashboard)：GDB Visual Debugging Interface. This text interface is specifically designed for the GNU Debugger (GDB), supporting modular display of relevant information for the debugging program, making it more intuitive and convenient to debug code. This interface is written in Python and has the features of easy customization and extensibility.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/42191943.png' style="max-width:80%; max-height=80%;"></img></p>

34、[kubernetes-network-policy-recipes](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/ahmetb/kubernetes-network-policy-recipes)：Recipes to Solve K8s Networking Issues with Copy-Paste. This project includes a variety of use cases and example YAML files for Kubernetes network policies, ready for direct copy and use.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/98780162.gif' style="max-width:80%; max-height=80%;"></img></p>

35、[particle-life](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/hunar4321/particle-life)：Particle Life Evolution Game. This project generates complex self-organizing patterns by defining the interactions between particles. The source code is extremely simple, and users can play online to create a variety of interesting patterns.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/523244338.jpg' style="max-width:80%; max-height=80%;"></img></p>

36、[proxypin](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/wanghongenpin/proxypin)：A Cross-platform Free Packet Sniffing Tool. This project is a packet sniffing tool developed using Flutter, capable of intercepting, inspecting, and rewriting HTTP(S) traffic. It supports functions such as QR code connection, domain filtering, and request rewriting, and is suitable for Windows, macOS, Linux, Android, and iOS platforms.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/649662864.png' style="max-width:80%; max-height=80%;"></img></p>

37、[vimwiki](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/vimwiki/vimwiki)：Personal Wiki in Vim. This is a Vim plugin that connects texts in a wiki-like manner, providing better functionality for organizing notes and ideas.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/6698053.png' style="max-width:80%; max-height=80%;"></img></p>

### Book
38、[game-programming-patterns](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/munificent/game-programming-patterns)：  ,Game Programming Patterns,. This book collects the proven, published experiences and patterns in 3A-grade game to solve the problems you encounter in game development.

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img3/master/hellogithub/94/11390832.jpg' style="max-width:80%; max-height=80%;"></img></p>

39、[PDF-Explained](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/zxyle/PDF-Explained)：PDF Explained. This project is the unofficial Chinese translation of the book 'PDF Explained'. It introduces how to construct simple PDF files and covers advanced features such as PDF operators, bookmarks, hyperlinks, annotations, and encryption in depth.



<p align="center">
    <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub93.md">『Previous』</a> | <a href='https://github.com/521xueweihan/HelloGitHub/issues/899'>Feedback</a> | <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub95.md">『Next』</a>
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
