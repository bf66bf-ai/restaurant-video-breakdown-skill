# py-restaurant-breakdown（测试版）

> 这是公开测试版 Skill。调用代码为 `/py-restaurant-breakdown`；当前用于收集跨 Agent 的安装和输出反馈，尚未声明为稳定版。

当用户提供餐饮参考视频并要求拆片、拉片、分析脚本或帮助客户复刻时使用。先判断消费场景和内容任务，再输出内容主线、到店理由、证据链、关键帧和可调整仿拍抓手；适用于本地视频、口播视频、连续现场素材和带文案的动图式视频。

## 安装

```bash
npx -y skills add bf66bf-ai/restaurant-video-breakdown-skill -g --all
```

## 使用

安装后，可以这样开始：

> 使用 `/py-restaurant-breakdown` 完成餐饮视频拆片，并按可观察标准检查结果。

## 运行依赖

- 支持 Agent Skills 的客户端

## 内容

本仓库只发布运行这个 Skill 所需的文件。本地评测样本、预期答案和运行记录不包含在测试包中；当前仓库为公开 beta，尚未代表正式稳定版。
