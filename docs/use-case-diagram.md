# 校园失物招领与暂存认领系统用例图

![UML 用例总览图，含系统边界、五类参与者及 11 个用例](use-case-diagram.svg)

实线表示主参与关系，虚线表示次参与关系。同一角色可在不同用例中承担不同职责。例如，失主是在线提交认领申请的主参与者，在审核归属证据和确认交付中是次参与者。

图中蓝色用例覆盖寻物、招领、暂存、审核与交付的 8 个关键用例。浅黄色用例是待验证的在线认领、争议复核与外部通知能力。用例名称、编号及业务流程见 [用例场景 PR #14](https://github.com/wwwchangjin/campus-lost-found-system/pull/14/files)。

修改 [PlantUML 图源](use-case-diagram.puml) 后，使用 PlantUML 1.2026.10、Graphviz 和 Noto Sans CJK SC 字体重新生成 SVG。在仓库根目录运行以下命令。

```sh
java -jar /path/to/plantuml-1.2026.10.jar -nometadata -tsvg docs/use-case-diagram.puml
```
