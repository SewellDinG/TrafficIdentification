## 基础知识

☆1、[SSL/TLS、对称加密和非对称加密和TLSv1.3](https://tinychen.com/200602-encryption-intro)

- SSL/TLS发展历史，对称与非对称加密。
- TLS v1.2和v1.3的握手过程及主要不同。

2、[PKI/CA工作原理及架构](https://www.jianshu.com/p/c65fa3af1c01)

- 数字签名、数字证书、PKI/CA体系。

## 工具

1、[初探加密流量识别](https://www.secrss.com/articles/14298)：Cisco开源的[Joy](https://github.com/cisco/joy)。

- 加密流量识别原型：数据集、提取特征与预处理、模型训练测试、特征可视化。
- 特征提取：数据流元特征、数据包包长序列、数据包时间间隔特征、数据包字节分布特征、数据包TLS特征。
- 模型选择：受数据集大小影响；输入特征影响，时间序列+报头、Payload+报头、统计特征。

2、[流量分析的瑞士军刀：Zeek](https://s0docs0zeek0org.icopy.site/en/current/intro/index.html)：一款集成了TCPDump（抓包）、Wireshark（流量分析）、Snort（入侵检测）、SYSLOG（日志记录）、Python/Perl（有灵活抽象的数据结构，支持脚本自定义处理）功能的网络流量分析利器。

