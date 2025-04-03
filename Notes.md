
# Existing Surveys
[1] Evans Owusu, Mohamed Rahouti, Senthil Kumar Jagatheesaperumal, Kaiqi Xiong, Yufeng Xin, Lu Lu and D. Frank Hsu. Online Network DoS/DDoS Detection: Sampling, Change Point Detection, and Machine Learning Methods. IEEE Communications Surveys & Tutorials. 2024.

**[2] Zhiyi Zhang, Guorui Xiao, Sichen Song, R. Can Aygun, Angelos Stavrou, Lixia Zhang and Eric Osterweil. Revealing Protocol Architecture’s Design Patterns in the Volumetric DDoS Defense Design Space. IEEE Communications Surveys & Tutorials. 2024.**

[3] Xiang Chen, Chunming Wu, Xuan Liu, Qun Huang, Dong Zhang, Haifeng Zhou, Qiang Yang and Muhammad Khurram Khan. Empowering Network Security With Programmable Switches: A Comprehensive Survey. IEEE Communications Surveys & Tutorials. 2023.

[4] Rochak Swami, Mayank Dave, Virender Ranga. Software-defined Networking-based DDoS Defense Mechanisms. ACM Computing Surveys. 2019.


# DDoS Attacks in Terrestrial Network


# DDoS Attacks in Satellite Network


# Existing DDoS Defense Mechanism in Terrestrial Network

preventing DDoS: 从源头上阻止 DDoS 攻击；

detecting DDoS: 检测 DDoS 攻击并发出警报，以便触发缓解措施；

mitigating DDoS: 消除或减少 DDoS 攻击造成的损害；

holistic solutions: 结合检测和缓解措施。


## Moving Target Defense

移动目标防御（Moving Target Defense, MTD）是一种新兴的主动防御技术，可以降低漏洞被攻击的风险。 MTD技术介绍: 使攻击面动态化，而不是通过监测，预防，监视，跟踪或补救威胁来防御不变的基础设施。

An SDN-Enabled Proactive Defense Framework for DDoS Mitigation in IoT Networks


## Network Topology Obfuscation

拓扑混淆技术，采用技术手段隐藏网络拓扑信息，使攻击者难以掌握关键链路。

[1] Jinwoo Kim,  Eduard Marin,  Mauro Conti,  and Seungwon Shin. EqualNet: A Secure and Practical Defense for Long-term Network Topology Obfuscation. In NDSS. 2022.

[2] Jinwoo Kim, Jaehyun Nam, Suyeol Lee, Vinod Yegneswaran, Phillip Porras and Seungwon Shin. BottleNet: Hiding Network Bottlenecks Using SDN-Based Topology Deception. IEEE Transactions on Information Forensics and Security. 2021.

[3] Xuyang Ding, Feng Xiao, Man Zhou and Zhibo Wang. Active Link Obfuscation to Thwart Link-flooding Attacks for Internet of Things. In IEEE International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom). 2020

[4] Roland Meier, Petar Tsankov, Vincent Lenders, Laurent Vanbever and Martin Vechev. NetHide: Secure and practical network topology obfuscation. In USENIX Security. 2018.

将NTO应用到卫星互联网面临两大挑战：其一，卫星通信路径天然具备可观测性，难以彻底隐藏；其二，星地网关易成为攻击聚焦点，即使拓扑混淆，关键瓶颈依旧显著。


## SDN/NFV-based

**SDN：** 通过集中式控制器全局管理网络，实时获取数据平面状态并动态下发配置（如流量白名单规则）至交换机。
**NFV：** 用虚拟化技术替代专有中间盒，在通用服务器上以虚拟机或容器形式部署安全功能。

[1] Changhun Jung, Sian Kim, Rhongho Jang, David Mohaisen, DaeHun Nyang. A Scalable and Dynamic ACL System for In-Network Defense. In CCS. 2022.

[2] **Seyed K. Fayaz, Yoshiaki Tobioka, Vyas Sekar and Michael Bailey. Bohatei: Flexible and Elastic DDoS Defense. In USENIX Security. 2015.**

[3] Hongliang Zhou, Xiaohua Jia, Jiangang Shu and Lei Zhou. CoWatch: Collaborative Prediction of DDoS Attacks in Edge Computing with Distributed SDN. In GLOBECOM. 2021.

[4] Xiangrui Yang, Biao Han, Zhigang Sun and Jinfeng Huang. SDN-based DDoS Attack Detection with Cross-Plane Collaboration and Lightweight Flow Monitoring. In GLOBECOM. 2017.

[5] Dingwen Hu, Peilin Hong and Yixin Chen. FADM: DDoS Flooding Attack Detection and Mitigation System in Software-Defined Networking. In GLOBECOM. 2017.

[6] Yixin Chen, Jianing Pei and Defang Li. DETPro: A High-Efficiency and Low-Latency System Against DDoS Attacks in SDN Based on Decision Tree. In ICC. 2019.

[7] Chafika Benzaïd, Mohammed Boukhalfa and Tarik Taleb. Robust Self-Protection Against Application-Layer (D)DoS Attacks in SDN Environment. In WCNC. 2020.

[8] Iman Akbari, Ezzeldin Tahoun, Mohammad A. Salahuddin, Noura Limam and Raouf Boutaba. ATMoS: Autonomous Threat Mitigation in SDN using Reinforcement Learning. In NOMS. 2020.

[9] Bing Wang, Yao Zheng, Wenjing Lou, Y. Thomas Hou. DDoS attack protection in the era of cloud computing and Software-Defined Networking. Computer Networks. 2015. (2014 ICNP)

[10] Ashfaq Ahmad Najar and S. Manohar Naik. Cyber-Secure SDN: A CNN-Based Approach for Efficient Detection and Mitigation of DDoS attacks. Computers & Security. 2024.

[11] Ramin Fadaei Fouladi, Orhan Ermiş and Emin Anarim. A DDoS attack detection and countermeasure scheme based on DWT and auto-encoder neural network for SDN. Computer Networks. 2022.

[12] Hongliang Zhou, Yifeng Zheng, Xiaohua Jia and Jiangang Shu. Collaborative prediction and detection of DDoS attacks in edge computing: A deep learning-based approach with distributed SDN. Computer Networks. 2023.

[13] Juan Wang, Ru Wen, Jiangqi Li, Fei Yan, Bo Zhao and Fajiang Yu. Detecting and Mitigating Target Link-Flooding Attacks Using SDN. IEEE Transactions on Dependable and Secure Computing. 2019.

[14] Jing Zheng, Qi Li, Guofei Gu, Jiahao Cao, David K. Y. Yau and Jianping Wu. Realtime DDoS Defense Using COTS SDN Switches via Adaptive Correlation Analysis. IEEE Transactions on Information Forensics and Security. 2018.


但SDN架构本身也存在流表攻击、恶意应用、通信接口劫持等脆弱点


虽然基于SDN（软件定义网络）的DDoS防御方案在支持SDN设备的网络环境中部署方便，但在面对跨域、分布式的大规模DDoS攻击时会遇到一些明显的挑战，具体包括以下两个方面：

**控制平面风险：** SDN的一个重要特点是控制与转发的分离，网络控制逻辑由集中式的控制器掌握。但正因为这种集中化的架构，控制器本身就变成了一个极具吸引力的攻击目标。攻击者可以将DDoS攻击直接对准控制器，导致其过载或失效，从而瘫痪整个网络的控制与管理能力。因此，需要额外的机制来检测、预防和缓解针对控制器的DDoS攻击（如冗余控制器部署、流量限制机制、异常检测等）。

Rowan Klöti, Vasileios Kotronis and Paul Smith. OpenFlow: A security analysis. In ICNP. 2013.

Seungwon Shin, Vinod Yegneswaran, Phillip A. Porras, Guofei Gu. AVANT-GUARD: scalable and vigilant switch flow management in software-defined networks. In CCS. 2013.

Ping Dong, Xiaojiang Du, Hongke Zhang, Tong Xu. A detection method for a novel DDoS attack against SDN controllers by vast new low-traffic flows. In ICC. 2016.

**跨域能力不足：** SDN的部署往往是局部的、在某一管理域内部，这就限制了它应对跨多个网络或自治系统的大规模DDoS攻击的能力。DDoS攻击往往是跨域的，攻击流量源于多个不同的区域或网络（比如使用僵尸网络Mirai发起攻击）。这类攻击的流量可能远远超出单个SDN域的防御处理能力。如果防御机制不能跨域协同部署，就难以全面覆盖攻击路径，容易形成防御盲区。

Manos Antonakakis, Tim April, Michael Bailey, Matthew Bernhard, Elie Bursztein, Jaime Cochran, Zakir Durumeric, J. Alex Halderman, Luca Invernizzi, Michalis Kallitsis, Deepak Kumar, Chaz Lever, Zane Ma, Joshua Mason, Damian Menscher, Chad Seaman, Nick Sullivan, Kurt Thomas and Yi Zhou. Understanding the Mirai Botnet. In USENIX Security. 2017.


## Programmable Switches-based

可编程交换机已成为DDoS检测和缓解的一个有前景的平台。与仅执行数据包转发的传统交换机不同，可编程交换机采用新型可编程ASIC，可支持额外的计算（如DDoS相关的计算，包括数据包过滤、速率限制和哈希表处理），并且能够在每个数据包的基础上执行这些操作，同时保持高线速保障。

与传统固定功能交换机不同，其允许管理员通过P4等网络编程语言直接定义数据平面逻辑。在以下四方面显著超越（Middlebox-based schemes and SDN/NFV-based schemes）：

1. **易于管理**：可编程交换机提供了支持网络编程语言（如P4），允许管理员在数据平面程序中自定义安全功能，并通过完整的编译工具链将这些程序部署到交换机。在运行时，可编程交换机为管理员或集中式SDN控制器提供了一套高级交换机管理API，用于动态调整其数据包处理行为。这些工具和API简化了安全功能的管理和配置。

2. **低成本**：可编程交换机的价格相对适中。根据市场数据，每台可编程交换机仅需数千美元，远低于中间盒的成本。其价格也与通用服务器相当。

   John Sonchack, Oliver Michel, Adam J. Aviv, Eric Keller and Jonathan M. Smith. Scaling Hardware Accelerated Network Monitoring to Concurrent and Dynamic Queries With *Flow. In USENIX ATC. 2018.

   Yu Zhou, Chen Sun, Hongqiang Harry Liu, Rui Miao, Shi Bai, Bo Li, Zhilong Zheng, Lingjun Zhu, Zhen Shen, Yongqing Xi, Pengcheng Zhang, Dennis Cai, Ming Zhang and Mingwei Xu. Flow Event Telemetry on Programmable Data Plane. In SIGCOMM. 2020.

3. **高灵活性**：得益于自上而下的可编程性，可编程交换机被视为高度灵活的设备。管理员能够动态更改目标交换机上运行的安全功能，或通过新程序重新配置可编程交换机以添加新安全功能。

4. **高性能**：可编程交换机确保每个安全功能均以线速数据包处理性能运行（最高可达数十Tbps）。这种高性能在性能上实现了数量级提升，不仅远超基于SDN/NFV的安全功能，甚至超过了现有中间盒（其吞吐量通常仅数百Gbps [35][36][37][38][39][40][41][42]）。此外，可编程交换机采用流水线式数据包处理范式，将最坏情况下的延迟限制在几微秒内。

   https://www.barefootnetworks.com/technology/#tofino

[1] Sophia Yoo, Xiaoqi Chen and Jennifer Rexford. SmartCookie: Blocking Large-Scale SYN Floods with a Split-Proxy Defense on Programmable Data Planes. In USENIX Security. 2024.

[2] Huancheng Zhou and Guofei Gu. Cerberus: Enabling Efficient and Effective In-Network Monitoring on Programmable Switches. IEEE S&P. 2024.

[3] Chris Misa, Ramakrishnan Durairajan, Arpit Gupta, Reza Rejaie and Walter Willinger. Leveraging Prefix Structure to Detect Volumetric DDoS Attack Signatures with Programmable Switches. IEEE S&P. 2024

[4] Huancheng Zhou, Sungmin Hong, Yangyang Liu, Xiapu Luo, Weichao Li and Guofei Gu. Mew: Enabling Large-Scale and Dynamic Link-Flooding Defenses on Programmable Switches. IEEE S&P. 2023.

[5] Guangmeng Zhou, Zhuotao Liu, Chuanpu Fu, Qi Li, and Ke Xu. An Efficient Design of Intelligent Network Data Plane. In USENIX Security. 2023.

[6] Albert Gran Alcoz, Martin Strohmeier, Vincent Lenders and Laurent Vanbever. Aggregate-based congestion control for pulse-wave DDoS defense. In SIGCOMM. 2022.

[7] Zaoxing Liu, Hun Namkung, Georgios Nikolaidis, Jeongkeun Lee, Changhoon Kim, Xin Jin, Vladimir Braverman, Minlan Yu and Vyas Sekar. Jaqen: A High-Performance Switch-Native Approach for Detecting and Mitigating Volumetric DDoS Attacks with Programmable Switches. In USENIX Security. 2021.

[8] Jiarong Xing, Wenqing Wu and Ang Chen. Ripple: A Programmable, Decentralized Link-Flooding Defense Against Adaptive Adversaries. USENIX Security. 2021.

[9] Diogo Barradas, Nuno Santos, Lu ́ıs Rodrigues, Salvatore Signorello†, Fernando M. V. Ramos and Andr ́e Madeira. FlowLens: Enabling Efficient Flow Classification for ML-based Network Security Applications. NDSS. 2021.

[10] Menghao Zhang, Guanyu Li, Shicheng Wang, Chang Liu,  Ang Chen, Hongxin Hu, Guofei Gu, Qianqian Li, Mingwei Xu and Jianping Wu. Poseidon: Mitigating Volumetric DDoS Attacks with Programmable Switches. In NDSS. 2020.


其他

Jinzhu Yan, Haotian Xu, Zhuotao Liu, Qi Li, Ke Xu, Mingwei Xu, and Jianping Wu. Brain-on-Switch: Towards Advanced Intelligent Network Data Plane via NN-Driven Traffic Analysis at Line-Speed. In NSDI. 2024.

LightGuardian: A Full-Visibility, Lightweight, In-band Telemetry System Using Sketchlets. In NSDI. 2021.

HeteroSketch: Coordinating Network-wide Monitoring in Heterogeneous and Dynamic Networks. In NSDI. 2022.

SketchLib: Enabling Efficient Sketch-based Monitoring on Programmable Switches. In NSDI. 2022.

Patronum: In-network Volumetric DDoS Detection and Mitigation with Programmable Switches. In ESORICS. 2024.



# Existing DDoS Attack Strategies in Satellite Network



[1] Giacomo Giuliari, Tommaso Ciussani, Adrian Perrig, and Ankit Singla. ICARUS: Attacking low earth orbit satellite networks. In USENIX Annual Technical Conference (USENIX ATC). 2021.

[2] StarMaze: Ring-based Attack in Satellite Internet Constellations. In 2024 IEEE/ACM 32nd International Symposium on Quality of Service (IWQoS). 2024.

[3] DoSat: A DDoS Attack on the Vulnerable Time-Varying Topology of LEO Satellite Networks. In International Conference on Applied Cryptography and Network Security (ACNS). 2024.



# Existing DDoS Defense Strategies in Satellite Network

[1] Yibo Lian, Tao Zhang, Changqiao Xu, Wei Dong, Minrui Xu and Zhenyu Xiahou. Deep Reinforcement Learning-Based Moving Target Defense for Multicast in Software-Defined Satellite Networks. In IEEE International Conference on Communications (ICC). 2024.

[2] Sara Salim, Nour Moustafa, Mohamed Hassanian, David Ormod and Jill Slay. Deep-Federated-Learning-Based Threat Detection Model for Extreme Satellite Communications. IEEE Internet of Things Journal. 2024.

[3] Wei Guo, Jin Xu, Yukui Pei, Liuguo Yin, Chunxiao Jiang and Ning Ge. A Distributed Collaborative Entrance Defense Framework Against DDoS Attacks on Satellite Internet. IEEE Internet of Things Journal. 2022.

[4] Mengke Wan, Jiang Fang, Chen Guo, Liru Geng, Yinlong Liu and Wei Ma. A Federated Learning-Based Intrusion Detection System for Satellite-Terrestrial Integrated Networks. In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). 2025




其他

Yongyi Cao, Hao Jiang, Yuchuan Deng, Jing Wu, Pan Zhou and Wei Luo. Detecting and Mitigating DDoS Attacks in SDN Using Spatial-Temporal Graph Convolutional Network. IEEE Transactions on Dependable and Secure Computing. 2022.

Aggregate-Based Congestion Control for Pulse-Wave DDoS Defense. In SIGCOMM. 2022.

Chuanpu Fu, Qi Li, Meng Shen and Ke Xu. Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns. In CCS. 2024.

Guanglin Duan, Qing Li, Zhengxin Zhang, Dan Zhao, Guorui Xie and Yuan Yang. DNSGuard: In-Network Defense Against DNS Attacks. IEEE Transactions on Dependable and Secure Computing. 2024

Ziming Zhao, Zhuotao Liu, Huan Chen, Fan Zhang, Zhuoxue Song and Zhaoxuan Li. Effective DDoS Mitigation via ML-Driven In-Network Traffic Shaping. IEEE Transactions on Dependable and Secure Computing. 2024

Ziming Zhao, Zhaoxuan Li, Zhuoxue Song, Fan Zhang and Binbin Chen. RIDS: Towards Advanced IDS via RNN Model and Programmable Switches Co-Designed Approaches. In INFOCOM. 2024
