# 超核文化传媒官网

静态网站，部署在 GitHub Pages。

## 部署步骤

1. 创建 GitHub 仓库（名称随意，如 `chaohewenhua-website`）
2. 推送代码到仓库
3. 仓库 Settings → Pages → Source 选择 `main` 分支
4. 修改 CNAME 文件为你的实际域名
5. 阿里云 DNS 解析配置：
   - 添加 CNAME 记录，指向 `你的用户名.github.io`

## 文件说明

- `index.html` - 主页面（含 JSON-LD 结构化数据）
- `CNAME` - 自定义域名配置
- `.nojekyll` - 禁用 Jekyll 处理
