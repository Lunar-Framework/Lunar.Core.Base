This branch (`backup`) serves as an archive of the commit structure before it was reorganized.

It preserves the original state of all commits prior to the refactoring. Moving forward, the primary workflow will be through merging Pull Requests (PRs) to avoid direct commits to the `main` branch.

---

此分支 (`backup`) 是对提交结构进行整理前的版本存档。

该分支保留了重构前，所有提交的原始状态。此后，主要工作流将通过合并PR的方式进行，以避免直接提交到 `main` 分支。

---

# Lunar.Core.Base

> **Status**: 🚧 Initial iteration (features and structure subject to frequent changes)

Lunar.Core.Base is a **pure C#**, **engine-agnostic** bridging definition library.  
It provides a shared foundation that can be referenced by both the **Lunar project** and **MooaLewaUI**, ensuring consistent base definitions across different engine implementations.

This repository does not depend on Unity or any other game engine.

## License
Lunar.Core.Base is available under a dual-license model:

### Open Source License (LGPL-3.0)
- You may use Lunar.Core.Base in closed-source projects as long as you do not modify its source code.
- If you modify Lunar.Core.Base (e.g. add/change definitions), you must release those modifications under the same license (LGPL-3.0).
- Your own game/application code may remain closed-source.

### Commercial License
- If you wish to modify Lunar.Core.Base and keep those modifications closed-source, or include it in a project where LGPL is not acceptable, you can contact me for a commercial license.

---

> **状态**：🚧 初始迭代中（功能与结构可能频繁变动）

Lunar.Core.Base 是一个 **纯 C#**、**引擎无关** 的桥接定义库。  
它为 **Lunar 项目** 与 **MooaLewaUI** 提供统一的基础定义，以保证在不同引擎实现中保持一致性。

本仓库不依赖 Unity 或任何其他游戏引擎。

## 许可证
Lunar.Core.Base 采用双重许可模式：

### 开源许可证（LGPL-3.0）
- 只要您不修改 Lunar.Core.Base 的源代码，就可以在闭源项目中使用它。
- 如果您修改了 Lunar.Core.Base（例如添加 / 更改定义），您必须在相同的许可证（LGPL-3.0）下发布这些修改。
- 您自己的游戏 / 应用程序代码可以保持闭源。

### 商业许可
- 如果您希望修改 Lunar.Core.Base 并保持这些修改闭源，或在不接受 LGPL 的项目中包含它，您可以联系我以获取商业许可。
