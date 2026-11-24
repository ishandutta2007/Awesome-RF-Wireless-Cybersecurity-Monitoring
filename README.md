# Awesome-RF-Wireless-Cybersecurity-Monitoring

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Tracked Repos](https://img.shields.io/badge/Open_Source_Tools-25+-blue.svg)](https://github.com/ishandutta2007/Awesome-RF-Wireless-Cybersecurity-Monitoring)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-RF-Wireless-Cybersecurity-Monitoring/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated directory of top **RF (Radio Frequency) & Wireless Cybersecurity Monitoring** platforms, SaaS tools, and open-source software. Track Wireless Intrusion Detection Systems (WIDS/WIPS), SDR spectrum monitoring, cellular IMSI-catcher defense, Wi-Fi 6/6E/7 analysis, and Bluetooth Low Energy (BLE) auditing.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Commercial Platforms](#saas--commercial-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Key Features Comparison & Use Cases](#key-features-comparison--use-cases)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & Responsible Use](#disclaimer--responsible-use)

---

## Sector Overview & Market Dynamics

The global wireless network security and RF monitoring market is valued at approximately **$8.16 billion to $9.5 billion in 2025/2026** and is projected to surpass **$47 billion to $57 billion by 2030–2031**, expanding at a compound annual growth rate (CAGR) of **12.5% to 14.8%**, fueled by rapid enterprise Wi-Fi 6E/7 adoption, private 5G deployments, and explosive IoT endpoint density.

The sector exhibits **moderate fragmentation with high specialization**: broad enterprise vulnerability and network infrastructure monitoring is concentrated among multi-billion-dollar cybersecurity and IT observability giants (Qualys, Tenable, Rapid7, Paessler), while dedicated RF physical-layer spectrum analysis, specialized Wi-Fi surveying, and tactical wireless penetration testing remain dominated by specialized category leaders (Ekahau, Hak5, NetSpot, Tarlogic/Acrylic Wi-Fi) alongside a thriving, highly active open-source ecosystem.

---

## SaaS & Commercial Platforms

The following table provides commercial and SaaS platforms for RF and wireless security monitoring, sorted descending by company size (market valuation or annual revenue):

| Platform / Vendor | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Free Trial Limits | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Qualys Network Scanner (VMDR)](https://qualys.com)** | **$5.1B+ Market Cap** ($608M+ Rev) | **$150 – $200 / asset / year** (~$596/mo on AWS Marketplace up to 128 hosts) | **30-day full-featured free trial**; unlimited cloud-agent and network vulnerability assessments for up to 16 internal/external assets | Cloud-native asset discovery, wireless network vulnerability management, rogue AP detection, and compliance auditing |
| **[Tenable Nessus](https://tenable.com)** | **$3.5B+ Market Cap** ($900M+ Rev) | **$4,790 / year** (Nessus Professional 1-year license) | **Nessus Essentials: Free forever**, limited to **5 IP addresses** per scan target with community plugin feeds; or 7-day unlimited trial | Industry-benchmark vulnerability scanner identifying rogue wireless devices, misconfigured APs, and network bridge risks |
| **[Rapid7 InsightVM](https://rapid7.com)** | **$1.8B+ Market Cap** ($844M+ Rev) | **$1.62 / asset / month** (~$9,720/year billed annually, 500 asset min.) | **30-day free trial** with full live dashboard features for up to **100 tracked network assets** | Continuous endpoint scanning, wireless segment risk prioritization, and automated wireless controller asset assessment |
| **[Ekahau Cloud](https://ekahau.com)** | **$1.2B Acquisition** ($231M Connectivity Div. Rev) | **$1,495 / year** (Ekahau Plan/Measure Pro; AI Pro standalone software ~$5,995 perpetual) | **14-day guided proof-of-concept / evaluation trial** with demo site survey floor plans and restricted export capabilities | Industry gold-standard enterprise Wi-Fi 6/6E/7 site surveying, 3D RF spectrum interference heatmaps, and Sidekick 2 spectrum telemetry |
| **[PRTG Network Monitor](https://paessler.com)** | **$105M+ Funding / PE backed** (~$65M Rev) | **$200 / month** (~$2,149/year for PRTG 500 tier up to 500 sensors) | **Free forever plan: Up to 100 sensors free for life**; plus 30-day unrestricted trial of commercial unlimited sensor tier | Centralized network observability with specialized SNMP, QoS, signal-to-noise ratio, and Wi-Fi traffic load sensors |
| **[Hak5 Cloud C2](https://hak5.org)** | **Privately held / Bootstrapped** (~$15M–$25M Est. Rev) | **$200 one-time** (Professional Edition perpetual license, 1 user / 50 devices) | **Community Edition: Free forever**, perpetual license capped at **10 concurrent devices**, 1 user, and 1 site | Fleet management and remote orchestration C2 for WiFi Pineapple, Packet Squirrel, LAN Turtle, and field auditing probes |
| **[NetSpot](https://netspotapp.com)** | **Privately held** (~$3M–$6M Est. Rev) | **$149 one-time** (NetSpot Pro single-user lifetime commercial license) | **Free Home Edition: Free forever**, non-commercial use only, Inspector/Discover mode active, Survey mode capped at 1 zone / demo data | Interactive Wi-Fi site surveys, physical RF heatmaps, channel conflict diagnostics, and dead-zone mapping for Windows and macOS |
| **[Acrylic Wi-Fi](https://acrylicwifi.com)** | **Privately held** (Tarlogic Security subsidiary, ~$2M–$5M Est. Rev) | **$44.95 / year** ($99.95 lifetime perpetual for Acrylic Wi-Fi Professional) | **Free Home Edition: Free forever**, non-commercial use, basic 802.11a/b/g/n/ac/ax scanning; plus 15-day Professional evaluation trial | Windows 802.11 monitor-mode packet capture, Rogue AP and Evil Twin detection, Wi-Fi channel spectrum heatmaps, and signal strength auditing |
| **[WiGLE](https://wigle.net)** | **Community / Non-Profit Crowdsourced** (<$1M Community funded) | **Custom commercial data feed** (Admin negotiated) / Free for standard research queries | **Free community tier: Free forever**, queries rate-limited to standard daily web/API search thresholds for non-commercial research | Crowdsourced global wireless database mapping billions of 802.11 Wi-Fi BSSIDs, Bluetooth beacons, and cellular cell towers worldwide |

---

## Open-Source GitHub Projects

Curated list of active, top-tier open-source projects for Software-Defined Radio (SDR) analysis, Wireless Intrusion Detection Systems (WIDS), Bluetooth/Wi-Fi auditing, and anti-surveillance defense. 

Sorted in **descending order by GitHub stargazers count**:

| Repository | Stars | Category / Purpose | Key Highlights |
| :--- | :---: | :--- | :--- |
| **[bettercap/bettercap](https://github.com/bettercap/bettercap)** | [![Stars](https://img.shields.io/github/stars/bettercap/bettercap?style=social&color=white)](https://github.com/bettercap/bettercap/stargazers) | Wi-Fi / BLE / HID / Network Auditing | Complete Go-based Swiss Army knife framework for 802.11 beacon manipulation, BLE sniffing/spoofing, and 2.4 GHz wireless mousejacking reconnaissance. |
| **[justcallmekoko/ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder)** | [![Stars](https://img.shields.io/github/stars/justcallmekoko/ESP32Marauder?style=social&color=white)](https://github.com/justcallmekoko/ESP32Marauder/stargazers) | Portable Hardware / ESP32 Firmware | Portable offensive and defensive firmware for ESP32 and Flipper Zero devices; captures PMKID/EAPOL frames, detects probes, and maps wireless presence. |
| **[jopohl/urh](https://github.com/jopohl/urh)** | [![Stars](https://img.shields.io/github/stars/jopohl/urh?style=social&color=white)](https://github.com/jopohl/urh/stargazers) | SDR Protocol Reverse-Engineering | Universal Radio Hacker: Investigates unknown RF protocols; demodulates raw IQ captures, parses symbol timings, and generates automated protocol models. |
| **[wireshark/wireshark](https://github.com/wireshark/wireshark)** | [![Stars](https://img.shields.io/github/stars/wireshark/wireshark?style=social&color=white)](https://github.com/wireshark/wireshark/stargazers) | Protocol Packet Inspection & Dissection | World-standard packet analyzer featuring deep dissectors for 802.11 radiotap headers, Bluetooth HCI/L2CAP, Zigbee, LoRaWAN, and LTE/5G wireless frames. |
| **[derv82/wifite2](https://github.com/derv82/wifite2)** | [![Stars](https://img.shields.io/github/stars/derv82/wifite2?style=social&color=white)](https://github.com/derv82/wifite2/stargazers) | Automated Wireless Auditing | Python-based automated wireless security audit tool orchestrating `aircrack-ng`, `reaver`, and `hcxdumptool` for handshake and PMKID collection. |
| **[v1s1t0r1sh3r3/airgeddon](https://github.com/v1s1t0r1sh3r3/airgeddon)** | [![Stars](https://img.shields.io/github/stars/v1s1t0r1sh3r3/airgeddon?style=social&color=white)](https://github.com/v1s1t0r1sh3r3/airgeddon/stargazers) | Multi-Use Wireless Auditing Suite | Comprehensive Bash-driven multi-tool for Linux providing automated evil-twin AP tracking, captive portal auditing, WPS PIN analysis, and monitor mode setup. |
| **[aircrack-ng/aircrack-ng](https://github.com/aircrack-ng/aircrack-ng)** | [![Stars](https://img.shields.io/github/stars/aircrack-ng/aircrack-ng?style=social&color=white)](https://github.com/aircrack-ng/aircrack-ng/stargazers) | 802.11 Wi-Fi Security Suite | Foundational Wi-Fi assessment suite including `airmon-ng`, `airodump-ng`, and `airplay-ng` for packet sniffing, deauth logging, and WPA2/WPA3 auditing. |
| **[merbanan/rtl_433](https://github.com/merbanan/rtl_433)** | [![Stars](https://img.shields.io/github/stars/merbanan/rtl_433?style=social&color=white)](https://github.com/merbanan/rtl_433/stargazers) | ISM-Band IoT RF Demodulator | Decodes over 200+ proprietary ISM band protocols (433.92 MHz, 868 MHz, 915 MHz) from wireless TPMS, weather stations, security alarms, and smart meters. |
| **[AlexandreRouma/SDRPlusPlus](https://github.com/AlexandreRouma/SDRPlusPlus)** | [![Stars](https://img.shields.io/github/stars/AlexandreRouma/SDRPlusPlus?style=social&color=white)](https://github.com/AlexandreRouma/SDRPlusPlus/stargazers) | Cross-Platform SDR Receiver & DSP | High-performance, cross-platform SDR GUI application supporting RTL-SDR, HackRF, Airspy, LimeSDR, and BladeRF with low-latency waterfall displays. |
| **[gnuradio/gnuradio](https://github.com/gnuradio/gnuradio)** | [![Stars](https://img.shields.io/github/stars/gnuradio/gnuradio?style=social&color=white)](https://github.com/gnuradio/gnuradio/stargazers) | Software Radio Framework & DSP SDK | Free & open-source signal processing platform widely used in academic, commercial, and defensive RF cybersecurity research and customized SDR pipeline construction. |
| **[EFForg/rayhunter](https://github.com/EFForg/rayhunter)** | [![Stars](https://img.shields.io/github/stars/EFForg/rayhunter?style=social&color=white)](https://github.com/EFForg/rayhunter/stargazers) | IMSI-Catcher / StingRay Detection | Rust tool built by the Electronic Frontier Foundation (EFF) running on Orbic mobile hotspots to detect rogue cell towers and cell-site simulators. |
| **[CellularPrivacy/Android-IMSI-Catcher-Detector](https://github.com/CellularPrivacy/Android-IMSI-Catcher-Detector)** | [![Stars](https://img.shields.io/github/stars/CellularPrivacy/Android-IMSI-Catcher-Detector?style=social&color=white)](https://github.com/CellularPrivacy/Android-IMSI-Catcher-Detector/stargazers) | Cellular Surveillance Detection | AIMSICD: Android-based security application defending against fake base stations (IMSI catchers), silent SMS interception, and cipher-downgrade attacks. |
| **[greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner)** | [![Stars](https://img.shields.io/github/stars/greenbone/openvas-scanner?style=social&color=white)](https://github.com/greenbone/openvas-scanner/stargazers) | Vulnerability Scanner & Assessment | Community edition vulnerability scanning daemon used in Greenbone Community Edition to scan wireless network controllers and connected infrastructure. |
| **[gqrx-sdr/gqrx](https://github.com/gqrx-sdr/gqrx)** | [![Stars](https://img.shields.io/github/stars/gqrx-sdr/gqrx?style=social&color=white)](https://github.com/gqrx-sdr/gqrx/stargazers) | SDR Spectrum Receiver GUI | Open-source SDR receiver powered by GNU Radio and Qt for real-time spectrum scanning, audio demodulation, and RF signal monitoring. |
| **[miek/inspectrum](https://github.com/miek/inspectrum)** | [![Stars](https://img.shields.io/github/stars/miek/inspectrum?style=social&color=white)](https://github.com/miek/inspectrum/stargazers) | IQ Sample & Spectrogram Visualizer | Fast offline radio signal analyzer designed for visually inspecting captured IQ samples, measuring symbol timing, and isolating transmitted RF bursts. |
| **[kismetwireless/kismet](https://github.com/kismetwireless/kismet)** | [![Stars](https://img.shields.io/github/stars/kismetwireless/kismet?style=social&color=white)](https://github.com/kismetwireless/kismet/stargazers) | Wireless Intrusion Detection (WIDS) | Industry standard passive wireless sniffer, WIDS, and wardriving platform supporting 802.11 Wi-Fi, Bluetooth LE, RTL-SDR, Zigbee, ADSB, and mousejack hardware. |
| **[ZerBea/hcxdumptool](https://github.com/ZerBea/hcxdumptool)** | [![Stars](https://img.shields.io/github/stars/ZerBea/hcxdumptool?style=social&color=white)](https://github.com/ZerBea/hcxdumptool/stargazers) | Low-Level WLAN Frame Capture | High-performance C utility for capturing raw 802.11 frames, detecting PMKIDs from access points without associated clients, and generating hashcat-ready captures. |
| **[greatscottgadgets/ubertooth](https://github.com/greatscottgadgets/ubertooth)** | [![Stars](https://img.shields.io/github/stars/greatscottgadgets/ubertooth?style=social&color=white)](https://github.com/greatscottgadgets/ubertooth/stargazers) | 2.4 GHz Bluetooth Spectrum Auditing | Open-source 2.4 GHz wireless development and monitoring hardware/software platform tailored for Bluetooth Basic Rate and Low Energy sniffing. |
| **[ghostop14/sparrow-wifi](https://github.com/ghostop14/sparrow-wifi)** | [![Stars](https://img.shields.io/github/stars/ghostop14/sparrow-wifi?style=social&color=white)](https://github.com/ghostop14/sparrow-wifi/stargazers) | Graphical Wi-Fi & SDR Tactical Scanner | Advanced Linux Wi-Fi and Bluetooth GUI analyzer integrating HackRF SDR sweeps, GPS mapping, and drone-based wireless surveillance telemetry. |
| **[nzymeorg/nzyme](https://github.com/nzymeorg/nzyme)** | [![Stars](https://img.shields.io/github/stars/nzymeorg/nzyme?style=social&color=white)](https://github.com/nzymeorg/nzyme/stargazers) | Enterprise Wireless WIDS & Anomaly Defense | Modern, dedicated WIDS platform collecting 802.11 management frames via passive sensors to alert on Evil Twins, deauthentication floods, and rogue APs. |
| **[uoaerg/wavemon](https://github.com/uoaerg/wavemon)** | [![Stars](https://img.shields.io/github/stars/uoaerg/wavemon?style=social&color=white)](https://github.com/uoaerg/wavemon/stargazers) | Terminal Wi-Fi Signal Monitor | Lightweight, ncurses-based real-time Linux CLI utility for monitoring wireless signal levels, link quality, noise thresholds, and station statistics. |
| **[bastibl/gr-ieee802-11](https://github.com/bastibl/gr-ieee802-11)** | [![Stars](https://img.shields.io/github/stars/bastibl/gr-ieee802-11?style=social&color=white)](https://github.com/bastibl/gr-ieee802-11/stargazers) | IEEE 802.11 a/g/p SDR Transceiver | GNU Radio OOT module providing an IEEE 802.11a/g/p wireless transceiver for decoding Wi-Fi frames directly over raw IQ samples. |
| **[br101/horst](https://github.com/br101/horst)** | [![Stars](https://img.shields.io/github/stars/br101/horst?style=social&color=white)](https://github.com/br101/horst/stargazers) | Terminal 802.11 WLAN Analyzer | "Highly Optimized Radio Scanning Tool": Lightweight ncurses Wi-Fi analyzer with integrated ASCII spectrum visualizer, ideal for embedded AP diagnostics. |
| **[CIS-C0/RFSentinel](https://github.com/CIS-C0/RFSentinel)** | [![Stars](https://img.shields.io/github/stars/CIS-C0/RFSentinel?style=social&color=white)](https://github.com/CIS-C0/RFSentinel/stargazers) | Mobile RF Surveillance & Tracker Detector | Android-based passive RF surveillance detector monitoring BLE beacons, Wi-Fi probe frames, and cell towers to detect Apple AirTags, surveillance drones, and IMSI catchers. |
| **[bastibl/gr-rds](https://github.com/bastibl/gr-rds)** | [![Stars](https://img.shields.io/github/stars/bastibl/gr-rds?style=social&color=white)](https://github.com/bastibl/gr-rds/stargazers) | FM Radio Data System (RDS) Receiver | GNU Radio out-of-tree block implementation for decoding and analyzing FM Radio Data System subcarrier telemetry. |

---

## Key Features Comparison & Use Cases

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                        RF & Wireless Cybersecurity Tech Stack                          │
└────────────────────────────────────────────────────────────────────────────────────────┘
            │                                               │
            ▼                                               ▼
┌──────────────────────────────────────┐        ┌──────────────────────────────────────┐
│  Hardware Sensors & Receivers        │        │  Analysis & Intrusion Detection      │
├──────────────────────────────────────┤        ├──────────────────────────────────────┤
│ • RTL-SDR / HackRF / USRP (SDR)      │        │ • WIDS / Rogue AP: Kismet, nzyme     │
│ • ESP32 Marauder / Flipper Zero      │   ──►  │ • IMSI Catchers: Rayhunter, AIMSICD  │
│ • Wi-Fi 6/7 Monitor Mode Cards       │        │ • RF Signal DSP: URH, GNU Radio      │
│ • Ekahau Sidekick 2 / Ubertooth One  │        │ • Vuln Scanners: Qualys, Nessus      │
└──────────────────────────────────────┘        └──────────────────────────────────────┘
```

- **Enterprise Wireless Intrusion Detection (WIDS/WIPS):** Deploy **nzyme** or **Kismet** on dedicated sensor nodes (Raspberry Pi or mini-PCs with monitor-mode Wi-Fi adapters) and ingest structured alerts into OpenSearch/Splunk.
- **Spectrum & Unknown RF Protocol Auditing:** Capture raw IQ files using **GQRX** or **SDR++**, and reverse-engineer proprietary physical/MAC layers with **Universal Radio Hacker (URH)** and **Inspectrum**.
- **Tactical Anti-Surveillance & Counter-IMSI Catchers:** Run **EFF Rayhunter** on portable hotspots and **CIS-C0/RFSentinel** or **AIMSICD** on mobile devices to detect unencrypted cellular downgrades, rogue base stations, and stalking trackers.
- **Site Surveying & Physical Security:** Utilize **Ekahau AI Pro** (or **NetSpot** / **Acrylic Wi-Fi**) to audit signal propagation, minimize RF leakage beyond corporate perimeters, and isolate rogue access points.

---

## How to Contribute

Contributions to keep this directory up-to-date are welcome!

1. **Fork the repository** on GitHub.
2. **Add or modify** entries in `README.md`. Ensure that:
   - SaaS entries include accurate starting tier prices, specific free tier/trial limits, and company size/valuation benchmarks.
   - Open-source projects include official repository links, star count badge syntax, and concise technical descriptions.
3. **Keep alphabetical or sort order** consistent (SaaS by company size, Open-Source by GitHub stars).
4. **Submit a pull request** with a brief summary of changes.

---

## Disclaimer & Responsible Use

- This list is curated strictly for **educational, security research, defensive monitoring, and lawful network auditing** purposes.
- Radio frequency transmission, wireless deauthentication testing, and cellular signal monitoring may be subject to strict legal and regulatory constraints (e.g., FCC, ETSI, ITU, WPC). Always ensure you have explicit written authorization before conducting audits on wireless infrastructure.

---

<div align="center">
  <sub>Maintained with ❤️ for the RF engineering, wireless security, and cybersecurity defense communities.</sub>
</div>
