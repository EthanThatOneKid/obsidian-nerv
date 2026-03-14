# NERV Terminal FUI: Operator's Manual v2.0

Welcome to the Forensic Reconstruction of the NERV Command Center interface. This system is designed for maximum information density and immersion.

## I. Operational Tiers

### **1. Command Center (Global)**
- **Aesthetic**: Pattern Blue accents and high-contrast countdowns.
- **CRT Simulation**: 2.5px pitch scanlines and RGB phosphor-bleed are applied globally.

### **2. Entry Plug (Tactical)**
- **Trigger**: Tactical tags like `#alert/angel` shift the environment.
- **Alert Levels**:
    - **Pattern Blue (#alert/angel)**: High-level detection state.
    - **Pattern Red (#alert/terminal)**: Emergency state with a **10Hz industrial flicker**.

### **3. MAGI (Strategic)**
- **Status Readouts**: Use monospaced JetBrains Mono for all diagnostic logs and UI labels.
- **Typography**: Matisse EB headers are mechanically compressed (`scaleX(0.85)`) to evoke the "urgency motif" of the original Tokyo-3 terminals.

## II. Tag-Driven Logic

Add the following tags to your note properties (YAML) to shift the UI state:

| Tag | State | Visual Effect |
| :--- | :--- | :--- |
| `#alert/angel` | Pattern Blue | Blue tint + Solid 3px border |
| `#alert/terminal` | Pattern Red | Red tint + **10Hz Flicker** |
| `#status/diagnostic` | Monospaced | High-density data layout |

## III. Layout Principles

- **Industrial Brutalism**: `border-radius` is set to `0px` across the entire application.
- **Data Saturation**: Padding and margins are minimal to simulate "The Burden of Knowledge."
- **Viewport Brackets**: Each workspace leaf is framed by HUD-style angular brackets.

---
*NERV Technical Department - Operational Integrity Guaranteed*
