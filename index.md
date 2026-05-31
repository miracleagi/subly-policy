# Subly Privacy Policy / 隐私政策

**Last updated / 最后更新**: 2026-05-30

---

## English

### 1. Who we are
Subly ("the App") is developed and maintained by **Zheng Chuanchuan** ("we", "us"). We are an independent developer based in China.

Contact: **palrainzcc@gmail.com**

### 2. What information we collect
**We do not collect any personal data.** Subly is designed as an offline, on-device app.

| Data type | Where it lives | Who can access |
|-----------|----------------|----------------|
| Your subscriptions (name, amount, dates, category, notes) | Locally on your device, or in your private iCloud database when iCloud Sync is enabled | Only you, on devices signed in to your Apple ID |
| App settings (font size, language, notification time, currency) | Locally on your device | Only you |
| Pro purchase status | Stored locally and validated by Apple's StoreKit | Only you |

We **do not** operate any backend server, and we **never** transmit your subscription data to us or any third party.

### 3. Apple services used
- **iCloud / CloudKit**: optional. When enabled, your data is stored in your own private CloudKit database. We have no access to it. iCloud's own privacy policy applies: https://www.apple.com/legal/privacy/
- **StoreKit (In-App Purchase)**: used to process the one-time Subly Pro unlock. Apple handles the payment and shares no payment details with us. We only receive a non-personal signal that the purchase succeeded.
- **User Notifications**: scheduled and delivered entirely on your device. We do not send push notifications from any server.

### 4. Third-party SDKs
**None.** Subly does not embed any analytics, advertising, crash-reporting, or tracking SDKs.

### 5. App Tracking Transparency (ATT)
We do not track you across apps or websites owned by other companies. We do not present the ATT prompt because we have no tracking to disclose.

### 6. Children's privacy
Subly is suitable for all ages and does not knowingly collect data from children.

### 7. Your rights
Because all data lives on your device or in your personal iCloud, you can delete it at any time by:
- Deleting individual subscriptions in the app
- Tapping **Settings → Delete All Subscriptions**
- Deleting the app from your device (this also clears local data; iCloud data can be removed from **Settings → Apple ID → iCloud → Manage Storage → Subly**)

### 8. Changes to this policy
If we ever change this policy, we will update the **Last updated** date and post the new version at https://miracleagi.github.io/subly-policy/. Material changes will be highlighted in the app's release notes.

### 9. Contact
Questions or concerns? Email **palrainzcc@gmail.com**.

---

## 简体中文

### 1. 我们是谁
Subly（"本 App"）由 **郑川川**（"我们"）独立开发与维护，所在地：中国。

联系方式：**palrainzcc@gmail.com**

### 2. 我们收集哪些信息
**我们不收集任何个人数据。** Subly 是一款完全离线、数据保存在设备本地的工具。

| 数据类型 | 存储位置 | 谁可以访问 |
|---------|---------|-----------|
| 你的订阅信息（名称、金额、日期、分类、备注） | 仅本地，或在开启 iCloud 同步时存于你的私有 iCloud 数据库 | 仅你本人（通过 Apple ID 登录的设备） |
| App 设置（字号、语言、通知时间、货币） | 仅本地 | 仅你本人 |
| Pro 购买状态 | 本地保存，由 Apple StoreKit 验证 | 仅你本人 |

我们**没有任何后端服务器**，**永远不会**把你的订阅数据传输给我们或任何第三方。

### 3. 使用的 Apple 服务
- **iCloud / CloudKit**：可选。开启后数据保存在你自己的私有 CloudKit 数据库中，我们无权访问。适用 Apple iCloud 隐私政策：https://miracleagi.github.io/subly-policy/
- **StoreKit（App 内购买）**：用于处理一次性的 Subly Pro 解锁。支付由 Apple 处理，我们不获取任何支付信息，仅收到匿名的"购买成功"信号。
- **本地通知（User Notifications）**：所有通知均在本机调度和触发，我们没有任何服务器向你推送通知。

### 4. 第三方 SDK
**无。** Subly 没有集成任何分析、广告、崩溃上报或追踪类 SDK。

### 5. App 追踪透明度（ATT）
我们不会在其他公司拥有的 App 和网站上追踪你。因为我们没有任何追踪行为，所以也不会弹出 ATT 授权框。

### 6. 儿童隐私
Subly 适合所有年龄段使用，不会主动收集儿童相关数据。

### 7. 你的权利
所有数据均保存于你的设备或个人 iCloud 中，你随时可以删除：
- 在 App 中删除单条订阅
- **设置 → 删除全部订阅**
- 从设备卸载 App（本地数据随之清除；iCloud 数据可在 **iOS 设置 → Apple ID → iCloud → 管理存储 → Subly** 中删除）

### 8. 政策变更
若本政策有变更，我们会更新顶部的"最后更新"日期，并将新版本发布于 <https://miracleagi.github.io/subly-policy/>。重大变更会在 App 更新说明中明示。

### 9. 联系我们
有任何问题，请发送邮件至 **<your-email@example.com>**。

---

## Where to host this / 这份文件放在哪里

App Store Connect 要求隐私政策必须有公开 URL。推荐零成本方案：

1. **GitHub Pages**（推荐）
   - GitHub 新建一个 public 仓库 `subly-policy`
   - 把 `PRIVACY.md` 放进去并重命名 `index.md`
   - 仓库 Settings → Pages → 启用 GitHub Pages
   - 拿到的 URL（如 `https://<your-username>.github.io/subly-policy/`）填进 App Store Connect 的隐私政策栏

2. **Notion 公开页**
   - 把内容粘贴到 Notion，发布为 Public，复制链接

3. **Vercel / Netlify** 也行，但 GitHub Pages 最省心

App Store Connect 填写位置：
- **App Information → Privacy Policy URL**
- **App Privacy** 部分（Data Types 全选 "No data collected"）
