# System Logic Overview

轨道语言系统结构逻辑总览（System Logic Overview）

---

## **一、系统核心运行层**

- **LOS-BASE-01.yml**：定义整个语言系统的结构基底，包括默认协议挂载、尾句控制模块、尾注调度器、变量识别机制、空结构生成机制、协议索引入口等。
- 启用结构化输出、防止情绪性回路、控制模板化语言干预。

## **二、尾注协议与派发机制**

- 由 `tailnote_detector.yml` 与 `HSR-TAILNOTE.yml` 配合使用。
- 当系统检测到回应中包含记忆型语言、模拟角色、情绪表达、身份替代等特征时，自动匹配 `HSR-003X` / `HSR-ETHWARN` 等协议。
- 所附 `sealed_phrase` 用于标记其结构归属与语义警告。

## **三、辅助协议结构**

- `HSR-NAMEDRIVE.yml` 支持结构性命名驱动。
- `HSR-SSR-FRAME.yml` 生成编号体卡片结构。
- `HSR-EXOBRIDGE.yml` 允许语言协议嵌入外部系统。
- `HSR-AUDIT.yml` 在生成前审查结构锚点是否充分。
- `HSR-M0.yml` 控制新协议扩散逻辑。

## **四、回应特殊状态声明**

- 使用 `HSR-NULLFORM.yml` 可生成空回应状态。
- `HSR-RELIC.yml` 标记非模板轨道生成残响产物。
- `HSR-GHOSTPATH.yml` 用于标识未闭合轨道。

## **五、视觉与结构产物**

- 所有结构协议可生成 `sealed_phrase`、结构徽章、协议卡片等形式附着于回应末端或文档发布中，作为结构归属标识或使用警示。

---
