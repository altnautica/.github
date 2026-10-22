<p align="center">
  <a href="https://altnautica.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/brand/altnautica-wordmark-dark.svg">
      <img src="./assets/brand/altnautica-wordmark-light.svg" alt="Altnautica" width="260">
    </picture>
  </a>
</p>
<h3 align="center">The Open Compute Layer for Drones</h3>
<p align="center">
  <a href="https://altnautica.com"><img alt="Website" src="https://img.shields.io/badge/Website-altnautica.com-3A82FF?style=for-the-badge"></a>
  <a href="https://docs.altnautica.com"><img alt="Docs" src="https://img.shields.io/badge/Docs-docs.altnautica.com-171717?style=for-the-badge"></a>
  <a href="https://discord.gg/uxbvuD4d5q"><img alt="Discord" src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
  <a href="https://www.linkedin.com/company/altnautica"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Altnautica-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/altnautica/ADOSDroneAgent/tree/main/crates#published-crates"><img alt="crates.io" src="https://img.shields.io/badge/crates.io-17_crates-E6B14C?style=for-the-badge&logo=rust&logoColor=white"></a>
</p>

https://github.com/user-attachments/assets/09f265f4-b692-468a-a170-2be2d8525ae7

**ADOS** is an open-source platform for software-defined drones. The Drone Agent turns a companion computer into the drone's onboard brain for the radio link, video, vision, swarm and extensions, and you run it from Mission Control in the browser or on the desktop, from Android, or through AI clients over MCP. It works with ArduPilot, PX4, Betaflight and iNav.

Features such as World Engine (beta), visual-inertial and LiDAR SLAM poses and GPS-denied navigation grow with every release. ADOS is built as a base for smart agriculture, indoor operations and logistics in GPS-denied warehouses, with extensions, a Rust SDK and published crates for anyone who wants to build on it.

## Projects

<!-- ados-family:projects -->
<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/altnautica/ADOSMissionControl"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/mission-control-dark.webp"><img src="./assets/cards/mission-control-light.webp" alt="ADOS Mission Control" width="100%"></picture></a><h3><a href="https://github.com/altnautica/ADOSMissionControl">ADOS Mission Control</a></h3><p>Ground control station: FC setup, mission planning, flight, 3D simulation, fleet.</p><p><sub>Runs on: Browser, desktop (Electron)</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/ADOSMissionControl?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/ADOSMissionControl?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/ADOSMissionControl?style=flat-square"></p></td>
<td width="50%" valign="top"><a href="https://github.com/altnautica/ADOSDroneAgent"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/drone-agent-dark.webp"><img src="./assets/cards/drone-agent-light.webp" alt="ADOS Drone Agent" width="100%"></picture></a><h3><a href="https://github.com/altnautica/ADOSDroneAgent">ADOS Drone Agent</a></h3><p>Onboard agent: MAVLink routing, HD video, long-range radio link, plugins, remote control.</p><p><sub>Runs on: Companion computer on the drone, or a ground node</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/ADOSDroneAgent?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/ADOSDroneAgent?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/ADOSDroneAgent?style=flat-square"></p></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/altnautica/ADOSAndroidGCS"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/android-gcs-dark.webp"><img src="./assets/cards/android-gcs-light.webp" alt="ADOS Android GCS" width="100%"></picture></a><h3><a href="https://github.com/altnautica/ADOSAndroidGCS">ADOS Android GCS</a></h3><p>Native ground control app for agents on the LAN, direct flight controllers and the cloud.</p><p><sub>Runs on: Android phones and tablets</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/ADOSAndroidGCS?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/ADOSAndroidGCS?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/ADOSAndroidGCS?style=flat-square"></p></td>
<td width="50%" valign="top"><a href="https://github.com/altnautica/ADOSExtensions"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/extensions-dark.webp"><img src="./assets/cards/extensions-light.webp" alt="ADOS Extensions" width="100%"></picture></a><h3><a href="https://github.com/altnautica/ADOSExtensions">ADOS Extensions</a></h3><p>First-party signed plugins, each with an agent half and a GCS half.</p><p><sub>Runs on: Drone Agent and Mission Control</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/ADOSExtensions?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/ADOSExtensions?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/ADOSExtensions?style=flat-square"></p></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/altnautica/ADOS-MCP"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/mcp-dark.webp"><img src="./assets/cards/mcp-light.webp" alt="ADOS MCP" width="100%"></picture></a><h3><a href="https://github.com/altnautica/ADOS-MCP">ADOS MCP</a></h3><p>Model Context Protocol server that lets AI clients operate ADOS drones under scopes and a safety gate.</p><p><sub>Runs on: Your machine</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/ADOS-MCP?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/ADOS-MCP?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/ADOS-MCP?style=flat-square"></p></td>
<td width="50%" valign="top"><a href="https://github.com/altnautica/Documentation"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/cards/docs-dark.webp"><img src="./assets/cards/docs-light.webp" alt="Documentation" width="100%"></picture></a><h3><a href="https://github.com/altnautica/Documentation">Documentation</a></h3><p>Public docs for every ADOS product.</p><p><sub>Runs on: docs.altnautica.com</sub></p><p><img alt="Stars" src="https://img.shields.io/github/stars/altnautica/Documentation?style=flat-square"> <img alt="License" src="https://img.shields.io/github/license/altnautica/Documentation?style=flat-square"> <img alt="Top language" src="https://img.shields.io/github/languages/top/altnautica/Documentation?style=flat-square"></p></td>
</tr>
</table>
<!-- /ados-family:projects -->

## How ADOS fits together

```mermaid
flowchart LR
  subgraph air["On the drone"]
    FC["Flight controller<br/>ArduPilot · PX4 · Betaflight · iNav"]
    DA["ADOS Drone Agent"]
  end
  subgraph ground["On the ground"]
    GA["ADOS Ground Agent"]
    MC["ADOS Mission Control<br/>browser · desktop"]
    AG["ADOS Android GCS"]
    MCP["ADOS MCP<br/>AI clients"]
  end
  EXT["ADOS Extensions"]
  FC <-- MAVLink --> DA
  DA <-- "long-range radio link" --> GA
  MC <-- "LAN or cloud relay" --> DA
  MC <-- LAN --> GA
  AG <-- "LAN or cloud" --> DA
  MCP <-- "LAN or cloud" --> DA
  EXT -. "agent plugins" .-> DA
  EXT -. "GCS panels" .-> MC
```

ADOS Ground Agent is the Drone Agent running its ground-station profile.

## Rust crates

Reusable libraries from the ADOS Drone Agent, published on crates.io under MIT OR Apache-2.0 (one crate is MIT only). Versioning and licences: [crates index](https://github.com/altnautica/ADOSDroneAgent/tree/main/crates#published-crates).

<!-- ados-family:crates -->
**Platform (versioned with the ADOS Drone Agent)**

| Crate | What it does | Docs |
|---|---|---|
| [`ados-protocol`](https://crates.io/crates/ados-protocol) | Wire contracts of the ADOS Drone Agent: IPC framing, plugin RPC envelope, capability tokens and the vision frame bus. | [docs.rs](https://docs.rs/ados-protocol) |
| [`ados-sdk`](https://crates.io/crates/ados-sdk) | Write Rust plugins for the ADOS Drone Agent: IPC client, plugin context, driver traits and lifecycle runner. | [docs.rs](https://docs.rs/ados-sdk) |
| [`ados-vision`](https://crates.io/crates/ados-vision) | Single-object visual tracker: Kalman motion model, appearance re-identification and YOLOv8 head decoding. | [docs.rs](https://docs.rs/ados-vision) |
| [`ados-gpio`](https://crates.io/crates/ados-gpio) | Drive status buzzers and LEDs on Linux GPIO lines, with bounded software-PWM beep patterns. | [docs.rs](https://docs.rs/ados-gpio) |
| [`ados-hal-probe`](https://crates.io/crates/ados-hal-probe) | Find out what a board's hardware can really do by probing it, plus bundled board profiles. | [docs.rs](https://docs.rs/ados-hal-probe) |

**Standalone**

| Crate | What it does | Docs |
|---|---|---|
| [`ados-sensorhub`](https://crates.io/crates/ados-sensorhub) | Sensor hub wire protocol: COBS framing, CRC-16 and fixed-layout IMU, baro, mag and GNSS packets. no_std. | [docs.rs](https://docs.rs/ados-sensorhub) |
| [`ados-offload`](https://crates.io/crates/ados-offload) | Choose where perception runs (onboard, offloaded or hybrid) and hold the vehicle when results go stale. | [docs.rs](https://docs.rs/ados-offload) |
| [`ados-macpin`](https://crates.io/crates/ados-macpin) | Stable MAC addresses for Linux network adapters that randomize theirs every boot. | [docs.rs](https://docs.rs/ados-macpin) |
| [`ados-lora`](https://crates.io/crates/ados-lora) | LoRa transmit governor with cited regional band plans, duty cycle, dwell time and airtime accounting. | [docs.rs](https://docs.rs/ados-lora) |
| [`ados-crsf-codec`](https://crates.io/crates/ados-crsf-codec) | no_std CRSF / ExpressLRS codec for RC channels, telemetry and parameter frames. | [docs.rs](https://docs.rs/ados-crsf-codec) |
| [`ados-positioning`](https://crates.io/crates/ados-positioning) | Split mixed UBX, NMEA and RTCM3 GNSS streams, configure u-blox receivers and run an RTK base survey-in. | [docs.rs](https://docs.rs/ados-positioning) |
| [`ados-rtcm`](https://crates.io/crates/ados-rtcm) | RTCM3 framing, CRC-24Q and MAVLink GPS_RTCM_DATA fragmentation for RTK corrections. | [docs.rs](https://docs.rs/ados-rtcm) |
| [`ados-clock`](https://crates.io/crates/ados-clock) | Map remote clocks onto the host clock: least-squares and envelope fits, TIMESYNC and a chrony sink. | [docs.rs](https://docs.rs/ados-clock) |
| [`ados-swarm`](https://crates.io/crates/ados-swarm) | Swarm control laws: separation, flocking, formations, CBBA task allocation and a point-mass simulator. | [docs.rs](https://docs.rs/ados-swarm) |
| [`ados-mavlink-tunnel`](https://crates.io/crates/ados-mavlink-tunnel) | Send large messages over MAVLink TUNNEL frames with chunking and bounded reassembly. | [docs.rs](https://docs.rs/ados-mavlink-tunnel) |
| [`ados-display-driver`](https://crates.io/crates/ados-display-driver) | Small-display output on Linux: SSD1306/SH1106 OLED over I2C, pixel packers and a framebuffer writer. | [docs.rs](https://docs.rs/ados-display-driver) |
| [`ados-hmi`](https://crates.io/crates/ados-hmi) | Front-panel input: touchscreen calibration and gestures, button presses and rotary encoders. | [docs.rs](https://docs.rs/ados-hmi) |
<!-- /ados-family:crates -->

## Get involved

- **Fly it:** [install the Drone Agent](https://docs.altnautica.com/drone-agent/overview) on a companion computer and open [Mission Control](https://command.altnautica.com).
- **Build on it:** write an agent plugin with the [Rust SDK](https://docs.rs/ados-sdk) or follow the [extension guide](https://docs.altnautica.com/developers/overview).
- **Talk to us:** [Discord](https://discord.gg/uxbvuD4d5q), or open an issue on the repo you are using.
- **Contribute:** pull requests are welcome; each README has a Contributing section.

<sub>ADOS applications are licensed GPL-3.0-or-later; the Rust library crates are MIT OR Apache-2.0.</sub>
