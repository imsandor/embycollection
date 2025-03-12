# Emby Collector
一个为emby服集邮佬提供直观展示集邮成果的Web界面

## 🌟 功能特点

### 📡 服务器管理
- 支持添加、编辑、删除服务器
- 支持多线路配置(直连/代理)
- 服务器信息完整展示
- 回收站功能

### ⏰ 提醒功能
- 添加服务器的保号方式
- 观看记录到期提醒
- 手动更新单个服务器的观看记录
- 批量更新观看记录
- 剩余天数可视化展示

### 🎨 图标管理
- 支持多图标包
- 图标搜索功能
- 在线预览图标
- 自定义图标URL

### 💾 数据管理
- 数据导入/导出
- 本地持久化存储
- JSON格式备份


## 🛠️ 技术栈

- Vue 3 
- Tailwind CSS
- Font Awesome
- Vue Draggable
- LocalStorage

## 📖 使用方法

1. 使用浏览器打开html文件
2. 点击"添加服务器"添加Emby服务器
3. 配置服务器信息
4. 通过设置页面导入/导出数据

## 💽 数据存储

LocalStorage存储项:
- `embyServers`: 服务器列表
- `embyTrash`: 回收站数据
- `embyIconPackages`: 图标包配置
- `darkMode`: 暗黑模式设置

## ⚠️ 注意事项

1. 请定期导出数据备份
2. 清除浏览器数据会导致配置丢失
3. 建议使用现代浏览器访问

## ⚠️ 重要

1. 本项目为纯前端项目，不包含任何服务器信息，所有服务器信息由用户自行添加
2. 请不要在任何场合泄露和展示Emby服地址
3. 请不要在中国大陆地区宣传



## 🤝 感谢

这个项目本身是为了方便自己记录和管理信息的，我的代码功底薄弱，也是借此机会实践。
如果你感觉好用，欢迎你分享给其他人，如果能点下stars就更好了。
又如果你恰好财力雄厚，也可以 buy me a coffee

<p align="center">
  <img src="https://github.com/imsandor/embycollector/blob/main/coffee.png" alt="coffee" width="400" />
</p>


