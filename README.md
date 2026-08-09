# PROJECT VORTEX-ION: In-Situ Pyro-Catalytic Filter Loop (Model VXI-4000)

[![DOI](https://zenodo.org)](https://doi.org)

Automated industrial emissions recovery platform (Model VXI-4000) designed for capturing and recycling volatile metallic particulates in secondary metallurgy.

## 📦 Executive Design Summary
The VXI-4000 resolves common filtration failures (pipe warping, clogging) by utilizing specialized superalloys, active gas-phase chemical reduction, and cold downstream compaction. Controlled by a low-latency, bare-metal microcontroller.

## 📁 Repository Structure & File Mapping
*   `master_firmware.cpp`: Hardened C++20 safety core.
*   `production_core_control.cpp`: Real-time scheduler.
*   `CMakeLists.txt`: Build automation configuration.
*   `run_hil_tests.sh`: Automated test runner.
*   `test_hil_simulation.py`: Real-time signal simulation.
*   `procurement_bom_v260.txt`: Asset procurement ledger.
*   `APPENDIX_A_Isolation_Protocol.md`: Corrosion prevention protocols.

## 💻 Cyber-Physical Control & 2-Tier Safety Matrix
Controlled by an **STM32H747 MCU**, featuring a hardwired 2-Tier Safety Strategy:
*   **Tier 1 (Pin PG7):** Non-destructive pneumatic bypass for maintenance events.
*   **Tier 2 (Pin PG8):** Catastrophic explosion isolation via high-speed, 4.0ms, resettable valve.

## 🧮 Standalone Financial Yield Ledger
*   **CapEx:** $215,000.00
*   **Daily Yield:** $1,703.25 / day (450.0 kg/day @ $3.785/kg)
*   **ROI:** $506,535.00 / year
*   **Break-Even:** ~5.1 Months
