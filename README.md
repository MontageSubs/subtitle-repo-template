## 待初始化

这是一个刚从模板创建的字幕仓库，尚未完成信息初始化。请按照以下步骤完成自动化配置。

### 下一步

1. **确认仓库名**：确保仓库名符合 `英文片名_年份` 格式（详见下方 [仓库命名规范](#仓库命名规范)），如不符合，请前往 **[Settings](../../settings)** 修改。
2. **检查可见性**：检查页面顶部仓库名右侧的标签
   - 已显示 **Public** --> 进行第 3 步
   - 显示 **Private** --> 点击 [此链接](../../settings#danger-zone) 进入 Danger Zone（或手动前往 **Settings → General → Danger Zone**），选择 **Change repository visibility** 更改为 **Public**
3. **触发初始化**：进入 **[Actions](../../actions/workflows/init.yml)** 页面 --> 选择 **"初始化 (Initialize)"** 工作流 --> 点击 **Run workflow** 运行（无需勾选强制选项）。

### 仓库命名规范

为了确保工作流能正确检索影视信息，仓库名必须严格遵循：**影视官方英文名_年份**（例如：`Cosmos_Laundroma_2015`）

**详细规则：**
- **空格替换**：所有空格使用下划线 `_` 代替。
- **字符处理**：含变音符号的字母（如 é, ü, ñ, ø 等）请替换为最接近的英文字母（如 e, u, n, o）。

### 工作流说明

工作流会自动根据仓库名在 TMDB 检索影视信息，并将本 README 重写为正式的项目主页。

> [!NOTE]
> - 自动化流程需要仓库为公开状态才能正常读写仓库信息。
> - 如果仓库名格式不正确或未在 TMDB 中匹配到对应作品，工作流会中止并给出错误说明，请按提示重新创建仓库。

---

## Awaiting Initialization

This is a subtitle repository created from a template and is awaiting initialization. Please follow the steps below to complete the automated setup.

### Next Steps

1. **Confirm Repository Name**: Ensure the repository name follows the `EnglishTitle_Year` format (see [Naming Conventions](#naming-conventions) below). If it does not, please update it in **[Settings](../../settings)**.
2. **Check Visibility**: Check the label next to the repository name at the top of the page.
   - **Public** --> Proceed to Step 3.
   - **Private** --> Click [this link](../../settings#danger-zone) to enter the Danger Zone (or manually navigate to **Settings → General → Danger Zone**) and set **Change repository visibility** to **Public**.
3. **Trigger Initialization**: Navigate to the **[Actions](../../actions/workflows/init.yml)** page --> select the **"Initialize"** workflow --> click **Run workflow** (the force option does not need to be checked).

### Naming Conventions

To ensure the workflow can correctly retrieve metadata, the repository name must strictly follow this format: **Official English Title_Year** (e.g., `Cosmos_Laundroma_2015`).

**Detailed Rules:**
- **Spaces**: Replace all spaces with underscores `_`.
- **Special Characters**: Replace letters with diacritics (such as é, ü, ñ, ø) with their closest basic English equivalents (such as e, u, n, o).

### Workflow Details

The workflow automatically retrieves metadata for movies and series from TMDB based on the repository name and rewrites this README as the official project homepage.

> [!NOTE]
> - The repository must be public for the automation to read and write metadata.
> - If the repository name format is invalid or no matching title is found on TMDB, the workflow will abort and replace this README with an error message. Please recreate the repository as instructed in that case.

---

<div align="center">

**蒙太奇字幕组 (MontageSubs)**  
"用爱发电 ❤️ Powered by Love"

</div>
