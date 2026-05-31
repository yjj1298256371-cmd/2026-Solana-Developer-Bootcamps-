# 海冬青学术 Songkoro Academic · 官网

一站式科研服务平台官网（静态站点）。专注科研项目孵化、学术背景提升、论文润色与期刊投稿支持，
服务本科生、硕士生、博士申请者及青年研究者。

## 页面结构

| 文件 | 栏目 | 说明 |
|------|------|------|
| `index.html` | 首页 | 服务总览、服务对象、优势、CTA |
| `journals.html` | 期刊发表 | 期刊匹配查询 + 卡片（筛选可用） |
| `conferences.html` | 学术会议 | 会议投稿查询 + 卡片（筛选可用） |
| `translation.html` | 论文翻译润色 | 定价、在线估价、案例对比（标签可切换） |
| `prereview.html` | 预审评估 | 三种预审对比、评估报告说明 |
| `detection.html` | 论文检测 | 查重 + AIGC 检测与改写优化 |
| `background.html` | 科研背景提升 | 栏目页（内容待补） |
| `news.html` | 学术资讯 | 栏目页（内容待补） |
| `cooperation.html` | 资源合作 | 栏目页（内容待补） |
| `about.html` | 关于我们 | 公司介绍、服务对象、合规承诺 |
| `assets/site.css` | — | 新页面共享样式（设计令牌沿用既有页面） |
| `assets/logo.png` | — | 站点 Logo |

导航栏在各页之间已互相打通，"论文服务"为下拉菜单（翻译润色 / 预审评估 / 论文检测）。

## 本地预览

```bash
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000/index.html
```

## 待办（需业务方提供真实信息后替换）

- 真实电话、邮箱、公众号二维码（目前为占位）
- 真实期刊 / 会议 / 案例 / 价格数据
- 各「立即咨询 / 提交稿件」按钮对接后端表单
- `background.html` / `news.html` / `cooperation.html` 补充正式内容与案例
- 去除各页 `<title>` 中的"（页面示意）"标注（旧页面）
