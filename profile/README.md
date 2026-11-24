# LumiStory

**一台自己的电脑上，一个会记住你、会管机器、动手前先问的常驻伙伴。**

*A resident companion for one Linux machine — it remembers, it maintains, and it asks before it acts.*

---

## 这里有什么

| 仓库 | 是什么 |
|---|---|
| [`lumi`](https://github.com/lumistory/lumi) | 主项目。跑在本机的常驻智能体：记忆、认知循环、工具面、子代理、聊天通道。Rust，cargo workspace。 |
| [`linux-intelligence`](https://github.com/lumistory/linux-intelligence) | 扩展。独立的 Linux 系统观察、操作审计与恢复基础设施，不依赖 Lumi，也不绑定任何模型。 |

两个仓库的关系是：`lumi` 是主体，`linux-intelligence` 是它可以接入的一种能力，但不是它的前提 —— 后者能单独跑，前者不装它也能跑。

## 两条设计取向

**证据分级，不猜因果。** 模型自己说的话只算推断，权重为零，永远不会自己升级成「已确认」。要确认必须有外部证据：用户说过的话、工具真跑出来的输出、内核观察到的状态。时间上的先后不叫因果。

**确定性的程序负责观察和执行，模型负责理解和建议。** 危险操作先过闸门，恢复操作也要过。模型不能绕过。

## 现状

两个仓库都是私有，正在开发中。没有发布，没有安装包，接口还在动。

---

<sub>组织登录名只能小写，所以 URL 是 `lumistory`；显示名是 `LumiStory`。</sub>
