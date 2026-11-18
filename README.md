# travel-itinerary-roadbook

可交互的单文件 HTML 旅行路书 skill（v3.13）。

## 直接下载

- [travel-roadbook-v3.13.zip](https://github.com/Simon-Wang-com/travel-itinerary-roadbook/raw/main/travel-roadbook-v3.13.zip)
- 旧版本保留：[v3.1](https://github.com/Simon-Wang-com/travel-itinerary-roadbook/raw/main/travel-roadbook-v3.1.zip) / [v2.7](https://github.com/Simon-Wang-com/travel-itinerary-roadbook/raw/main/travel-roadbook-v2.7.zip)

## 这是什么

用一个 HTML 文件生成手机/电脑都能直接打开的旅行路书，包含：

- 按实际天数生成的 Day tab 与行程时间线
- 景点自动识别 + 内嵌实拍图
- 景点打卡热度榜与详情页
- 美食、记账、预算、天气穿搭、导览图
- 返回/关闭的来路栈、滚动位置记忆
- 二维码交付
- 车票/机票识别、票务入口嵌入当天交通行
- 车票卡禁止「航班座位」按钮；机票卡保留「返回车票」

## 安装

1. 下载仓库中的 `travel-roadbook-v3.13.zip`。
2. 打开豆包工作客户端 → 左侧「插件·技能·伙伴」→「技能」→ 右上角「+ 添加」→「上传技能」。
3. 选择这个 zip，等待解析完成。

公开上架到豆包市场时，还需在豆包开放平台创建技能、完成企业资质认证、填写评测报告和 5–10 条示例提示词，提交平台审核。

## 版本

- skill 版本：v3.13（累计修改 43 次）。
- 生成的路书自身版本独立计算：第一版为 v0.1，之后每次修改递增（v0.2、v0.3……），不跟 skill 版本混用。

## v3.13 修复重点

- 车票/高铁卡不再显示「✈️ 航班座位」按钮，避免用户在高铁路书里误入机票座位。
- 机票卡保留「🚆 返回车票」，从航班入口打开后仍可切回车票。
- 模板、静态验收和用户视角走查同步增加「车票卡禁止 `tkPlaneOpen`」检查。
- 继续保留 v3.12 的票务入口贴合交通行：G1623 在 Day 1 10:04、D6439 在 Day 2 13:53、MF8301 在 Day 5 15:15 的交通行之后。
