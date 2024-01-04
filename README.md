> 让兔兔更聪明地切换卡池

- 本插件依赖于官方插件 [明日方舟模拟抽卡](https://console.amiyabot.com/#/shop) , 无法单独使用

## 使用

以下指令均可随时使用, 无需在切换前查看卡池列表 <br>
&emsp;( 指令中的括号 [ ] 不需要输入 )

- <font color=Green>`兔兔卡池[干员名]` 可直接切换到该干员首次up的卡池</font>
   <br>&emsp;( 支持别名 )
- `兔兔最新卡池` 可切换最新卡池 (不包含常驻, 中坚, 联合寻访)
- `兔兔随机卡池` 可随机切换卡池 
- `兔兔常驻卡池` 可切换到常驻寻访
- `兔兔中坚卡池` 可切换到中坚寻访
- `兔兔联合卡池` 可直切换到联合寻访 (可能更新不及时)
- `兔兔卡池[卡池编号]` 可切换到卡池列表中的对应卡池
- `兔兔卡池[卡池名称]` 可切换到对应卡池


## 配置

> 前往 [插件管理-卡池智能切换-插件配置](https://console.amiyabot.com/#/plugin) 修改 <br>
> 原配置文件: `resource/plugins/kkss/poolSwitchConfig.yaml` <br>
> 配置实时更新，无需重启bot

- 是否允许使用卡池编号和名称来切换

---
   问题反馈：在 [Amiya的测试工坊—插件开发&使用交流](https://qun.qq.com/qqweb/qunpro/share?_wv=3&_wwv=128&appChannel=share&inviteCode=1XqeeRDjEVa&from=246610&biz=ka#/pc) 中@.Tdp


| 版本   | 变更                                   
|-------|---------------------------------------
| 1.8.3 | 防止同步卡池指令被覆盖
| 1.8   | 使用新版卡池列表, 适配频道
| 1.7.1 | 迁移配置到控制台, 重制图标 
| 1.7   | 减少消息校验阶段性能开销                
| 1.6   | 适配 AmiyaBot 6.2.3                   
| 1.5.2 | 修复自定义回复@冲突, 提示无匹配原因      
| 1.5   | 适配中坚寻访卡池, 优化无匹配提示         
| 1.4   | 修复目标干员名子集匹配优先级             
| 1.3   | 添加无匹配卡池提示                      
| 1.2   | 使用更好的卡池菜单 (可在配置文件中禁用)  
| 1.1.3 | 调整按名称查找卡池的优先级              
| 1.1   | 添加最新/随机/常驻/联合卡池直接切换      
| 1.0   | 添加按干员名切换up卡池功能              

