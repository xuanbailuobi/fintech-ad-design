# Fintech Ad Design

金融广告图片的参考图复刻、排版优化和作图规范技能。  
当前版本：**2.0.0**，调用名：**`$fintech-ad-design`**。

当前阶段不包含自主策划原创广告；后续根据用户教学逐步扩展。
品牌、国家地区、语言、币种、利率、计息方式、还款顺序、借款范围和周期均按项目配置。

## 在Mac上安装

可以将以下内容发给Mac上的Codex：

> 使用 skill-installer，从 https://github.com/xuanbailuobi/fintech-ad-design/tree/main/skills/fintech-ad-design 安装技能。保留已有版本，检查安装后的 SKILL.md 和参考文件是否完整。

也可使用Git方式，在首次安装时运行：

```sh
git clone https://github.com/xuanbailuobi/fintech-ad-design.git "$HOME/fintech-ad-design"
mkdir -p "$HOME/.agents/skills"
ln -s "$HOME/fintech-ad-design/skills/fintech-ad-design" "$HOME/.agents/skills/fintech-ad-design"
```

若同名目录已经存在，先让Codex检查并备份/迁移，不要直接删除或覆盖。
Codex支持用户技能目录及符号链接；未识别时重启应用。
[官方技能说明](https://learn.chatgpt.com/docs/build-skills)

安装后输入：

```text
$fintech-ad-design

按附件参考图复刻可编辑广告。
产品：
国家/地区：
广告语言：
币种：
借款范围：
借款周期：
利率及单位：
计息方式：
还款安排：

缺少必要信息时询问。
```

在Mac上另行连接Figma并获得目标文件权限。技能不包含登录状态或访问凭证。

## 更新到新版本

采用上述Git和符号链接安装时：

```sh
git -C "$HOME/fintech-ad-design" pull --ff-only
```

有本地修改或分叉时先合并，不使用强制覆盖。
通过skill-installer复制安装的版本需要重新同步或让Codex更新安装目录。
GitHub提交不会自动同步到其他设备。

## 维护版本

- `VERSION`记录当前版本。
- `CHANGELOG.md`记录用户确认的通用改进。
- `skills/fintech-ad-design/references/learning.md`说明学习和更新流程。
- 项目数据与通用规则分开；`private-projects/`、`local-assets/`默认忽略。
- 修正升补丁版本，新增已认可方法升次版本，重大范围变化升主版本。
- 发布前核对版本一致、参考链接和计算示例。正式标签使用`vX.Y.Z`。

本仓库仅提供通用规则和空项目模板，不包含用户原始PDF或品牌素材。
不默认赋予第三方素材使用权；外部素材按其各自许可使用。
