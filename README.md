
# 多前缀号码生成器

这是一个简单的前端网页工具，用来根据多个前 6 位前缀批量生成随机电话号码。

## 使用方法

1. 打开 `index.html`（本地双击或部署到 GitHub Pages）。
2. 在“多个前缀”文本框中，每行输入一个前 6 位号码，例如：

   ```text
   407270
   407276
   407281
   407289
   407290
   ```

3. 在“每个前缀生成数量”中输入数量（例如 50）。
4. 点击“🎯 生成号码”按钮。
5. 生成结果可：
   - 直接复制到剪贴板。
   - 下载为 TXT 文件。
   - 下载为 CSV 文件（第一列为 phone_number）。

## GitHub Pages 部署

1. 新建一个公开仓库（例如 `phone-generator`）。
2. 把本 ZIP 解压后的所有文件上传到仓库根目录。
3. 在仓库 Settings → Pages 中，将 Source 设为：
   - Branch: `main`
   - Folder: `/root`
4. 保存后，稍等片刻即可通过类似以下 URL 访问：

   `https://你的用户名.github.io/phone-generator/`
