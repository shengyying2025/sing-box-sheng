# 📦 sing-box-sheng

> 基于 **sing-box-yg** 的精简与安全化改造版本  
> 面向 **个人 VPS 使用**，强调 **透明、可控、可审计**

---

## ⚠️ 重要说明（请先阅读）

本项目 **并非原始项目**，而是基于以下仓库进行的 **个人化改造与精简**：

- 原项目地址：  
  https://github.com/yonggekkk/sing-box-yg  
- 原作者：**yonggekkk（甬哥）**

本仓库 **保留核心一键脚本能力**，同时 **删除与个人使用无关或存在安全风险的内容**。

---

## 🔐 本仓库的设计原则

- ✅ 面向 **个人 VPS**，非机场 / 非多用户  
- ✅ 保留 **sing-box 一键部署脚本（sb.sh）**  
- ❌ 不包含 GitHub Actions 自动 SSH  
- ❌ 不包含未知来源的预编译二进制  
- ❌ 不包含 serv00 / 免费主机专用逻辑  
- ❌ 不包含 Cloudflare Workers / 自动保活  
- ❌ 不推荐 `curl | bash` 盲目执行  

> **建议在执行脚本前，先阅读脚本内容**

---

## 📁 当前仓库文件说明

本仓库当前仅保留以下文件：

```text
LICENSE                     # GPL v3 开源协议
README.md                   # 项目说明文档
sb.sh                       # sing-box 一键部署脚本（核心）
kp.sh                       # 辅助脚本（未被主脚本调用，可选）
app.js                      # Web 页面相关（未被 sb.sh 调用）
sb官方客户端配置说明.txt    # 客户端配置参考说明



### 一、Sing-box-yg精装桶小白专享一键四协议共存脚本（VPS专用）

* 支持人气最高的四大协议：Vless-reality-vision、Vmess-ws(tls)/Argo、Hysteria-2、Tuic-v5

* 支持纯IPV6、纯IPV4、双栈VPS，支持amd与arm架构，支持alpine系统，推荐使用最新的Ubuntu系统

* 小白简单模式：无需域名证书，回车三次就安装完成，复制、扫描你要的节点配置

#### 相关说明及注意点请查看[甬哥博客说明与Sing-box视频教程](https://ygkkk.blogspot.com/2023/10/sing-box-yg.html)

-----------------------------------------------------


### VPS专用一键脚本如下：快捷方式：```sb```

```
bash <(wget -qO- https://raw.githubusercontent.com/shengyying2025/sing-box-sheng/main/sb.sh)
```


### Sing-box-yg脚本界面预览图（注：相关参数随意填写，仅供围观）

![1d5425c093618313888fe41a55f493f](https://github.com/user-attachments/assets/2b4b04a6-2de4-499a-afa1-ed78bccc50a8)

-----------------------------------------------------




-----------------------------------------------------
### 感谢支持！微信打赏甬哥侃侃侃ygkkk
![41440820a366deeb8109db5610313a1](https://github.com/user-attachments/assets/5cd2d891-ae54-4397-8211-ac4c6d1099c9)

---------------------------------------
### 感谢你右上角的star🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/sing-box-yg.svg)](https://starchart.cc/yonggekkk/sing-box-yg)

---------------------------------------
#### 声明：所有代码来源于Github社区与ChatGPT的整合
