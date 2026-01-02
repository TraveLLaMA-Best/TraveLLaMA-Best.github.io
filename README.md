# TraveLLaMA Project Page

🦙 **TraveLLaMA: A Multimodal Travel Assistant with Large-Scale Dataset and Structured Reasoning**

AAAI 2026 论文官方项目主页

## 📁 项目结构

```
TraveLLaMA-Best.github.io/
├── index.html              # 主页面
├── README.md               # 本文件
└── static/
    ├── css/
    │   ├── bulma.min.css      # Bulma CSS 框架
    │   ├── fontawesome.all.min.css
    │   └── index.css          # 自定义样式
    ├── js/
    │   └── fontawesome.all.min.js
    └── images/                # 需要添加的图片
        ├── teaser.png         # 首图 (对应 first_travel.pdf)
        ├── dataset.png        # 数据集图 (对应 okkkkkkk.pdf 或 map.pdf)
        ├── method.png         # 方法图 (对应 CoT_dataset.pdf)
        ├── agent.png          # Agent架构图 (对应 good.pdf)
        └── comparison.png     # 对比图 (对应 chat.pdf)
```

## 🖼️ 需要添加的图片

请将论文中的 PDF 图片转换为 PNG 格式，并放入 `static/images/` 目录：

| 文件名 | 对应论文图片 | 说明 |
|--------|-------------|------|
| `teaser.png` | `first_travel.pdf` | 论文首图，展示 TraveLLaMA 系统概览 |
| `dataset.png` | `okkkkkkk.pdf` 或 `new_map_all.pdf` | 数据集全球分布图 |
| `method.png` | `CoT_dataset.pdf` | 数据构建和训练流程图 |
| `agent.png` | `good.pdf` | Agent 推理和规划架构图 |
| `comparison.png` | `chat.pdf` | TraveLLaMA vs Claude 3.5 对比图 |

### PDF 转 PNG 方法

1. **使用 macOS Preview**:
   - 打开 PDF 文件
   - File → Export → 选择 PNG 格式

2. **使用命令行** (需要安装 ImageMagick):
   ```bash
   convert -density 300 input.pdf output.png
   ```

3. **在线工具**: [CloudConvert](https://cloudconvert.com/pdf-to-png)

## 🚀 本地预览

```bash
cd TraveLLaMA-Best.github.io
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 🌐 部署到 GitHub Pages

1. 创建 GitHub 仓库 `TraveLLaMA-Best.github.io`
2. 上传所有文件
3. 在仓库 Settings → Pages → Source 选择 `main` 分支
4. 访问 `https://travellama-best.github.io`

## ✏️ 自定义修改

- **颜色主题**: 编辑 `static/css/index.css` 中的 `:root` CSS 变量
- **论文链接**: 在 `index.html` 中更新 arXiv/GitHub/Dataset 链接
- **作者链接**: 在作者姓名处添加个人主页链接

## 📄 License

This website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

