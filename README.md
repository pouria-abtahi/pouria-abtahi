## Hi, I'm Pouria 👋

Computer Engineering Technology graduate (Seneca Polytechnic, Toronto). I work where hardware meets software: microcontroller firmware, PCB design, sensors and IoT. I build with AI coding agents (Claude Code and Codex) every day.

[LinkedIn](https://www.linkedin.com/in/pouria-abtahi) · Toronto, ON

---

### 🔧 Embedded & hardware projects

| Project | What it shows |
|---|---|
| [**freertos-emergency-shutdown-k64f**](https://github.com/pouria-abtahi/freertos-emergency-shutdown-k64f) | FreeRTOS firmware on an NXP Cortex-M4F: tasks, semaphores, software timers, GPIO/PIT interrupts with FreeRTOS-safe priorities. CMake + GitHub Actions build, `CLAUDE.md` for agent work. |
| [**advanced-iot-weather-station**](https://github.com/pouria-abtahi/advanced-iot-weather-station) | Raspberry Pi IoT station: DHT11, rain and wind sensors over SPI ADC, 16×2 LCD, GSM/SMS alerts, Blynk cloud dashboard, Proteus PCB. |
| [**labjack-servo-capacitor-control**](https://github.com/pouria-abtahi/labjack-servo-capacitor-control) | C + LabJack U3-HV DAQ: analog sensing, 50 Hz servo PWM, threshold logic, plus a custom PCB (PADS schematic, layout, Gerbers). |
| [**variable-dc-power-supply-lm317**](https://github.com/pouria-abtahi/variable-dc-power-supply-lm317) | Mains-powered 2–14 V bench supply: LM317 design, single-sided PCB, BOM, enclosure build, Hi-Pot and insulation-resistance safety tests. |

**Embedded toolbox:** C · FreeRTOS · ARM Cortex-M (NXP Kinetis) · Raspberry Pi · UART / SPI / I²C · GPIO, timers, PWM, interrupts · MCUXpresso · PADS · Proteus · multimeter, oscilloscope, soldering

### 🤖 How I work: AI-assisted development

Claude Code is my main development tool, with Codex alongside it. I don't just prompt; I set up the environment the agent works in:

- **Project instructions:** a `CLAUDE.md` per repo with build commands, hard rules (for example, never hand-edit generated code) and how to verify a change.
- **Custom skills:** I've written my own library of Claude Code skills for code review, safe git/release, production debugging, visual QA and project context.
- **Plugins and MCP:** I use MCP servers and plugins (GitHub, Playwright for browser testing, Context7 for live docs, and others) as part of my daily workflow.
- **Verify, don't trust:** the agent's output has to build, pass CI and get checked in a real browser or on real hardware before I call it done.

### 💼 Current work

I'm currently working on several client projects (private repositories), all built with an AI-first workflow using Claude Code and Codex.

### 🧩 Other projects

- [airline-reservation-system](https://github.com/pouria-abtahi/airline-reservation-system): C# WinForms + SQLite
- [client-server-shopping-system](https://github.com/pouria-abtahi/client-server-shopping-system): C# TCP client/server with a custom protocol
- [basketvr-toss-vr-game](https://github.com/pouria-abtahi/basketvr-toss-vr-game): Unity VR physics game
