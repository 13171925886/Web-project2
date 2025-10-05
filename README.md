# Elite Sports 精英体育

一个现代化的体育综合平台，提供赛事信息、运动员展示、训练服务和装备商城。

## 项目特色

- 🏆 **专业赛事** - 足球、篮球、网球等多项顶级赛事
- 👥 **精英运动员** - 签约运动员档案和专业技能展示  
- 🏃‍♂️ **科学训练** - 体能、技术、心理三位一体训练体系
- 🛍️ **专业装备** - 精选运动装备，品质保障

## 技术栈

- HTML5 + CSS3 + JavaScript
- 响应式设计，支持多设备
- 现代化深色主题
- SVG矢量图标

## 项目结构

```
├── index.html              # 首页
├── assets/                 # 静态资源
│   ├── css/style.css      # 样式文件
│   ├── js/main.js         # 脚本文件
│   └── images/            # 图片资源
└── pages/                 # 页面目录
    ├── about.html         # 关于我们
    ├── events.html        # 赛事
    ├── athletes.html      # 运动员
    ├── training.html      # 训练
    ├── shop.html          # 商城
    └── contact.html       # 联系
```

## 快速开始

1. **下载项目**
   ```bash
   # 下载或克隆项目到本地
   ```

2. **启动服务**
   ```bash
   # 方式一：直接打开 index.html
   # 方式二：使用本地服务器
   python -m http.server 8000
   # 或
   npx serve .
   ```

3. **访问网站**
   ```
   http://localhost:8000
   ```

## 页面功能

### 首页 (index.html)
- 品牌展示和导航
- 运动项目介绍（足球、篮球、网球）
- 即将到来的赛事时间线
- 训练营报名入口

### 关于我们 (about.html)
- 公司使命、愿景、价值观
- 品牌理念展示

### 赛事 (events.html)
- 赛事日历展示
- 购票功能入口
- 赛事详情介绍

### 运动员 (athletes.html)
- 签约运动员档案
- 专业技能介绍
- 运动项目分类

### 训练 (training.html)
- 精英训练营介绍
- 训练模块说明（体能、技术、心理）
- 报名联系方式

### 商城 (shop.html)
- 专业运动装备展示
- 产品分类和介绍
- 购买功能入口

### 联系 (contact.html)
- 联系表单
- 公司地址和邮箱
- 商务合作信息

## 设计特点

- **深色主题** - 专业的深色配色方案
- **渐变效果** - 现代化渐变背景和按钮
- **卡片布局** - 清晰的信息层次
- **响应式** - 适配桌面、平板、手机

## 自定义修改

### 修改品牌信息
在 `index.html` 中修改标题和Logo：
```html
<title>Elite Sports · 精英体育</title>
<a class="logo" href="/">Elite<span>Sports</span></a>
```

### 调整主题色彩
在 `assets/css/style.css` 中修改CSS变量：
```css
:root {
  --bg: #0b0f14;        /* 背景色 */
  --brand: #2aa9ff;     /* 主品牌色 */
  --brand-2: #7c5cff;   /* 辅助品牌色 */
  --accent: #00d1b2;    /* 强调色 */
}
```

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 联系方式

- 商务合作：biz@elitesports.example
- 训练咨询：train@elitesports.example
- 客服支持：support@elitesports.example
- 媒体联系：contact@elitesports.example

## 许可证

© 2025 Elite Sports. All rights reserved.

---

**Elite Sports** - 卓越之上，精英之选