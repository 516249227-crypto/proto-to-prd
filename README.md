# proto-to-prd

高保真原型 → 高细节 PRD 的生成技能（Agent Skills 规范）。

读取 HTML 可交互原型、设计稿截图、线框图或页面文字描述，按页面结构生成结构化 PRD：编号页面清单（G/P/S/M 四类）、7 列数据字段表、交互流程、状态变更方表、GIVEN-WHEN-THEN 验收标准、ASCII 线框图、明确排除表；生成后执行一致性自检，再通过批次确认循环与用户对齐待确认事项，清零时沉淀为决策与确认记录。

PRD 只覆盖用户可见的数据和业务规则；接口契约、运行时行为等工程内容由下游文档承接。

## 安装（Trae）

```bash
git clone git@github.com:516249227-crypto/proto-to-prd.git ~/.trae-cn/skills/proto-to-prd
```

或下载 zip 解压到 `~/.trae-cn/skills/` 下。新开对话后说"把原型转成 PRD"即可触发。

## 更新

在技能目录内执行 `git pull`。
