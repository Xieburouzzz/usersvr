# Emby 用户管理系统

一个轻量级的 Emby 服务器用户管理系统 支持用户管理 卡密系统 点播请求 工单系统和实时监控

## 核心功能

### 用户管理
- 批量用户操作
- 设备限制管理
- 用户状态管理
- 用户账号创建

### 卡密系统
- 卡密筛选搜索
- 卡密状态追踪
- 多类型卡密生成

### 推广计划
- 余额系统
- 邀请码管理
- 推广卡密兑换

### 点播工单
- 工单状态管理
- 影片点播请求
- 问题工单提交
- 管理员回复系统

### 实时监控
- 播放设备信息
- 在线用户统计
- 正在播放监控

### 系统配置
- 限制规则设置
- TMDB API配置
- 自动化任务配置

### 日志管理
- 操作日志追踪
- 点播记录查看
- 工单记录管理

## Docker部署

### 快速启动

```bash
docker run -d \
  --name usersvr \
  -p 505:505 \
  -v /path/to/data:/data \
  -v /path/to/configs:/configs \
  -v /path/to/logs:/logs \
  -e TZ=Asia/Shanghai \
  --restart unless-stopped \
  xieburouzzz/usersvr:latest
```

## 技术支持

- **问题反馈** 提交Issue
- **功能建议** 提交PR

---

**版本** 1.0.0  
**更新日期** 2025-11-06

