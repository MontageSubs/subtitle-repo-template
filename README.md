## 待初始化

这是一个刚从模板创建的字幕仓库，尚未完成信息初始化。

**下一步：**

1. **先将本仓库改为 Public**：进入 **Settings → General → Danger Zone → Change repository visibility**，选择 **Public**
   > 自动化流程需要仓库为公开状态才能正常读写仓库信息（组织级 secret 在免费版下默认不对私有仓库开放），此步骤无法自动完成，请手动操作
2. 进入本仓库的 **[Actions](../../actions/workflows/init.yml)** 页面
3. 选择 **"初始化 (Initialize)"** 工作流
4. 点击 **Run workflow** 手动触发，无需填写任何参数

工作流会自动根据仓库名（`英文片名_年份` 格式）在 TMDB / 豆瓣检索影片信息，并重写本 README 为正式的项目主页。

> [!NOTE]
> 如果仓库名格式不正确，或未能在 TMDB 中匹配到对应影片，工作流会中止并将本 README 替换为对应的错误说明，请届时按提示删除并重新创建仓库。

---

## 待初始化（繁體）

這是一個剛從範本建立的字幕儲存庫，尚未完成資訊初始化。

**下一步：**

1. **先將本儲存庫改為 Public**：進入 **Settings → General → Danger Zone → Change repository visibility**，選擇 **Public**
   > 自動化流程需要儲存庫為公開狀態才能正常讀寫儲存庫資訊（組織層級 secret 在免費版下預設不對私有儲存庫開放），此步驟無法自動完成，請手動操作
2. 進入本儲存庫的 **[Actions](../../actions/workflows/init.yml)** 頁面
3. 選擇 **"初始化 (Initialize)"** 工作流程
4. 點擊 **Run workflow** 手動觸發，無需填寫任何參數

工作流程會自動根據儲存庫名稱（`英文片名_年份` 格式）在 TMDB／豆瓣檢索影片資訊，並重寫本 README 為正式的專案主頁。

> [!NOTE]
> 如果儲存庫名稱格式不正確，或未能在 TMDB 中比對到對應影片，工作流程會中止並將本 README 替換為對應的錯誤說明，請屆時依提示刪除並重新建立儲存庫。

---

## Awaiting Initialization

This is a subtitle repository just created from the template and has not yet been initialized.

**Next steps:**

1. **Make this repository Public first**: go to **Settings → General → Danger Zone → Change repository visibility**, and select **Public**
   > The automation needs the repository to be public to read/write repository metadata (on the Free plan, org-level secrets aren't available to private repos by default). This step cannot be automated — please do it manually
2. Go to this repository's **[Actions](../../actions/workflows/init.yml)** page
3. Select the **"初始化 (Initialize)"** workflow
4. Click **Run workflow** to trigger it manually — no input required

The workflow will look up the title on TMDB / Douban based on the repository name (in `EnglishTitle_Year` format), then rewrite this README into the project's public homepage.

> [!NOTE]
> If the repository name format is invalid, or no matching title is found on TMDB, the workflow will abort and replace this README with the corresponding error message. Please delete and recreate the repository as instructed.

---

<div align="center">

**蒙太奇字幕组 (MontageSubs)**  
"用爱发电 ❤️ Powered by love"

</div>
