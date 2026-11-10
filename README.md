# usaqi-pet

A small animated desktop companion for Windows. Take a focus break, offer a snack, or let Usagi wander across your screen.

System Requirements

- Windows 10 or Windows 11.
- .NET Framework 4.x; version 4.8 or later is recommended.
- A mouse or another pointing device supporting dragging and right-clicking.

This version does not support macOS or Linux. Compatibility across all display configurations and Windows devices has not been independently verified.
Controls

| Input | Result |
| --- | --- |
| Click the head | Play the head-pat reaction |
| Click the body | Poke the pet; repeated pokes can trigger anger |
| Drag and release | Place the pet at that position without dropping it |
| Drag to a screen edge and release | Dock at the left, right, or top edge when docking is enabled |
| Hover over a docked pet | Reveal the pet |
| Quickly shake left and right while dragging | Trigger dizziness and recovery |
| Right-click the pet | Open the floating interaction menu |
| Double-click the tray avatar | Bring the pet back to a visible location |
| Right-click the tray avatar | Open the traditional tray menu |

Use the **飞出去** (Fly Out) action to launch the pet intentionally. Ordinary dragging does not throw it.

Docking only happens when the user places the pet at an edge. Autonomous walking or climbing does not trigger docking.

## Menu Guide

| Chinese label | English meaning |
| --- | --- |
| 摸摸头 | Head Pat |
| 坐下 | Sit Down |
| 打瞌睡 | Doze |
| 飞出去 | Fly Out |
| 投喂道具 / 投喂与道具 | Snacks and Items |
| 陪伴专注 | Focus Session |
| 散步 | Start Roaming |
| 更多 | More |
| 停止散步 | Stop Roaming |
| 贴边开关：开 / 关 | Edge Docking: On / Off |
| 随机动作：开 / 关 | Random Activities: On / Off |
| 一键找回 | Retrieve Pet |
| 返回 | Back |
| 退出 | Exit |

Random activities are enabled by default. Turn them off under **更多** (More) if you want the pet to remain where you place it. Toggle settings apply to the current session and are not saved between launches.

Automatic activities pause during focus sessions, dragging, docking, and menu interaction. Manual actions take priority. Manually started roaming continues until stopped or interrupted by another action.

### Snacks and Items

| Item | Animation |
| --- | --- |
| 胡萝卜 — Carrot | Hold, bite, chew, and smile |
| 甜甜圈 — Doughnut | Lift, take a bite, and enjoy |
| 布丁 — Pudding | Scoop with a spoon and eat |
| 咖啡 — Coffee | Sip, perk up, and bounce |
| 星星棒 — Star Wand | Wave the wand and create a trail of stars |

Each item finishes with a short sequence that lowers the prop, returns the paws to rest, and restores the standing pose. During a focus session, the pet returns to sitting instead.
