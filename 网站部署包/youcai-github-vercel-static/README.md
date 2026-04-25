# 中山优才教育｜家庭教育指导师落地页

这是一个可直接部署到 Vercel 的静态官网项目。

## 文件说明

- `index.html`：网站首页，已包含页面结构、样式、交互和 FAQ 结构化数据
- `vercel.json`：Vercel 静态部署配置

## 部署方式

### 方式一：GitHub + Vercel

1. 在 GitHub 新建仓库，例如：`youcai-family-education-page`
2. 将本项目所有文件上传到仓库根目录
3. 登录 Vercel
4. 点击 `Add New` → `Project`
5. 选择刚创建的 GitHub 仓库
6. Framework Preset 选择 `Other`
7. Build Command 留空
8. Output Directory 留空或填写 `.`
9. 点击 `Deploy`

### 方式二：Vercel CLI

```bash
npm i -g vercel
vercel --prod
```

## 上线前建议替换

- 客服电话：`400-XXX-XXXX`
- 公司地址：`广东省中山市`
- 证书查询说明
- 企业微信/在线客服链接
- 隐私政策
- ICP 备案号（如部署到中国大陆服务器或使用大陆 CDN）

## 注意

当前表单为前端演示，不会真实保存用户提交内容。正式上线前建议接入：

- 企业微信客服
- 飞书表单 / 金数据
- Vercel Forms 替代方案
- 自建接口和数据库
