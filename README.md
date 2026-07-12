# 今日上上签·AI灵境壁纸 🏮

国潮赛博朋克风的 AI 灵签壁纸生成器 —— 每日抽签，生成专属手机壁纸。

## ✨ 功能

- 🎋 **每日 12 次免费抽签**：随机生成大吉/中吉/小吉/吉/凶/小凶六种签种
- 🤖 **AI 图片生成**：使用 Pollinations.ai 免费 API，生成国潮赛博朋克风壁纸
- 📜 **AI 签文解读**：DeepSeek API 驱动，生成 80 字优美励志签文
- 💰 **付费解锁**：支付 10 元解锁 4K 高清无水印壁纸 + 200 字深度命理解读
- 📤 **一键分享**：支持 Web Share API 分享给好友
- 📱 **移动端适配**：完美适配手机和桌面端

## 🚀 快速部署

### 方式一：Vercel（推荐）

1. 注册 [Vercel](https://vercel.com) 账号
2. 导入此 GitHub 仓库
3. 点击 Deploy，无需任何配置

### 方式二：GitHub Pages

1. Fork 此仓库
2. Settings → Pages → Source 选择 `main` 分支 → Save
3. 访问 `https://你的用户名.github.io/仓库名/`

## 🔧 配置

打开 `index.html`，在 `<script>` 标签开头的 `CONFIG` 对象中填写：

```javascript
const CONFIG = {
  DEEPSEEK_API_KEY: '你的DeepSeek_API_Key',  // 从 platform.deepseek.com 获取
  PAYJS_MCHID: '你的PAYJS商户号',            // 从 payjs.cn 获取
  PAYJS_KEY: '你的PAYJS密钥',                // 从 payjs.cn 获取
  // ...
};
```

## 📦 技术栈

- 纯 HTML/CSS/JS，单文件部署
- Pollinations.ai（免费 AI 图片生成）
- DeepSeek API（AI 文字生成）
- PAYJS（个人免签支付）
- localStorage（数据持久化）

## ⚠️ 免责声明

本应用仅供娱乐，签文内容由 AI 生成，不构成任何预测或建议。