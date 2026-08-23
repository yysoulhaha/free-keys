# AI模型网关

多供应商多 Key 聚合网关 · model: auto 自动路由 · 会员激活码制

## 下载（Windows）

前往 [Releases](../../releases) 下载最新安装包：

- [AI-Gateway-Setup-1.0.0-x64.exe](../../releases/download/v1.0.0/AI-Gateway-Setup-1.0.0-x64.exe)（33MB）

## 特性

- **多供应商聚合**：nvidia / OpenAI 兼容上游统一接入，多 Key 轮询与冷却
- **自动路由**：model: auto 按可用性智能分发，故障自动切换
- **会员体系**：VIP / SVIP 激活码激活专属模型池，云端密池加密下发
- **开箱即用**：内置 nvidia 默认供应商，自带 Python 运行时，无需安装任何环境
- **管理面板**：模型管理、探活监控、用量统计、主题切换

## 安装

1. 双击安装包，默认安装到 C 盘（可自选目录）
2. 桌面快捷方式启动，托盘常驻
3. 管理面板地址：<http://127.0.0.1:8670>

## 接入

任何 OpenAI 兼容客户端均可接入：

\Base URL: http://127.0.0.1:8670/v1
API Key:  123
Model:    auto
\
> 本仓库同时承载会员模型池的加密清单（\*.enc.json），仅凭激活码可解。
