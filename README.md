# 李安｜ 电气自动化 → 工业自动化 / 智能制造方向

电气自动化技术专业应届生（专业排名前 5%，持电工三级/高级工证书），围绕**"从 PLC 到云"的完整技术栈**独立开发 **13 个工业自动化开源项目**，全部含 CI、测试与成套工程文档。

🎯 **求职方向**：智能制造系统 / 电气自动化 / 设备调试与售后 助理工程师 ｜ 广东 · 可驻场出差 ｜ 简历可向本人索取

## 🗂️ 项目索引（按方向）

- 🔌 **电气 / PLC**：[PLC-Robot-Integration](https://github.com/lian-automation/PLC-Robot-Integration)（S7-1200+ABB 码垛单元虚拟调试）· [Electrical-Equipment-Maintenance-System](https://github.com/lian-automation/Electrical-Equipment-Maintenance-System)（维保体系文档包）· [Virtual-Smart-Factory](https://github.com/lian-automation/Virtual-Smart-Factory)（旗舰整合）
- 🎛️ **过程 / 运动控制**：[Water-Treatment-PID-Control-Simulation](https://github.com/lian-automation/Water-Treatment-PID-Control-Simulation) · [Building-Automation-DDC-Simulation](https://github.com/lian-automation/Building-Automation-DDC-Simulation) · [Gantry-Sync-Cam-Simulation](https://github.com/lian-automation/Gantry-Sync-Cam-Simulation)
- 🤖 **调度 / 视觉 / 分布式**：[Multi-AGV-Dispatch-Simulation](https://github.com/lian-automation/Multi-AGV-Dispatch-Simulation) · [Machine-Vision-Inspection-System](https://github.com/lian-automation/Machine-Vision-Inspection-System) · [IEC61499-Distributed-Industrial-Control-System](https://github.com/lian-automation/IEC61499-Distributed-Industrial-Control-System)
- ☁️ **IoT / 云边 / 数据**：[Digital-Twin-Predictive-Maintenance-Platform](https://github.com/lian-automation/Digital-Twin-Predictive-Maintenance-Platform) · [Cloud-Edge-Industrial-Control-Platform](https://github.com/lian-automation/Cloud-Edge-Industrial-Control-Platform) · [Industrial-IoT-Edge-Gateway-System](https://github.com/lian-automation/Industrial-IoT-Edge-Gateway-System) · [Smart-Factory-Data-Acquisition-System](https://github.com/lian-automation/Smart-Factory-Data-Acquisition-System)

## 🚀 快速开始：2 分钟复跑旗舰项目

```bash
git clone https://github.com/lian-automation/Virtual-Smart-Factory.git
cd Virtual-Smart-Factory
pip install -r requirements.txt      # numpy / flask / pymodbus
python selftest.py                   # 17 用例全厂自检 + 600s 加速联跑，报告落 reports/
python main.py --web --speed 10      # 浏览器打开 http://127.0.0.1:5080 看实时监控大屏
```

🔭 每个指标的生成命令与输出位置：旗舰仓 **[REPRODUCE.md](https://github.com/lian-automation/Virtual-Smart-Factory/blob/main/REPRODUCE.md)**

**作品集纪律**：所有指标为仿真验证值（如实标注，不冒充现场数据）；每条 CI 命令本地预跑绿才写入；每个数字都能在仓库内找到生成它的脚本与报告。欢迎 clone 复跑。

📮 2156791374@qq.com ｜ 📱 15089590118
