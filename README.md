<!--一下子提供一种思路，欢迎大家发挥 -->

# 概览
“云极”（EPC）是UCloud提供的高性能计算产品，旨在为用户提供基于公有云技术的超高性能算力，以及涵盖数据传输、数据计算、数据可视化处理（即将上线）等一站式的使用体验。

EPC计算节点以UCloud快杰裸金属云主机为底座。其CPU基于2019年推出的AMD EPYC2系列，具有极高性价比。虚拟化架构为“裸金属架构”，基于NVIDIA最新系列 BlueField DPU打造，有效提升宿主机CPU性能稳定性，让快杰裸金属云主机在具备快杰云主机弹性灵活高性能诸多特性的同时，做到了物理机级别的资源隔离。快杰裸金属云主机目前可提供最高规格为CPU 240核心，内存480GB的实例。

EPC支持以下功能：

* 秒级创建计算节点，按需计费
* 自助创建基于SMB 3.1.1的网络文件存储
* 可接入教育网线路，并为EPC计算节点配有专属域名instance_name.edu.ucloud.cn
* 支持在控制台申请盘柜租赁，支持盘柜规格：48TB/RAID5
* 默认支持百度云盘和钉钉网盘客户端定向加速
* 可挂载虚拟的Nvidia Tesla T4 GPU，为图形处理功能加速（即将支持）


#### <center>[厂商对比](#1对比)   |   [最佳实践](#2最佳实践) </center>   

## 1.对比

对比超算中心与云计算服务商，UCloud EPC平台的优势所在。

* [对比云计算服务商](/epc/compareToCloud)
* [对比超算中心](/epc/CompareToHpcCenter)


## 2.最佳实践

在EPC平台上，软件安装与使用的最佳实践

* [VASP](/epc/vasp)
* [OpenFoam](/epc/openfoam)
