# Yuan's Learning Notes

互動式技術學習筆記，以第一性原理拆解雲端可觀測性與 APM 相關概念。

**GitHub Pages:** https://yuandesu.github.io/learning-notes/

---

## 筆記列表

### 基礎架構
- **ECS / Fargate Agent 部署架構比較** — 從實體硬體到容器，拆解三種部署架構差異
- **Forwarder vs Extension** — Datadog Forwarder 與 Lambda Extension 的差異比較

### 語言 / Tracer
- **JVM、JAR 與 -javaagent** — 為什麼更新 dd-java-agent.jar 後必須重啟 JVM
- **Lambda Web Adapter + Orchestrion** — Go tracer 在 LWA 上 trace 送不出去的根本原因
- **Java Tracer SQL 擷取流程** — APM 如何從 JDBC 層攔截並正規化 SQL（含互動模擬器）

### APM 概念
- **Span Sampling 完全理解** — Head/Tail-based sampling 與 Ingestion Control 完整拆解
- **LLM Observability 完整指南** — LLM 應用的可觀測性核心概念與實作
- **APM Tagging 完全理解** — 5 層 telemetry 結構與 tag 繼承規則

### 事件調查
- **APM Trace 消失 23 小時調查** — Trace 消失但 Log 正常的根因分析
---