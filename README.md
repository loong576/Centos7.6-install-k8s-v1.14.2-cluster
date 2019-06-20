# Centos7.6部署k8s(v1.14.2)集群
Centos7.6部署k8s(v1.14.2)集群

本文通过kudeadm方式在centos7.6上安装kubernetes v1.14.2集群(目前centos和kubernetes都为最新版)，共分为五个部分：
<br>
**一、Docker安装；
<br>
二、k8s安装准备工作；
<br>
三、Master节点安装；
<br>
四、Node节点安装；
<br>
五、Dashboard安装；
<br>
六、集群测试。**
<br>
<br>

<br>

**环境说明:**

| 主机名 | 操作系统版本 | ip | docker version | kubelet version | kubeadm version | kubectl version | flannel version | 备注 |
| :------: | :------:  | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
| master | Centos 7.6.1810 | 172.27.9.131 |Docker 18.09.6 | V1.14.2 | V1.14.2 | V1.14.2 | V0.11.0 | master主机 |
| node01 | Centos 7.6.1810 | 172.27.9.135 |Docker 18.09.6 | V1.14.2 | V1.14.2 | V1.14.2 | V0.11.0 | node节点 |
| node02 | Centos 7.6.1810 | 172.27.9.136 |Docker 18.09.6 | V1.14.2 | V1.14.2 | V1.14.2 | V0.11.0 | node节点 |


<br> 
<br>

**Centos7.6安装详见：**[Centos7.6操作系统安装及优化全纪录 ](https://blog.51cto.com/3241766/2398136)
<br>
<br>

**本文链接：**[Centos7.6部署k8s(v1.14.2)集群 ](https://blog.51cto.com/3241766/2405624)
