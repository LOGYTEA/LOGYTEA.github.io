ZenFile 插件商店

index.json    商店清单，ZenFile「设置 - 插件」读取
packages/     插件包，每个是一个 zip

新增插件：把 zip 放进 packages/，再在 index.json 里加一条
（id 必须与包内 plugin.json 的 id 完全一致，url 必须 https）。
