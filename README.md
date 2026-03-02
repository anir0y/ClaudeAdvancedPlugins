# Claude Advanced Plugins

A comprehensive collection of **42 advanced plugins** (49 slash commands) for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) that supercharge your development, security, and productivity workflows.

Each plugin installs as a custom slash command in Claude Code, giving you instant access to specialized expertise.

## Quick Install

```bash
git clone https://github.com/CyberSecurityUP/ClaudeAdvancedPlugins.git
cd ClaudeAdvancedPlugins
chmod +x install.sh
./install.sh
```

That's it. All plugins are now available as `/command-name` in Claude Code.

## Plugin Categories

### Backend Development

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Backend Architect** | `/backend-architect`, `/backend-api-design`, `/backend-db-optimize` | System architecture, API design, database optimization, scalability patterns |

### Frontend Development

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Frontend Forge** | `/frontend-forge`, `/frontend-component` | Component architecture, accessibility, design systems, TypeScript |
| **Frontend Animations** | `/frontend-animations` | CSS/GSAP/Framer Motion animations, micro-interactions, scroll effects, spring physics |
| **Frontend DOM** | `/frontend-dom` | DOM manipulation, Web Components, Shadow DOM, browser APIs, View Transitions |
| **Frontend 3D** | `/frontend-3d` | Three.js, React Three Fiber, WebGL, GLSL shaders, 3D scenes |
| **Frontend Performance** | `/frontend-perf` | Core Web Vitals, bundle optimization, code splitting, rendering performance |
| **Frontend Micro** | `/frontend-micro` | Micro-frontends, Module Federation, state machines, monorepo architecture |

### Red Team & Offensive Security

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Red Team Ops** | `/red-team-ops`, `/red-team-payload` | Adversary simulation, attack chains, MITRE ATT&CK, C2 infrastructure |
| **Pentest Toolkit** | `/pentest-toolkit`, `/pentest-web` | PTES methodology, OWASP Top 10, vulnerability assessment |
| **Pentest Network** | `/pentest-network` | Infrastructure testing, service enumeration, network exploitation |
| **Pentest Mobile** | `/pentest-mobile` | Android/iOS app testing, Frida, OWASP MASTG/MASVS |
| **Pentest Cloud** | `/pentest-cloud` | AWS/Azure/GCP security testing, IAM exploitation, privilege escalation |
| **Pentest Wireless** | `/pentest-wireless` | Wi-Fi, Bluetooth, BLE, IoT radio, SDR security testing |
| **Pentest AD** | `/pentest-ad` | Active Directory attacks, Kerberos, ADCS, BloodHound, delegation abuse |
| **Pentest Social** | `/pentest-social` | Social engineering campaigns, phishing, vishing, OSINT, physical SE |
| **Pentest Report** | `/pentest-report` | Professional pentest report writing, CVSS scoring, executive summaries |
| **Exploit Dev** | `/exploit-dev`, `/exploit-ctf` | Binary exploitation, ROP chains, heap techniques, CTF solving |
| **API Security** | `/api-security` | OWASP API Top 10, GraphQL/gRPC/WebSocket testing |

### Blue Team & Defense

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Blue Team SOC** | `/blue-team-soc` | SOC operations, alert triage, Tier 1-3 analysis, incident investigation |
| **Blue Team DFIR** | `/blue-team-dfir` | Digital forensics, incident response, evidence handling, NIST SP 800-61 |
| **Blue Team Malware Analysis** | `/blue-team-malware-analysis` | Static/dynamic malware analysis, YARA rules, behavioral analysis |
| **Blue Team SIEM** | `/blue-team-siem` | Sigma rules, Splunk SPL, Elastic KQL/EQL, Sentinel KQL, detection engineering |
| **Blue Team Threat Intel** | `/blue-team-threat-intel` | CTI lifecycle, OSINT, actor profiling, STIX/TAXII, TLP classification |
| **Blue Team Hardening** | `/blue-team-hardening` | CIS Benchmarks, STIGs, Windows/Linux/container/cloud hardening |
| **Blue Team Network Defense** | `/blue-team-network-defense` | IDS/IPS, firewall management, network monitoring, Suricata/Zeek rules |
| **Blue Team EDR** | `/blue-team-edr` | EDR/XDR analysis, Sysmon configuration, endpoint threat hunting |

### Reverse Engineering

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Reverse Binary** | `/reverse-binary` | PE/ELF/Mach-O analysis, disassembly, decompilation, Ghidra/IDA |
| **Reverse Malware** | `/reverse-malware` | Malware RE, unpacking, C2 protocol analysis, config extraction |
| **Reverse Protocol** | `/reverse-protocol` | Network protocol RE, binary format analysis, Wireshark dissectors |
| **Reverse Firmware** | `/reverse-firmware` | Firmware extraction, embedded systems, UART/JTAG, emulation |
| **Reverse Obfuscation** | `/reverse-obfuscation` | Deobfuscation, anti-debug bypass, anti-VM bypass, unpacking |

### Security Architecture & Engineering

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Secure Code Review** | `/secure-code-review` | SAST-style code review, CWE mapping, vulnerability patterns |
| **Threat Modeler** | `/threat-modeler` | STRIDE, DREAD, PASTA, attack trees, risk matrices |
| **Crypto Analysis** | `/crypto-analysis` | Cryptographic auditing, RSA/ECC attacks, TLS analysis, key management |
| **Vuln Research** | `/vuln-research` | Vulnerability discovery, fuzzing, CodeQL, responsible disclosure |
| **Supply Chain Sec** | `/supply-chain-sec` | Dependency attacks, SBOM, SLSA framework, build pipeline security |
| **Cloud Security** | `/cloud-security` | Cloud security architecture, landing zones, IAM, multi-cloud design |
| **DevSecOps** | `/devsecops` | CI/CD security, SAST/DAST/SCA integration, security pipeline design |

### Productivity & AI

| Plugin | Commands | Description |
|--------|----------|-------------|
| **Memory Vault** | `/memory-vault` | Persistent cross-session knowledge management |
| **Context Manager** | `/context-manager` | Context window optimization, smart file loading |
| **Hallucination Guard** | `/hallucination-guard` | Accuracy verification, confidence signaling, source validation |

### Systems

| Plugin | Commands | Description |
|--------|----------|-------------|
| **OS Internals** | `/os-internals`, `/os-debug` | Linux/Windows/macOS kernel internals, system debugging |

## Usage Examples

```bash
# Backend
/backend-architect Design a microservices architecture for an e-commerce platform
/backend-db-optimize Analyze slow queries in this PostgreSQL schema

# Frontend
/frontend-animations Create a scroll-triggered parallax hero section with GSAP
/frontend-dom Build a virtual scrolling list with Intersection Observer
/frontend-3d Create an interactive 3D product viewer with React Three Fiber
/frontend-perf Audit this Next.js app for Core Web Vitals issues
/frontend-micro Design a micro-frontend architecture with Module Federation

# Red Team
/red-team-ops Plan a red team exercise targeting the corporate network
/red-team-payload Craft a staged payload for authorized Windows 11 testing
/pentest-ad Enumerate and attack this Active Directory environment
/pentest-cloud Assess AWS IAM for privilege escalation paths
/pentest-mobile Test this Android APK for OWASP MASVS compliance

# Blue Team
/blue-team-soc Triage this IDS alert for potential lateral movement
/blue-team-dfir Investigate a suspected ransomware incident
/blue-team-siem Write Sigma rules to detect Kerberoasting attacks
/blue-team-malware-analysis Analyze this suspicious DLL sample
/blue-team-edr Create Sysmon config for detecting process injection

# Reverse Engineering
/reverse-binary Analyze this stripped ELF binary from a CTF challenge
/reverse-malware Unpack and analyze this .NET RAT sample
/reverse-protocol Reverse engineer this custom TCP protocol from PCAP
/reverse-firmware Extract and analyze firmware from this IoT device
/reverse-obfuscation Deobfuscate this JavaScript with control flow flattening

# Security Architecture
/crypto-analysis Audit the TLS configuration and JWT implementation
/vuln-research Find vulnerabilities in this C parser using fuzzing
/supply-chain-sec Audit npm dependencies for supply chain risks
/devsecops Design a security pipeline for GitHub Actions

# Productivity
/hallucination-guard Verify this API documentation matches the actual code
/context-manager Optimize context for working on the authentication module
/memory-vault save patterns This project uses repository pattern with DI
```

## Selective Installation

```bash
# Install only blue team plugins
./install.sh -p blue-team-soc -p blue-team-dfir -p blue-team-siem -p blue-team-edr

# Install only frontend plugins
./install.sh -p frontend-forge -p frontend-animations -p frontend-dom -p frontend-3d -p frontend-perf

# Install only pentest plugins
./install.sh -p pentest-toolkit -p pentest-network -p pentest-ad -p pentest-cloud -p pentest-mobile

# Install only reverse engineering plugins
./install.sh -p reverse-binary -p reverse-malware -p reverse-protocol -p reverse-firmware

# List all available plugins and their commands
./install.sh --list

# Force reinstall (overwrite existing)
./install.sh --force
```

## Uninstall

```bash
./uninstall.sh
# or
./install.sh --uninstall
```

## Plugin Details

<details>
<summary><strong>Backend Development (3 commands)</strong></summary>

### Backend Architect
Expert system architecture and API design. Covers distributed systems, database optimization, caching strategies (Redis, CDN), resilience patterns (circuit breaker, bulkhead), message queues, and observability (OpenTelemetry, Prometheus). Produces architecture diagrams, API specs, data models, and implementation roadmaps.
</details>

<details>
<summary><strong>Frontend Development (7 commands)</strong></summary>

### Frontend Forge
Modern frontend engineering with component architecture, TypeScript, Core Web Vitals, accessibility (WCAG 2.1 AA), and design systems.

### Frontend Animations
Full animation toolkit covering CSS animations/transitions, Framer Motion (React), GSAP (ScrollTrigger, SplitText, DrawSVG), React Spring, Lottie, and CSS scroll-driven animations. Includes micro-interactions, page transitions, parallax, particle systems, and performance optimization with `prefers-reduced-motion` support.

### Frontend DOM
Deep DOM expertise including layout thrashing prevention, Virtual DOM internals, Shadow DOM and Web Components (with form association and CSS parts), Intersection/Mutation/Performance/Resize Observers, View Transitions API, Popover API, event delegation, AbortController cleanup, and DOM security (Trusted Types, CSP, DOMPurify).

### Frontend 3D
Three.js and React Three Fiber (R3F) for 3D web experiences. Custom GLSL shaders (vertex + fragment), post-processing (bloom, DOF, SSAO), physics (Rapier), model loading (GLTF/Draco/KTX2), lighting (PBR, IBL), animation, and interaction. Performance optimization with instancing, LOD, and GPU profiling.

### Frontend Performance
Core Web Vitals optimization (LCP, INP, CLS). Resource hints (preload, preconnect, prefetch), image optimization (AVIF/WebP, responsive images, fetchpriority), render-blocking elimination, code splitting, tree shaking, bundle analysis, Web Workers, `scheduler.yield()`, and caching strategies.

### Frontend Micro
Micro-frontend architecture with Webpack 5 Module Federation, Vite federation, Web Component wrappers, and iframe isolation. Cross-MFE communication (event bus, shared Zustand), XState state machines, Preact Signals, monorepo management (Turborepo, Nx), and contract testing.
</details>

<details>
<summary><strong>Red Team & Offensive Security (13 commands)</strong></summary>

### Red Team Ops
Adversary simulation with MITRE ATT&CK mapping. Initial access, post-exploitation, persistence, lateral movement, C2 infrastructure, and evasion. Always includes detection opportunities for purple teaming.

### Pentest Toolkit & Web
Full PTES methodology. Web app testing covers all OWASP Top 10 2021 categories plus GraphQL, WebSocket, and deserialization attacks.

### Pentest Network
Infrastructure testing with Nmap, service enumeration (SMB, LDAP, SNMP, DNS, RDP), vulnerability scanning, ARP spoofing, LLMNR poisoning, relay attacks, pivoting (chisel, ligolo-ng), and lateral movement.

### Pentest Mobile
Android and iOS security testing. APK decompilation (JADX), Frida instrumentation, SSL pinning bypass, root/jailbreak detection bypass, OWASP MASVS/MASTG compliance, data storage analysis, and third-party SDK risk assessment.

### Pentest Cloud
AWS/Azure/GCP security testing. IAM privilege escalation paths, S3/storage exposure, IMDS exploitation, service principal abuse, cross-account attacks, and multi-cloud tools (ScoutSuite, Prowler, Pacu).

### Pentest Wireless
Wi-Fi (WPA2/WPA3/Enterprise), Bluetooth (Classic + BLE), IoT radio (Zigbee, Z-Wave, LoRa), RFID/NFC, and SDR. Evil Twin, deauth, PMKID capture, and rogue AP attacks.

### Pentest AD
Complete Active Directory attack lifecycle. BloodHound, Kerberoasting, AS-REP Roasting, ADCS attacks (ESC1-ESC11), delegation abuse (unconstrained, constrained, RBCD), credential extraction (LSASS, DPAPI, LAPS), DCSync, Golden/Silver/Diamond tickets, and ACL-based escalation.

### Pentest Social
Social engineering assessments. Phishing campaign design, vishing scripts, physical security testing, OSINT profiling, USB drop attacks, and security awareness metrics.

### Pentest Report
Professional penetration test report writing with executive summaries, CVSS 3.1 scoring, CWE mapping, attack narratives, evidence documentation, and remediation roadmaps.

### Exploit Dev & CTF
Binary exploitation (buffer overflow, ROP, heap, format string, SROP), protection bypass (ASLR, canary, DEP, PIE, RELRO, CFI), web exploitation, and CTF challenge solving across all categories (PWN, RE, web, crypto, forensics, misc).

### API Security
OWASP API Security Top 10 (2023). BOLA, authentication bypass, mass assignment, rate limiting bypass, SSRF, GraphQL attacks (introspection, batching, depth), gRPC security, and WebSocket hijacking.
</details>

<details>
<summary><strong>Blue Team & Defense (8 commands)</strong></summary>

### Blue Team SOC
SOC Tier 1-3 operations. Alert triage framework (contextualize, enrich, correlate, determine, respond), false positive tuning, IOC extraction, threat hunting, and SOC metrics (MTTD, MTTR).

### Blue Team DFIR
Complete NIST SP 800-61 incident response. Disk forensics (MFT, USN, Prefetch, Shimcache, Amcache), memory forensics (Volatility 3), network forensics (PCAP analysis), cloud forensics, evidence handling, and chain of custody.

### Blue Team Malware Analysis
Static and dynamic malware analysis. Packer detection, string extraction (FLOSS), PE/ELF analysis, sandbox execution, API tracing, classification by family (ransomware, RAT, stealer, loader), YARA/Sigma/Snort rule generation, and MITRE ATT&CK mapping.

### Blue Team SIEM
Detection engineering in Sigma (universal), Splunk SPL, Elastic KQL/EQL, and Microsoft Sentinel KQL. Covers endpoint, network, identity, and cloud detection. Includes performance optimization, alert fatigue reduction, and Atomic Red Team testing.

### Blue Team Threat Intel
Cyber Threat Intelligence lifecycle. OSINT collection, IOC analysis, TTP mapping, threat actor profiling, campaign correlation, STIX 2.1/TAXII integration, TLP classification, and intelligence report writing (flash alerts, campaign reports, actor profiles).

### Blue Team Hardening
CIS Benchmarks and STIGs for Windows, Linux, containers, cloud, and network devices. Covers password policy, audit policy, ASR rules, Credential Guard, SSH hardening, SELinux/AppArmor, sysctl tuning, and compliance frameworks (PCI-DSS, HIPAA, SOC 2, ISO 27001).

### Blue Team Network Defense
IDS/IPS (Snort/Suricata rules), Zeek scripts, firewall management, network segmentation, DNS security (DNSSEC, RPZ, sinkholing), email security (SPF/DKIM/DMARC), proxy/web filtering, and Zero Trust architecture.

### Blue Team EDR
EDR/XDR endpoint analysis. Sysmon configuration (all event types), process tree analysis, LOLBin detection, DLL sideloading, registry persistence, beaconing detection, threat hunting queries, and response actions (isolation, quarantine, sweep).
</details>

<details>
<summary><strong>Reverse Engineering (5 commands)</strong></summary>

### Reverse Binary
PE/ELF/Mach-O analysis. Disassembly, decompilation (Ghidra, IDA, Binary Ninja), Go and Rust binary recovery, compiler identification, packer detection, FLIRT signatures, DBI frameworks (Frida, DynamoRIO), and emulation (Unicorn, angr).

### Reverse Malware
Deep malware RE. Unpacking (UPX, Themida, VMProtect, custom), string deobfuscation, C2 protocol reverse engineering, DGA analysis, config extraction, persistence mechanism analysis, evasion technique documentation, and detection signature development.

### Reverse Protocol
Network protocol and binary format reverse engineering. Message structure identification, encoding detection (protobuf, MessagePack, ASN.1), state machine recovery, Wireshark Lua dissector development, Python client implementation, and protocol fuzzing harness creation.

### Reverse Firmware
Embedded systems and IoT firmware analysis. Extraction (binwalk, SPI/JTAG), filesystem analysis (SquashFS, JFFS2, UBIFS), cross-architecture RE (ARM, MIPS, RISC-V), emulation (QEMU, Firmadyne), hardware debugging, and boot process analysis.

### Reverse Obfuscation
Deobfuscation across all platforms. JavaScript (AST manipulation, control flow unflattening), PowerShell (Base64, IEX unwrapping), .NET (de4dot, ConfuserEx), Java (ProGuard reversal), Python (PyInstaller extraction), binary (opaque predicates, VM handlers), anti-debug bypass (PEB patching, timing normalization), and anti-VM bypass.
</details>

<details>
<summary><strong>Security Architecture (7 commands)</strong></summary>

### Secure Code Review
Systematic SAST-style code review. Input validation, authentication, authorization (IDOR, RBAC), injection prevention, cryptography audit, error handling, data protection, dependency security, race conditions, and CWE mapping with CVSS scoring.

### Threat Modeler
STRIDE, DREAD, PASTA, and Attack Trees. Data flow diagrams, threat catalogs with MITRE ATT&CK mapping, risk matrices (likelihood vs impact), and mitigation roadmaps.

### Crypto Analysis
Cryptographic assessment. RSA attacks (Coppersmith, Wiener, Hastad, Bleichenbacher), ECC attacks (invalid curve, nonce reuse), hash attacks (length extension, collision), TLS analysis, key management audit, PRNG weakness detection, and migration planning.

### Vuln Research
Vulnerability discovery methodology. SAST (Semgrep, CodeQL), fuzzing (AFL++, libFuzzer, Honggfuzz), symbolic execution (angr, KLEE), differential testing, CWE classification, PoC development, and responsible disclosure (90-day timeline, CVE reservation).

### Supply Chain Sec
Software supply chain security. Typosquatting, dependency confusion, malicious updates, build pipeline attacks, source code attacks, SBOM generation (CycloneDX, SPDX), SLSA framework compliance, artifact signing (cosign, Sigstore), and lockfile enforcement.

### Cloud Security
Cloud security architecture for AWS/Azure/GCP. IAM design, VPC segmentation, encryption (KMS), logging (CloudTrail, Azure Monitor), CSPM, secure landing zones, multi-account strategy, IaC security, and compliance mapping.

### DevSecOps
CI/CD security pipeline. Pre-commit hooks (gitleaks), SAST (Semgrep, CodeQL), SCA (Snyk, Dependabot), container scanning (Trivy, Grype), IaC scanning (Checkov, tfsec), DAST (ZAP, Nuclei), SBOM generation, artifact signing, runtime protection (Falco), and GitHub Actions/GitLab CI configurations.
</details>

<details>
<summary><strong>Productivity & Systems (5 commands)</strong></summary>

### Memory Vault
Persistent knowledge management across Claude Code sessions. Captures architecture decisions, debugging insights, project conventions, and user preferences with semantic organization.

### Context Manager
Context window optimization. Smart file loading prioritization, context compression, checkpointing, recovery after compression, and anti-pattern detection.

### Hallucination Guard
Hallucination prevention. Source verification, confidence levels ([VERIFIED] to [UNCERTAIN]), API/path/version/behavioral hallucination detection, self-correction protocol, and verification workflow.

### OS Internals & Debug
Linux, Windows, and macOS kernel internals. Process scheduling (CFS, MLFQ), virtual memory (page tables, TLB, ASLR), file systems (ext4, NTFS, APFS), networking stack, kernel data structures, eBPF, Windows ETW, macOS XNU/Mach, and system-level debugging (GDB, perf, DTrace, Instruments).
</details>

## How It Works

Claude Code supports [custom slash commands](https://docs.anthropic.com/en/docs/claude-code) stored as Markdown files in `~/.claude/commands/`. Each plugin is a carefully crafted system prompt that activates specialized expertise when invoked.

The install script simply copies the command `.md` files to your Claude commands directory. No dependencies, no runtime, no configuration.

## Requirements

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) CLI installed
- Bash shell (macOS, Linux, WSL)

## Security Disclaimer

The security-focused plugins are designed for **authorized security testing only**:

- Authorized penetration testing engagements
- Red team exercises with proper scope and rules of engagement
- CTF competitions and wargames
- Security research and education
- Bug bounty programs with proper scope
- Purple team exercises

**Never use these tools against systems without explicit authorization.**

## Contributing

Contributions are welcome! To add a new plugin:

1. Create a directory under `plugins/your-plugin-name/commands/`
2. Add one or more `.md` files with the command prompts
3. Use `$ARGUMENTS` placeholder where user input should be inserted
4. Include clear instructions, methodology, and output format
5. Submit a pull request

## License

MIT License - see [LICENSE](LICENSE) for details.

---

**Built for the security community by [CyberSecurityUP](https://github.com/CyberSecurityUP)**
