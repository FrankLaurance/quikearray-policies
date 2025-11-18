# 使用 GitHub Pages 托管用户协议和隐私政策指南

## 概述

本指南将帮助你使用 GitHub Pages 免费托管 QuikeArray 的用户协议和隐私政策 HTML 页面。

## 优势

- ✅ 完全免费
- ✅ 支持 HTTPS（Apple 要求）
- ✅ 无需服务器维护
- ✅ 可随时更新
- ✅ 专业的 URL（yourname.github.io）

---

## 第一步：创建 GitHub 仓库

### 1.1 注册 GitHub 账号
如果还没有账号，访问 https://github.com 注册。

### 1.2 创建新仓库
1. 登录 GitHub
2. 点击右上角 `+` → `New repository`
3. 填写仓库信息：
   - **Repository name**: `quikearray-policies`（或其他名称）
   - **Description**: QuikeArray 用户协议和隐私政策
   - **Public**: 选择 Public（必须公开才能使用 GitHub Pages）
   - ✅ 勾选 `Add a README file`
4. 点击 `Create repository`

---

## 第二步：准备 HTML 文件

### 2.1 用户协议 HTML

创建文件 `terms.html`:

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuikeArray 用户协议</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 {
            color: #007AFF;
            border-bottom: 2px solid #007AFF;
            padding-bottom: 10px;
        }
        h2 {
            color: #555;
            margin-top: 30px;
        }
        .date {
            color: #888;
            font-size: 14px;
        }
        .highlight {
            background-color: #fff3cd;
            padding: 15px;
            border-left: 4px solid #ffc107;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <h1>QuikeArray 用户协议</h1>
    <p class="date">生效日期：2025年11月18日</p>
    
    <p>欢迎使用 QuikeArray！请在使用本应用前仔细阅读本协议。</p>

    <h2>1. 服务说明</h2>
    <p>QuikeArray 是一款专业的排球阵容管理工具，提供以下功能：</p>
    <ul>
        <li>排球阵容编排和管理</li>
        <li>战术板绘图功能</li>
        <li>阵容导出（文本和图片）</li>
        <li>球员信息管理</li>
        <li>位置轮转功能</li>
    </ul>

    <h2>2. 使用许可</h2>
    <h3>2.1 授权范围</h3>
    <ul>
        <li>您获得非独占、不可转让的应用使用权</li>
        <li>仅供个人或团队合法使用</li>
        <li>不得用于任何非法目的</li>
    </ul>

    <h3>2.2 使用限制</h3>
    <ul>
        <li>不得对应用进行反向工程、反编译或反汇编</li>
        <li>不得复制、修改或分发应用的任何部分</li>
        <li>不得利用应用进行任何违法活动</li>
    </ul>

    <h2>3. 专业版购买</h2>
    <h3>3.1 购买说明</h3>
    <ul>
        <li>专业版为一次性买断制，无需订阅</li>
        <li>购买后永久解锁所有高级功能</li>
        <li>购买通过 Apple App Store 完成</li>
    </ul>

    <h3>3.2 功能说明</h3>
    <ul>
        <li><strong>免费版</strong>：基础排阵功能，最多3个场次</li>
        <li><strong>专业版</strong>：解锁导出功能、无限场次、位置轮转等高级功能</li>
    </ul>

    <h3>3.3 退款政策</h3>
    <ul>
        <li>所有购买遵循 Apple App Store 的退款政策</li>
        <li>如需退款，请通过 App Store 申请</li>
        <li>开发者无法直接处理退款请求</li>
    </ul>

    <h3>3.4 恢复购买</h3>
    <ul>
        <li>您可以在新设备上免费恢复已购买的专业版</li>
        <li>使用相同的 Apple ID 登录即可自动恢复</li>
    </ul>

    <h2>4. 数据与隐私</h2>
    <div class="highlight">
        <strong>重要：</strong>所有数据（球员信息、阵容、设置等）仅存储在您的设备上。我们不收集、上传或存储您的任何数据到服务器。
    </div>

    <h3>4.1 本地存储</h3>
    <p>所有数据仅存储在您的设备上，我们不收集、上传或存储您的任何数据到服务器。</p>

    <h3>4.2 数据安全</h3>
    <ul>
        <li>您需自行备份重要数据</li>
        <li>删除应用将删除所有本地数据</li>
        <li>我们不对数据丢失承担责任</li>
    </ul>

    <h2>5. 知识产权</h2>
    <p>5.1 应用的所有权利（包括但不限于版权、商标、专利）归开发者所有</p>
    <p>5.2 用户创建的阵容和数据归用户所有</p>

    <h2>6. 免责声明</h2>
    <h3>6.1 "按现状"提供</h3>
    <ul>
        <li>应用按"现状"和"可用"基础提供</li>
        <li>不保证应用无错误或不中断</li>
    </ul>

    <h3>6.2 责任限制</h3>
    <p>在法律允许的最大范围内，开发者不对任何间接、特殊、附带或惩罚性损害负责，包括但不限于数据丢失、利润损失等。</p>

    <h3>6.3 第三方服务</h3>
    <ul>
        <li>应用内购买由 Apple 提供，遵循 Apple 的相关条款</li>
        <li>相册访问等系统功能由 iOS 系统提供</li>
    </ul>

    <h2>7. 协议变更</h2>
    <ul>
        <li>我们保留随时修改本协议的权利</li>
        <li>重大变更将在应用内通知</li>
        <li>继续使用应用即表示接受修改后的协议</li>
    </ul>

    <h2>8. 适用法律</h2>
    <p>本协议受中华人民共和国法律管辖。</p>

    <h2>9. 联系方式</h2>
    <p>如有任何问题，请通过以下方式联系我们：</p>
    <ul>
        <li>App Store 应用页面反馈</li>
        <li>应用内设置页面</li>
    </ul>

    <hr style="margin: 40px 0;">
    <p style="text-align: center; color: #888;">感谢您使用 QuikeArray！</p>
</body>
</html>
```

### 2.2 隐私政策 HTML

创建文件 `privacy.html`:

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuikeArray 隐私政策</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 {
            color: #007AFF;
            border-bottom: 2px solid #007AFF;
            padding-bottom: 10px;
        }
        h2 {
            color: #555;
            margin-top: 30px;
        }
        .date {
            color: #888;
            font-size: 14px;
        }
        .highlight {
            background-color: #d4edda;
            padding: 15px;
            border-left: 4px solid #28a745;
            margin: 20px 0;
        }
        .important {
            background-color: #fff3cd;
            padding: 15px;
            border-left: 4px solid #ffc107;
            margin: 20px 0;
        }
        .icon {
            display: inline-block;
            margin-right: 8px;
        }
    </style>
</head>
<body>
    <h1>QuikeArray 隐私政策</h1>
    <p class="date">生效日期：2025年11月18日 | 最后更新：2025年11月18日</p>
    
    <div class="highlight">
        <strong>重要说明：</strong>本应用不收集、不上传、不存储任何个人数据到服务器。所有数据仅保存在您的设备上。
    </div>

    <h2>概述</h2>
    <p>QuikeArray（以下简称"本应用"或"我们"）非常重视您的隐私。本隐私政策说明了我们如何处理您的信息。</p>

    <h2>1. 我们收集的信息</h2>
    
    <h3>1.1 我们不收集的信息</h3>
    <ul>
        <li><span class="icon">❌</span> 不收集个人身份信息（姓名、电话、邮箱等）</li>
        <li><span class="icon">❌</span> 不收集位置信息</li>
        <li><span class="icon">❌</span> 不收集设备标识符</li>
        <li><span class="icon">❌</span> 不使用分析工具或第三方追踪</li>
        <li><span class="icon">❌</span> 不上传任何数据到服务器</li>
    </ul>

    <h3>1.2 本地存储的信息</h3>
    <p>以下信息仅存储在您的设备上，不会离开您的设备：</p>
    <ul>
        <li><span class="icon">✅</span> 球员信息（姓名、位置、号码等）</li>
        <li><span class="icon">✅</span> 阵容配置和战术图</li>
        <li><span class="icon">✅</span> 应用设置（界面偏好、颜色等）</li>
        <li><span class="icon">✅</span> 专业版购买状态（通过 Apple 管理）</li>
    </ul>

    <h2>2. 系统权限使用说明</h2>

    <h3>2.1 剪贴板读取</h3>
    <div class="important">
        <strong>用途：</strong>自动识别并导入球员名单
    </div>
    <p><strong>详细说明：</strong></p>
    <ul>
        <li>应用启动时会检查剪贴板内容</li>
        <li>仅识别特定格式的球员名单（如"1. 张三"）</li>
        <li>如检测到球员名单格式，自动导入到应用中</li>
        <li>不上传剪贴板内容到任何服务器</li>
        <li>不存储剪贴板历史记录</li>
    </ul>
    <p><strong>您可以：</strong></p>
    <ul>
        <li>在 iOS 设置中关闭剪贴板访问（iOS 16+会有提示）</li>
        <li>手动输入球员信息而不使用剪贴板导入</li>
    </ul>

    <h3>2.2 相册访问权限</h3>
    <div class="important">
        <strong>用途：</strong>保存导出的阵容图片到相册
    </div>
    <p><strong>详细说明：</strong></p>
    <ul>
        <li>仅在您主动点击"导出图片"时请求权限</li>
        <li>仅用于将生成的阵容图片保存到您的相册</li>
        <li>不读取相册中的任何照片</li>
        <li>不上传图片到任何服务器</li>
    </ul>
    <p><strong>您可以：</strong></p>
    <ul>
        <li>拒绝相册权限，仍可使用文本导出功能</li>
        <li>随时在系统设置中撤销权限</li>
    </ul>

    <h2>3. 数据存储与安全</h2>

    <h3>3.1 本地存储</h3>
    <ul>
        <li>所有数据使用 iOS 系统的 UserDefaults 存储在您的设备上</li>
        <li>数据不会同步到 iCloud 或其他云服务</li>
        <li>数据不会在设备间共享</li>
    </ul>

    <h3>3.2 数据安全</h3>
    <ul>
        <li>数据受 iOS 系统的沙盒保护</li>
        <li>其他应用无法访问本应用的数据</li>
        <li>设备加密时，数据也会被加密</li>
    </ul>

    <h3>3.3 数据删除</h3>
    <ul>
        <li>卸载应用将自动删除所有本地数据</li>
        <li>应用内无"清除数据"功能，因为所有数据都存在本地</li>
        <li>无法恢复已删除的数据</li>
    </ul>

    <h2>4. 应用内购买</h2>

    <h3>4.1 购买处理</h3>
    <ul>
        <li>所有购买通过 Apple 的 StoreKit 框架处理</li>
        <li>我们不收集或存储支付信息</li>
        <li>购买状态通过 Apple 验证</li>
    </ul>

    <h3>4.2 购买数据</h3>
    <ul>
        <li>本地保存购买状态（已购买/未购买）</li>
        <li>可通过"恢复购买"功能恢复购买状态</li>
        <li>购买记录由 Apple 管理</li>
    </ul>

    <h2>5. 第三方服务</h2>

    <h3>5.1 Apple 服务</h3>
    <p>本应用使用以下 Apple 提供的系统服务：</p>
    <ul>
        <li><strong>App Store / StoreKit</strong>：应用内购买</li>
        <li><strong>Photos Framework</strong>：保存图片到相册</li>
        <li><strong>UIPasteboard</strong>：读取剪贴板</li>
    </ul>
    <p>这些服务受 Apple 隐私政策约束，详见：<a href="https://www.apple.com/legal/privacy/">https://www.apple.com/legal/privacy/</a></p>

    <h3>5.2 无其他第三方</h3>
    <ul>
        <li><span class="icon">✅</span> 不集成任何广告 SDK</li>
        <li><span class="icon">✅</span> 不集成任何分析工具</li>
        <li><span class="icon">✅</span> 不集成任何社交媒体 SDK</li>
        <li><span class="icon">✅</span> 不集成任何云服务</li>
    </ul>

    <h2>6. 儿童隐私</h2>
    <p>本应用不针对 13 岁以下儿童，但由于我们不收集任何个人信息，各年龄段用户均可安全使用。</p>

    <h2>7. 数据传输</h2>
    <ul>
        <li><span class="icon">❌</span> 不向任何第三方传输数据</li>
        <li><span class="icon">❌</span> 不向服务器传输数据</li>
        <li><span class="icon">❌</span> 不在设备间传输数据</li>
        <li><span class="icon">✅</span> 所有数据仅存在于您的设备</li>
    </ul>

    <h2>8. 您的权利</h2>

    <h3>8.1 数据控制</h3>
    <ul>
        <li>您完全控制应用内的所有数据</li>
        <li>可随时删除球员、阵容等数据</li>
        <li>可随时卸载应用删除所有数据</li>
    </ul>

    <h3>8.2 权限管理</h3>
    <ul>
        <li>可在 iOS 设置中管理应用权限</li>
        <li>拒绝权限不影响基本功能使用</li>
    </ul>

    <h2>9. 隐私政策变更</h2>

    <h3>9.1 更新通知</h3>
    <ul>
        <li>重大变更将在应用内通知</li>
        <li>更新日期将在文档顶部标注</li>
    </ul>

    <h3>9.2 持续承诺</h3>
    <ul>
        <li>我们承诺保持"不收集数据"的原则</li>
        <li>如未来需要收集数据，将事先征得您的明确同意</li>
    </ul>

    <h2>10. 联系我们</h2>
    <p>如对本隐私政策有任何疑问，请通过以下方式联系：</p>
    <ul>
        <li>App Store 应用页面反馈</li>
        <li>应用内设置页面</li>
    </ul>

    <h2>11. 法律依据</h2>
    <p>本隐私政策符合以下法律法规：</p>
    <ul>
        <li>《中华人民共和国个人信息保护法》</li>
        <li>Apple App Store 审核指南</li>
        <li>iOS 隐私要求</li>
    </ul>

    <hr style="margin: 40px 0;">
    <div class="highlight">
        <strong>总结：</strong>QuikeArray 是一款完全本地化的应用，不收集任何个人数据，不连接任何服务器，所有数据仅存储在您的设备上。您的隐私完全由您自己掌控。
    </div>
    <p style="text-align: center; color: #888; margin-top: 30px;">感谢您信任并使用 QuikeArray！</p>
</body>
</html>
```

---

## 第三步：上传文件到 GitHub

### 3.1 通过 GitHub 网页上传

1. 进入你的仓库页面
2. 点击 `Add file` → `Upload files`
3. 拖拽或选择 `terms.html` 和 `privacy.html`
4. 在底部填写提交信息：`Add terms and privacy pages`
5. 点击 `Commit changes`

### 3.2 通过 Git 命令行上传（可选）

```bash
# 克隆仓库
git clone https://github.com/你的用户名/quikearray-policies.git
cd quikearray-policies

# 复制 HTML 文件到此目录
# 然后提交
git add terms.html privacy.html
git commit -m "Add terms and privacy pages"
git push
```

---

## 第四步：启用 GitHub Pages

### 4.1 配置 Pages

1. 进入仓库的 `Settings`
2. 左侧菜单找到 `Pages`
3. 在 `Source` 部分：
   - Branch: 选择 `main`（或 `master`）
   - Folder: 选择 `/ (root)`
4. 点击 `Save`

### 4.2 等待部署

- GitHub 会自动构建和部署（通常 1-3 分钟）
- 完成后会显示网站地址：
  ```
  https://你的用户名.github.io/quikearray-policies/
  ```

---

## 第五步：更新应用中的链接

### 5.1 获取最终 URL

你的协议页面 URL 将是：
- **用户协议**: `https://你的用户名.github.io/quikearray-policies/terms.html`
- **隐私政策**: `https://你的用户名.github.io/quikearray-policies/privacy.html`

### 5.2 在 SettingsView.swift 中更新

将代码中的链接替换为你的 GitHub Pages URL：

```swift
// 关于部分
Section(header: Text("关于")) {
    Link(destination: URL(string: "https://你的用户名.github.io/quikearray-policies/terms.html")!) {
        HStack {
            Image(systemName: "doc.text")
            Text("用户协议")
            Spacer()
            Image(systemName: "arrow.up.right.square")
                .font(.caption)
                .foregroundColor(.gray)
        }
    }
    
    Link(destination: URL(string: "https://你的用户名.github.io/quikearray-policies/privacy.html")!) {
        HStack {
            Image(systemName: "lock.shield")
            Text("隐私政策")
            Spacer()
            Image(systemName: "arrow.up.right.square")
                .font(.caption)
                .foregroundColor(.gray)
        }
    }
    
    HStack {
        Text("版本")
        Spacer()
        Text(Bundle.main.infoDictionary?["CFBundleShortVersionString"] as? String ?? "1.0")
            .foregroundColor(.gray)
    }
}
```

---

## 第六步：测试

### 6.1 测试链接

在浏览器中访问：
- https://你的用户名.github.io/quikearray-policies/terms.html
- https://你的用户名.github.io/quikearray-policies/privacy.html

### 6.2 测试应用

1. 在模拟器或真机运行应用
2. 进入设置页面
3. 点击"用户协议"和"隐私政策"
4. 确认能够正确打开网页

---

## 后续维护

### 更新协议内容

1. 在 GitHub 仓库中编辑 HTML 文件
2. 提交更改
3. GitHub Pages 会自动更新（1-3 分钟）
4. 应用中的链接会立即显示新内容

### 添加自定义域名（可选）

如果你有自己的域名：
1. 在 GitHub Pages 设置中添加自定义域名
2. 配置 DNS CNAME 记录
3. URL 会变成：`https://你的域名.com/terms.html`

---

## 注意事项

### ✅ 优点
- 完全免费
- 自动 HTTPS
- 易于维护
- 符合 Apple 审核要求

### ⚠️ 注意
- 仓库必须是 Public（公开）
- 链接必须是 HTTPS（GitHub Pages 自动支持）
- 首次部署需要等待几分钟

### 📝 App Store 审核
在提交应用时，Apple 可能会检查：
- 用户协议链接是否有效
- 隐私政策是否完整
- HTTPS 是否正常工作

使用 GitHub Pages 完全符合这些要求！

---

## 常见问题

**Q: GitHub Pages 会过期吗？**
A: 不会，只要仓库存在，GitHub Pages 就会一直可用。

**Q: 可以使用私有仓库吗？**
A: 不可以，GitHub Pages 需要公开仓库（免费版）。

**Q: 可以使用中文域名吗？**
A: 建议使用英文，但内容可以是中文。

**Q: 需要备案吗？**
A: 使用 GitHub Pages 不需要备案。

---

## 快速检查清单

上线前确认：
- [ ] 创建 GitHub 仓库
- [ ] 上传 terms.html 和 privacy.html
- [ ] 启用 GitHub Pages
- [ ] 测试页面可访问
- [ ] 更新应用中的链接
- [ ] 在真机测试链接跳转
- [ ] 确认 HTTPS 正常

完成以上步骤，你的用户协议和隐私政策就可以正式使用了！
