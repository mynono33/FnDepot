# tailscale-fnos
描述: 基于官方tailscale v1.94.2文件打包和设计UI适配飞牛fnOS上运行
**UI功能:**
- **概述:** 展示运行状态信息，实时流量图
- **连接:** 支持apikey和web认证登陆，设备名、子路由和出口节点设置
- **设备:**
   1. 设备列表：可显示每个peer详细连接信息，总使用流量，且可选择某个peer作为出口节点
   2. 网络拓扑：节点连接关系可视化，支持拖拽
   3. ping测试：长ping节点测试，原味复刻官方移动端app功能
- **设置：**
   1. Login server 自定义（兼容Headscale）
   2. 高级设置：DNS、shields up模式设置
   3. Log日志查看
