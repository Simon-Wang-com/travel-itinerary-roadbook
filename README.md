# travel-itinerary-roadbook

可交互的单文件 HTML 旅行路书 skill（v3.1）。

## 直接下载

- [travel-roadbook-v3.1.zip](https://github.com/Simon-Wang-com/travel-itinerary-roadbook/raw/main/travel-roadbook-v3.1.zip)

## 这是什么

用一个 HTML 文件生成手机/电脑都能直接打开的旅行路书，包含：

- 按实际天数生成的 Day tab 与行程时间线
- 景点自动识别 + 内嵌实拍图
- 景点打卡热度榜与详情页
- 美食、记账、预算、天气穿搭、导览图
- 返回/关闭的来路栈、滚动位置记忆
- 二维码交付

## 安装

1. 下载仓库中的 [travel-roadbook-v3.1.zip](https://github.com/Simon-Wang-com/travel-itinerary-roadbook/raw/main/travel-roadbook-v3.1.zip)。
2. 打开豆包工作客户端 → 左侧「插件·技能·伙伴」→「技能」→ 右上角「+ 添加」→「上传技能」。
3. 选择这个 zip，等待解析完成。

公开上架到豆包市场时，还需在豆包开放平台创建技能、完成企业资质认证、填写评测报告和 5–10 条示例提示词，提交平台审核。

## 版本

- skill 版本：v3.1（累计修改 31 次）。
- 生成的路书自身版本独立计算：第一版为 v0.1，之后每次修改递增（v0.2、v0.3……），不跟 skill 版本混用。

## v3.1 修复重点

- 模板不再保留南京/杭州示例详情、餐厅表、官方导览图和示例高德关键词；只保留框架与占位。
- 自检脚本新增编码 URL 检查，模板严格示例残留检查为 0。
- Day 标签恢复原版选中态：深青填充 + 白字；未选中浅色胶囊。
- 时间线自动补高德导航，版本号必须递增，票卡/座位/航班识别继续保留。
