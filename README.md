# k3s-platform-gitops

本仓库用于管理 openEuler + k3s 基础环境服务分系统的 GitOps 配置。

## 已部署模块

- openEuler 操作系统
- k3s 三节点集群
- k3s 内置 containerd 容器运行时
- OpenEBS LocalPV Hostpath 存储系统
- Docker Registry v2 本地镜像仓库
- RabbitMQ 消息队列
- EMQX 实时通信组件
- Spark Kubernetes Operator 分布式计算框架
- Prometheus + Grafana + Alertmanager 系统监控模块
- Argo CD GitOps 自动化部署模块

## 目录说明

- registry：本地 Docker Registry 配置
- messaging：RabbitMQ 与 EMQX 配置
- monitoring：kube-prometheus-stack values 配置
- compute：Spark Operator 相关配置
- argocd-apps：Argo CD Application 配置
- scripts：辅助脚本
