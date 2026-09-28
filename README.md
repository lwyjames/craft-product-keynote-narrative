# 产品发布叙事与讲解词

`craft-product-keynote-narrative` 是用于中文产品发布会的个人技能：把产品功能或已确认的 UX 流程组织成发布叙事、逐页文案、演示节奏和可口播的讲解词，并依据目标时长或实测语速校准。

## 发布工作流

发布需求由用户提供。进入发布工作流时，技能实际创建或更新 `发布叙事.md`。草稿、修订、批准阶段沿用同一文件名，状态和修订记录写在文件内部；只有用户明确批准当前版本，才标记为“批准版”。批准后若修改叙事内容，状态恢复为“修订待确认”。

独立的方向讨论、标题脑暴或局部讲解词改写，可按请求以简短文字交付。

## 文件

- [SKILL.md](SKILL.md)：技能触发条件、叙事方法、交付和审批规则。
- [references/timing-and-delivery.md](references/timing-and-delivery.md)：实测语速、演示时间与口播时长的校准方法。
- [agents/openai.yaml](agents/openai.yaml)：技能在界面中的名称与描述。
- [assets/icon.svg](assets/icon.svg)：技能图标。
- [产品发布叙事与讲解词 skill 使用说明书](docs/产品发布叙事与讲解词skill使用说明书.md)：完整工作流、各 skill 分工、Prompt 示例与交付验收。

此仓库是技能的公开源码副本。