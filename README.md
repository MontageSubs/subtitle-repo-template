## 待初始化

这是一个刚从模板创建的字幕仓库，尚未完成信息初始化。

**下一步：**

1. 检查本仓库当前的可见性：页面顶部仓库名右侧会有一个标签，显示 **Public** 或 **Private**
   - 已显示 **Public** → 直接进行下一步
   - 显示 **Private** → 点击 [此链接](../../settings#danger-zone) 直达 Danger Zone，或手动前往 **Settings → General → Danger Zone**，选择 **Change repository visibility → Public**
2. 进入本仓库的 **[Actions](../../actions/workflows/init.yml)** 页面
3. 选择 **"初始化 (Initialize)"** 工作流
4. 点击 **Run workflow** 手动触发，无需填写任何参数

工作流会自动根据仓库名（`英文片名_年份` 格式）在 TMDB / 豆瓣检索影片信息，并重写本 README 为正式的项目主页。

> [!NOTE]
> - 自动化流程需要仓库为公开状态才能正常读写仓库信息
> - 如果仓库名格式不正确，或未能在 TMDB 中匹配到对应影片，工作流会中止并将本 README 替换为对应的错误说明，请届时按提示删除并重新创建仓库

---

## Awaiting Initialization

This is a subtitle repository just created from the template and has not yet been initialized.

**Next steps:**

1. Check this repository's current visibility: a label next to the repository name at the top of the page shows either **Public** or **Private**
   - Shows **Public** → proceed to the next step
   - Shows **Private** → click [this link](../../settings#danger-zone) to jump directly to Danger Zone, or manually go to **Settings → General → Danger Zone**, then select **Change repository visibility → Public**
2. Go to this repository's **[Actions](../../actions/workflows/init.yml)** page
3. Select the **"初始化 (Initialize)"** workflow
4. Click **Run workflow** to trigger it manually — no input required

The workflow will look up the title on TMDB / Douban based on the repository name (in `EnglishTitle_Year` format), then rewrite this README into the project's public homepage.

> [!NOTE]
> - The automation needs the repository to be public to read/write repository metadata
> - If the repository name format is invalid, or no matching title is found on TMDB, the workflow will abort and replace this README with the corresponding error message. Please delete and recreate the repository as instructed

---

<div align="center">

**蒙太奇字幕组 (MontageSubs)**  
"用爱发电 ❤️ Powered by love"

</div>
