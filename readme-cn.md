<div align="center" width="100px">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/4006792/214640818-fd4de9e6-bdee-47f0-ae66-e69ee9ec84bb.png">
   <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/4006792/214636328-8e4f83e8-66cb-4114-a3d8-473eb908b9c3.png">
   <img width="200" alt="Saleor电商平台Logo" src="https://user-images.githubusercontent.com/4006792/214636328-8e4f83e8-66cb-4114-a3d8-473eb908b9c3.png">
 </picture>
</div>

<div align="center">
  <strong>跨语言与技术栈的电商解决方案</strong>
</div>

<div align="center">
  基于 GraphQL 的纯 API 可组合式电商平台
</div>

<br>

<div align="center">
  加入开发者社区：<br>
  <a href="https://saleor.io/">官方网站</a>
  <span> | </span>
  <a href="https://twitter.com/getsaleor">Twitter</a>
  <span> | </span>
  <a href="https://github.com/saleor/saleor/discussions">GitHub 讨论区</a>
  <span> | </span>
  <a href="https://discord.gg/H52JTZAtSH">Discord</a>
</div>

<div align="center">
   <a href="https://saleor.io/blog">技术博客</a>
  <span> | </span>
  <a href="https://saleor.typeform.com/to/JTJK0Nou">订阅新闻简报</a>
</div>

<br>

<div align="center">
  <a href="https://codecov.io/gh/saleor/saleor" >
    <img src="https://codecov.io/gh/saleor/saleor/graph/badge.svg?token=qkNcTJ4TmI" alt="代码覆盖率"/>
  </a>
  <a href="https://docs.saleor.io/">
    <img src="https://img.shields.io/badge/文档-docs.saleor.io-brightgreen.svg" alt="文档中心" />
  </a>
  <a href="https://github.com/astral-sh/ruff">
    <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json" alt="Ruff代码检查">
  </a>
</div>

## 目录

- [核心优势](#核心优势)
- [功能特性](#功能特性)
- [安装部署](#安装部署)
- [文档中心](#文档中心)
- [贡献指南](#贡献指南)
- [用户反馈](#用户反馈)
- [许可协议](#许可协议)

## 核心优势

- **技术无关性** - 无单一插件架构或技术锁定
- **纯GraphQL架构** - 精心设计的 API，无风格混杂
- **无头架构** - 仅通过 API 交互、配置和扩展后端
- **开源自由** - 功能完整的单一版本，无商业限制
- **云原生设计** - 经过全球知名品牌实战检验
- **原生多平台支持** - 按[渠道](https://docs.saleor.io/docs/3.x/developer/channels)管理价格、货币、库存和商品

## 为什么选择API优先架构？

Saleor 的 API 优先扩展性为开发者提供强大工具，可通过以下方式扩展后端：
[Webhooks](https://docs.saleor.io/docs/3.x/developer/extending/webhooks/overview)、
属性配置、
[元数据](https://docs.saleor.io/docs/3.x/api-usage/metadata)、
[应用扩展](https://docs.saleor.io/docs/3.x/developer/extending/apps/overview)、
[订阅查询](https://docs.saleor.io/docs/3.x/developer/extending/webhooks/subscription-webhook-payloads)、
[API扩展](https://docs.saleor.io/docs/3.x/developer/extending/webhooks/synchronous-events/overview)、
[仪表板嵌入](https://docs.saleor.io/docs/3.x/developer/extending/apps/overview)

与传统单体架构相比的优势：

* 更少宕机时间 - 应用独立部署
* 高可靠性 - 自定义逻辑与核心分离
* 平滑升级 - 避免扩展冲突
* 技术自由 - 支持任意技术栈
* 并行开发 - 协作更高效
* 易调试 - 问题定位更精准
* 弹性扩展 - 各组件独立扩容

### 适用场景建议
如果您是独立开发者，服务于流量较低的小型企业，传统 WordPress 或 Magento 的单体架构可能更简单快捷。但如果您需要：

* 每日频繁部署
* 高可靠性与可用性
* 团队协作开发
* 处理复杂业务需求

Saleor 是您的理想选择。

## 功能特性
- **企业级能力**：安全、可扩展、稳定，经大型品牌验证
- **管理仪表盘**：高效易用的后台系统（独立项目[仓库](https://github.com/saleor/saleor-dashboard)）
- **全球化设计**：多币种、多语言、多仓库支持
- **内容管理**：商品与营销内容管理
- **商品管理**：支持复杂商品目录的丰富内容模型
- **订单系统**：灵活订单模型，支持分单支付、多仓发货、退换货
- **客户管理**：历史订单与偏好设置
- **促销引擎**：限时折扣、优惠券、购物车规则、礼品卡
- **支付编排**：多支付网关支持，可扩展支付API
- **购物车系统**：高级支付与税务选项，完整优惠控制
- **SEO优化**：无头架构带来无限SEO可能性
- **应用扩展**：通过 iframe 集成任意技术栈

![Saleor管理仪表盘](https://user-images.githubusercontent.com/9268745/224249510-d3c7658e-6d5c-42c5-b4fb-93eaf65a5335.png)

## 安装部署

[查看官方安装文档](https://docs.saleor.io/docs/3.x/developer/installation) 获取详细部署指南。

注意：
`main`分支为开发版本，可能存在不稳定。生产环境请使用最新稳定版：
- [Saleor核心](https://github.com/saleor/saleor/releases/)
- [仪表盘](https://github.com/saleor/saleor-dashboard/releases/)
- [店铺前端](https://github.com/saleor/react-storefront/releases/)

### Saleor云平台
最快体验方式是通过 [Saleor Cloud](https://cloud.saleor.io) 开发者账户。

[立即注册](https://cloud.saleor.io/register) 或安装 CLI 工具：
```bash
npm i -g @saleor/cli
```

## 文档中心

[官方文档](URL_ADDRESS[官方文档](https://docs.saleor.io/docs/3.x/) 提供了详细的安装、配置和使用指南。

完整文档请访问：docs.saleor.io
贡献文档请前往 saleor/saleor-docs 仓库。
平台集成
本地运行完整Saleor生态（API+前端+仪表盘）推荐使用 saleor-platform 项目。
查看集成平台
店铺前端
基于 Next.js App Router + React + TypeScript + Tailwind CSS 的开源示例：
React店铺前端仓库 在线示例
贡献指南
我们欢迎所有贡献！建议从 Good first issue 开始参与。
查看开发路线图或提出新功能建议，请创建issue。
完整指南请见贡献说明。
