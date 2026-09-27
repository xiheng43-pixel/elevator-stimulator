# elevator-stimulator
this small and fun stimulator lets you experience the elevator experience for people who wants to ride in an elevator!
# 双梯嵌入式电梯模拟系统 (Elevator Simulator)

这是一个基于原生 HTML5/CSS3/JavaScript 实现的双梯交互模拟器，演示了嵌入式系统中**有限状态机 (FSM)** 与**多电梯调度算法 (SCAN)** 的基本工作原理。

## 🌟 项目亮点

- **状态机控制**：电梯具有 `IDLE(待机)`、`UP(上行)`、`DOWN(下行)`、`DOOR_OPEN(开门)` 4种状态转换。
- **双梯并行**：采用贪婪调度算法，自动分配距离最近的电梯响应呼叫。
- **可视化交互**：动画演示乘客进出轿厢及电梯上下平滑移动过程。

## 🚀 在线体验

👉 [点击在线体验电梯模拟器](https://你的用户名.github.io/elevator-simulator/)

## 🛠️ 技术栈

- **前端技术**：HTML5, CSS3 (CSS Variables, Flexbox, Transitions), JavaScript (ES6+ OOP)
- **底层原理**：嵌入式状态机模型 (FSM)、计算机算法设计
