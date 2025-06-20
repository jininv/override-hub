# 自用 mihomo 覆写配置和 sub-store 组合订阅模板
根据Seameee/override-hub做了一些修改

### sub-store 懒人配置
预置了 sub-store 的懒人配置，导入后添加你的订阅就能使用
1. 组合订阅模板
   - 功能包括：
     - 节点重命名
     - 节点排序
     - 去除风险节点
     - 替换旗帜
     - IPv6 入口解析（可选）
     - 多机场流量信息整合
     - 家宽/落地节点自动设置代理链（可选）
   - 使用方法：
     - 在 sub-store 订阅管理页面，添加自己的机场订阅
     - 在 sub-store 订阅管理页面，点击左上角 ➕ 号
     - 将 [sub-store组合订阅模板](https://raw.githubusercontent.com/jininv/override-hub/refs/heads/main/sub-store组合订阅模板.json) 导入本地配置
     - 选择需要整合的机场订阅并保存

2. 托管配置模板
   - 使用方法：
     - 在 sub-store 文件管理页面，点击左上角 ➕ 号
     - 将 [mihomo配置](https://raw.githubusercontent.com/jininv/override-hub/refs/heads/main/mihomo配置.json) 导入本地配置

