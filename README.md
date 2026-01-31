# IB 艺术留学申请追踪系统 | IB Art Application Tracker

一个帮助 IB 学生追踪艺术设计专业大学申请进度的本地网页应用。

## 🚀 快速开始

### 方法一：直接打开
双击 `index.html` 文件，在浏览器中打开即可使用。

### 方法二：本地服务器（推荐）
```bash
cd /home/ubuntu/clawd/ib-art-tracker
python3 -m http.server 8080
```
然后访问 http://localhost:8080

## ✨ 功能特性

### 📊 仪表盘
- 申请倒计时
- TOEFL/作品集/CAS 进度一览
- 待办事项管理
- 整体进度可视化

### 🏫 学校管理（17所预置）
**美国 10所：**
- RISD 罗德岛设计学院
- SAIC 芝加哥艺术学院
- Parsons 帕森斯设计学院
- Pratt 普瑞特艺术学院
- SVA 纽约视觉艺术学院
- CalArts 加州艺术学院
- CCA 加州艺术学院(旧金山)
- MICA 马里兰艺术学院
- SCAD 萨凡纳艺术学院
- ArtCenter 艺术中心设计学院

**欧洲 7所：**
- RCA 皇家艺术学院 (英国)
- UAL 伦敦艺术大学 (英国)
- Goldsmiths 金史密斯学院 (英国)
- ArtEZ (荷兰)
- Design Academy Eindhoven (荷兰)
- Aalto University (芬兰)
- ECAL (瑞士)

### 🎨 作品集管理
- 添加/编辑/删除作品
- 追踪完成进度
- 记录类型、媒介、导师反馈

### 📈 成绩追踪
- TOEFL 分数历史
- IB 各科预估分
- CAS 小时数统计
- 竞赛/奖项记录

### 📅 时间线
- 重要日期管理
- 申请截止日追踪
- 任务完成状态

### ⚙️ 设置
- 中英双语切换
- 数据导出/导入 (JSON)
- 作品集目标数量设置
- 申请截止日期设置

## 💾 数据存储

所有数据存储在浏览器的 localStorage 中：
- `ib-tracker-data` - 主数据
- `ib-tracker-lang` - 语言设置
- `ib-tracker-portfolio-target` - 作品集目标
- `ib-tracker-deadline` - 申请截止日期

## 📤 数据同步

### 手动同步
1. 在设置页面点击「导出数据」
2. 保存 JSON 文件
3. 在另一设备点击「导入数据」选择文件

### GitHub 同步（计划中）
### Notion 同步（计划中）

## 🔧 技术栈

- Vue 3 (CDN)
- Tailwind CSS (CDN)
- 纯前端，无需后端

## 📝 License

MIT
