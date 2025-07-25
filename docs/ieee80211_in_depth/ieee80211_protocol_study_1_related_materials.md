# 802.11协议精读1：学习资料整理

转载自: [802.11协议精读1：学习资料整理 - 知乎](https://zhuanlan.zhihu.com/p/20716157)

## 序言

笔者从研究生开始，一直在做有关802.11协议的相关内容。故在此将笔者学习期间收集了较好的学习资料进行整理，并记录如下。该整理按照由潜至深的顺序，可以根据个人不同的情况，进行选择。（PS：其中有的附上的下载链接均为网上搜索而言，仅为学习使用而已，有的资料可能不是最新版，所以还是购买原版书好一些)。

PS：这篇文章是较早的版本，目前建议可以直接关注github项目：https://github.com/fzxy002763/Wi-Fi_Study_Public。

## 综合类

### 1.CWNP系列教材

CWNP（CWNP）是一个无线方向的认证项目，其教材是比较适合初学802.11协议的人使用的，其主要是避免了大量的数学工程，基本是从工程师应用的角度来编写。按照其官网所描述，CWNP的认证包含：CWTS，CWNA，CWSP，CWDP，CWAP，CWNE，CWNT。其中CWNA的教材最为适合初学，且也有中文的翻译版。其余CWSP，CWDP等教材适合进阶一步阅读。部分的教材（包含了CWTS，CWNA，CWSP，CWDP，CWAP）可以在【Download Wireless Networking Study Guides】该链接下载，我也打包了一份【CWNP系列教材（整合版）】。

### 2.802.11权威指南（O'Reilly）

802.11权威指南是早期的一本802.11的专著，与协议的贴合度很高（个人感觉更接近于2007版本的802.11协议），不过缺点在于对于一些当前最新的802.11协议缺乏描述，毕竟该书的初版的时候，802.11n还是处于草案阶段。整体而言，整本书的内容还是比较丰富的，而且也包含了很多细节的部分（如物理层细节），同时也避免了很多公式推导。目前收集到《802.11权威指南》的资源如下，【802.11权威指南】。

### 3.802.11 Survival Guide（O'Reilly）

由于802.11权威指南中没有专门讨论过802.11n和802.11ac，所以后面O'Reilly还有两本书专门说明有关802.11n和802.11ac的内容，包含：802.11n A Survival Guide与802.11ac A Survival Guide。粗读一遍，感觉协议的很多部分（包含物理层和MAC层）还是描述的很详细的，其相应的资源整理如下，【802.11 Survival Guide（OReilly)】。

### 4.Next Generation Wireless LANs（Cambridge）

Cambridge的两本有关802.11的专著：Cambridge.Next Generation Wireless LANs.802.11n与Cambridge.Next Generation Wireless LANs.802.11n and 802.11ac，感觉是两本描述802.11的书籍中最为细致的两本书，也同时感觉最为权威的两本书，其中很多物理层细节与MAC层细节都只有在这本书中可以找到（尤其是802.11的物理层部分）。如果打算详细研究802.11协议的话，非常建议读下这本书，其中后者是新版（包含了802.11n和802.11ac的主要内容），所以更加推荐阅读。其相应的资源整理如下，【Next Generation Wireless LANs (Cambridge)】。

其实有关Cambridge.Next Generation Wireless LANs.802.11n，该书国内也存在翻译版，其资源整理如下，【下一代无线局域网：802.11n的吞吐率、强健性和可靠性】。

### 5.WAPI协议

WAPI和802.11的关系有兴趣可以自行搜索。从学习的角度上而言，WAPI可以当做中文的802.11（即802.11的早期版本）。比较适合早期阅读802.11协议原版，毕竟原协议内容，写法之类都和一般书本不同，所以还是中文的资料好适应一些。其相应的资源整理如下，【WAPI】。

### 6.802.11协议（2007版与2012版）

802.11协议有很多个版本，包含了众所周知的是802.11a/b/g/n/ac这些，其余还有802.11r/802.11k/802.11s等等很多协议版本，以及还存在协议的演化，比如802.11ae/802.11aa这些。其中802.11的2007版和2012版算是一个协议整合版，其中802.11-2012版包含了07版以及802.11n，802.11k，802.11r等相应的内容，所以适合详细阅读802.11协议使用，不过2012版中没有包含802.11ac/ad，802.11ah，802.11ae，802.11aa等相关的内容，所以这些新协议还需要读协议的分支。其中07版和12版的相应资源整理如下，【IEEE 802.11 2007/2012】。

## 安全类

### 1.802.11 security（O'Reilly）

O'Reilly也有一本关于802.11安全的专著，这本书目前还没有读完，整体感觉还是比较好的。相应资源如下，【802.11 security（OReilly）】。

### 2.Real 802.11 Security - Wi-Fi Protected Access and 802.11i

这本书老早之前读过一次，总体感觉还是可以的，该书主要讨论的是802.11i的内容，不过由于出版的较早，所以有些内容有些老了。相应的资源如下，【Real 802.11 Security - Wi-Fi Protected Access and 802.11i】。

## 设计类

### 1.IEEE 802.11 Tutorial（Berkeley）

这份材料是bekerly那里出的较早期的IEEE 802.11 Tutorial，实际应该放在综合类中的。不过这份资料中的很多流程图描绘的还不错，是从整个协议执行的机制上所述，且都做了一定的简化，所以也是不错的材料。相应的资源如下，【IEEE 802.11 Tutorial (Berkeley)】。

### 2.Wi-Fi：802.11 物理层和发射机测量概述

这份资料是泰克公司公开的资料，实际上是将802.11物理层部分加以总结出的一份文档，用来快速学习802.11物理层的有关知识是很适合的，而且其中的内容也是从测试厂家的角度而写，相比一般书本的知识，这些内容更加偏实际一些。相应的资源如下，【Wi-Fi：802.11物理层和发射机测量概述】。

### 3.802.11物理层规范海报

这一份泰克这份海报，非常贴切802.11协议，其中很多物理层的内容，以及信道分配，5G可用信道有哪些，都有总结，作为速查非常方便。相应的资源如下，【802.11物理层规范海报】

### 4.通信新读

实际上这份资料与802.11的关系不是很大，但是该书是一本的用来学习通信知识不错的书。适合初学者学习通信的理论知识，与大话系列不同，这本书还是很注重理论知识的。该书没有完整的电子版，只收集到试读的部分（笔者不少资料还是读的纸质版），相应的资源如下，【通信新读（试读）】。

### 5.OFDM for wireless communications systems

这本书是一份OFDM的专题书，且内容较短且精，适合作为了解OFDM基本原理后，不断重新深入理解OFDM原理所阅读，其中有些细节还是比较不错的。相应的资源如下，【OFDM for wireless communications systems】。

### 6.Radio Frequency Propagation Made Easy

802.11中的信道模型实际上描述的内容并不多，故需要一些有关射频传播模型的背景知识才好深入理解一些，上面这份教材讲的深浅适中，对于理解802.11协议中的内容是足够的了。相应的资源如下，【Radio Frequency Propagation Made Easy】

## 仿真类

### 1.MIMO-OFDM Wireless Communications with MATLAB

该书是一篇有关MIMO-OFDM理论以及仿真的综合书，书中夹杂描述了一些802.11情况下的信道模型，物理层模型之类，由于当前802.11的主流技术是基于MIMO-OFDM的，且如果需要真正学习802.11相应的通信知识，还是多接触些物理层和数学为好，该书的理论都有配以仿真，所以很适合学习。相应的资源，包含原书和源码如下，【MIMO-OFDM Wireless Communications with MATLAB】。

### 2.NS2仿真实验-多媒体与无线网络

柯志恒老师的书，很多学习NS2的人一开始都学习过，这里收集了下书的电子版以及源码，相应的资源如下，【NS2仿真实验-多媒体与无线网络 】。

### 3.The NS2 Manual

有关NS2的资料实际上是非常多的，笔者曾经用过一段时间NS2做802.11仿真，当时顺着这份材料学习了下，所以记录下。NS2有关802.11的资料还是非常多的，每个人可以根据自己的需求寻找资料。该资源如下，【The NS2 Manual】。

### 4.Implementation of IEEE 802.11 Physical Layer Model in NS3

这份材料的原题目比较长（Study and Implementation of IEEE 802.11 Physical Layer Model in YANS (Future NS-3) Network Simulator），主要是讨论如何在NS3中模拟802.11物理层的模型。该资料中，提供了很多不同种类的物理层模型，以及参数，由于笔者在做仿真的时候，需要采用一些跨层仿真的方法，从这份资料里面算是得到不少启发，故记录一下。该资料相应的资源如下，【Implementation of IEEE 802.11 Physical Layer Model in NS3】。

## 实现类

### 1.深入理解Android：WiFi模块 NFC和GPS卷

这本书是朋友推荐的一本书，当时是为了学习802.11安全协议的部分。由于直接从openwrt的角度来分析802.11源码的书很少，所以这本从andriod的角度分析源码的书也是挺好的，相应的资源如下，【深入理解Android：WiFi模块 NFC和GPS卷】。

### 2.基于XILINX FPGA的OFDM通信系统基带设计

该书是比较完整的叙述了802.11a的基带在FPGA上实现的书，虽然调源码的时候发现可能会发现有一些错误，但是总体上而言，这本书的知识结构也是较为完整的，笔者对于802.11在FPGA实现的英语材料没有怎么阅读过，故从这本书上也算获取了不少知识，总体感觉也是不错的。该书以及其源码的资源如下，【基于XILINX FPGA的OFDM通信系统基带设计】。

### 3.Linux Kernel Networking

该书主要是描述了Linux内核中网络的实现部分，其第12章具体就是对应无线模块。由于描述Linux内核中无线模块资料比较少，所以这本书也是比较推荐的，只不过对于细节部分，该书描述不是特别细致，不过总体还是不错的。该书以及其源码的资源如下，【Linux Kernel Networking 】。

### 4.Linux Wi-Fi open source drivers-mac 802.11

该材料比较完整的叙述了从kernel到802.11驱动底层的一个函数调用过程，用来学习802.11具体驱动过程是一份比较好的材料。该资料的资源如下，【Linux Wi-Fi open source drivers-mac 802.11】。

### 5.通信IC设计

这份本书内容感觉目前是除了MATLAB 2016a/b代码以外，对802.11物理层最为详尽描述的材料了（在该书下册）。该书也有附带的相应代码。该书目前只有纸质版，有可以自行阅读。

## 历史类

1. The Innovation Journey of Wi-Fi (The Road to Global Success)

这一份是描述802.11协议诞生以来到被广泛推广这一段时间以来的大致发展历史，其第二作者Vic Hayes在1990-2000年期间作为IEEE 802.11的主席，对这一块历史了解应该是非常深入的。该资料的资源如下，[The Innovation Journey of Wi-Fi (The Road to Global Success)](http://download.csdn.net/detail/fzxy002763/9752224)