# Dev Resource Index

A curated list of resources across Computer Science, Web Development, Security, and more.
Maintained as a living document — updated as new links are added.

---

## Table of Contents

**Computer Science & Development**
- [Systems Programming & OS Internals](#systems-programming--os-internals)
- [Sysadmin & Networking](#sysadmin--networking)
- [Linux & Command Line](#linux--command-line)
- [Algorithms & Data Structures](#algorithms--data-structures)
- [Web & Software Development](#web--software-development)
- [Real-Time & Media](#real-time--media)
- [3D & Graphics](#3d--graphics)
- [AI & Machine Learning](#ai--machine-learning)
- [Security](#security)
- [OSINT](#osint)
- [UI & Design](#ui--design)
- [Open Source & Dev Practice](#open-source--dev-practice)
- [Awesome Lists](#awesome-lists)
- [Community & Threads](#community--threads)
- [Education](#education)

**Other Fields**
- [Hardware & Tinkering](#hardware--tinkering)
- [Streaming & Broadcasting](#streaming--broadcasting)
- [Psychology of Games](#psychology-of-games)
- [Reading & Culture](#reading--culture)

---
---

# Computer Science & Development

## Systems Programming & OS Internals

- [Beej's Guides](https://beej.us/guide/) — Practical, well-written guides covering network programming, C, and more. A classic.
- [Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/) — Step-by-step tutorial by Stephen Brennan on building a Unix shell from scratch in C.
- [Unicorn Engine](https://github.com/unicorn-engine/unicorn) — Lightweight, multi-architecture CPU emulator framework.
- [Operating Systems: Three Easy Parts](https://pages.cs.wisc.edu/~remzi/OSTEP/) - The book is centered around three conceptual pieces that are fundamental to operating systems: virtualization, concurrency, and persistence.
- [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) — MIT course covering the tools and workflows CS programs don't teach: shell, git, editors, and more.
- [LearnCpp.com](https://www.learncpp.com/) — Free, comprehensive C++ tutorial series from basics to advanced topics.
- [What Are Deadlocks? How to Prevent Them](https://www.mathworks.com/products/polyspace/static-analysis-notes/what-deadlocks-how-prevent-during-software-development.html) — MathWorks explainer on deadlocks and prevention strategies in concurrent software. `[article to read]`

---

## Sysadmin & Networking

- [pfSense](https://www.pfsense.org/) — Open source firewall/router platform for network administration.
- [Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) — Open source VMM for running modern cloud workloads on KVM.
- [1xBTS](https://github.com/chrismoos/1xbts) — Open source CDMA2000 cellular network implementation.
- [Sysinternals](https://learn.microsoft.com/en-us/sysinternals/) - Technical resources and utilities to manage, diagnose, troubleshoot, and monitor a Microsoft Windows environment.
- [OverTheWire Wargames](https://overthewire.org/wargames/) — Browser-accessible security wargames for learning Linux and exploitation fundamentals hands-on.

### Network Monitoring & Privacy Tools

- [Safing](https://safing.io/) — Open source network monitoring and privacy tool (Portmaster) for controlling app-level network access.
- [NetBalancer](https://netbalancer.com/) — Windows tool for monitoring and controlling network traffic per-application.
- [NetLimiter](https://www.netlimiter.com/) — Bandwidth monitoring and control tool for Windows.
- [GlassWire](https://www.glasswire.com/) — Network monitoring tool with built-in firewall and traffic visualization.

### Architecture & Infrastructure

- [The Map of System Topologies](https://itnext.io/the-map-of-system-topologies-e2d3d0b89618) — Visual breakdown of system design patterns and topologies.
- [Deployment Strategies: Types, Trade-offs, and How to Choose](https://circleci.com/blog/deployment-strategies-types-trade-offs-and-how-to-choose/) — CircleCI breakdown of blue/green, canary, rolling, and other deployment models.
- [System Design Primer](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems.
- [System Design Pattern](https://github.com/Sairyss/system-design-patterns) - Resources related to distributed systems, system design, etc.
- [The History of Cloud Computing, Explained](https://www.techtarget.com/whatis/feature/The-history-of-cloud-computing-explained) — TechTarget overview of how cloud computing evolved.

---

## Linux & Command Line

- [Linuxize](https://linuxize.com/) — Practical Linux tutorials and command references.
- [GNU Bash Manual](https://www.gnu.org/software/bash/manual/html_node/index.html) — Official reference for the Bash shell.
- [Bash Guide](https://tldp.org/LDP/Bash-Beginners-Guide/html/) - This is a practical guide which, while not always being too serious, tries to give real-life instead of theoretical examples.
- [Linux Foundation Training](https://training.linuxfoundation.org/) — Official training and certification programs from the Linux Foundation.
- [Bash Cheat Sheet](https://github.com/RehanSaeed/Bash-Cheat-Sheet) — Comprehensive quick-reference for Bash scripting and command line usage.
- [systemd vs SysVinit vs OpenRC](https://cubepath.com/docs/comparison-guide/systemd-vs-sysvinit-vs-openrc) — Comparison guide covering Linux init system options and their trade-offs. `[article to read]`

---

## Algorithms & Data Structures

- [VisuAlgo](https://visualgo.net/en) — Interactive visualizations for sorting, graphs, trees, and other algorithms.
- [Javascript Algorithms](https://github.com/trekhleb/javascript-algorithms) - Algorithms and data structures implemented in JavaScript with explanations.

---

## Web & Software Development

### Dev-Experience Tools
*Tooling that shapes how you build — editors, versioning, process management, observability.*

- [Zed](https://zed.dev/) — High-performance, multiplayer code editor built in Rust.
- [Kakoune](https://github.com/mawww/kakoune) — Modal text editor with a focus on interactive, selection-first editing. An alternative take on vi-style editing.
- [fnm](https://github.com/Schniz/fnm) — Fast Node.js version manager built in Rust.
- [npq](https://github.com/lirantal/npq) — Safely install npm packages by auditing them before install.
- [Socket Optimize](https://socket.dev/blog/introducing-socket-optimize) — Supply-chain security tool that flags and swaps out risky or malicious npm packages.
- [PM2](https://github.com/Unitech/pm2) — Production process manager for Node.js with built-in load balancing and monitoring.
- [React Scan](https://github.com/aidenybai/react-scan) - Scan and fix React performance issues.
- [ELK Stack](https://www.elastic.co/elastic-stack/) - Elasticsearch and Kibana pave the way for diverse use cases that start with logging and span as far as your imagination takes you.
- [Backstage.io](https://backstage.io/) - An open source framework for building developer portals.

### End-Product Frameworks & Libraries
*What ships inside the app itself.*

- [Relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
- [Fate](https://github.com/nkzw-tech/fate) - Fate is a modern data client for React.
- [React Bits](https://reactbits.dev/) — Collection of React patterns, techniques, and tips.
- [Motion](https://motion.dev/) — Animation library for the web (formerly Framer Motion's standalone release).
- [Anime.js](https://github.com/juliangarnier/anime) — Lightweight JavaScript animation library with a simple but powerful API.
- [React-Window](https://github.com/bvaughn/react-window) - React components for efficiently rendering large lists and tabular data.
- [pg-boss](https://github.com/timgit/pg-boss) — Job queueing library for Node.js backed by PostgreSQL.
- [Design Patterns PHP](https://designpatternsphp.readthedocs.io/en/latest/) - This is a collection of known design patterns and some sample code how to implement them in PHP.

### Databases

- [SQLite Tutorial](https://www.sqlitetutorial.net/) — Practical tutorial series covering SQLite from basics to advanced usage.

---

## Real-Time & Media

- [LiveKit](https://livekit.com/) — Open source infrastructure for real-time audio, video, and data. WebRTC at scale.
- [openWakeWord](https://github.com/dscripka/openWakeWord) — Open-source wake word and phrase detection framework focused on performance and simplicity.

---

## 3D & Graphics

- [Three.js](https://threejs.org/) — JavaScript library for creating 3D graphics in the browser using WebGL.
- [SuperSplat](https://github.com/playcanvas/supersplat) — Browser-based 3D Gaussian splat editor by PlayCanvas.
- [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) — Official implementation of the SIGGRAPH 2023 paper on real-time 3D Gaussian splatting for novel view synthesis.
- [RodinHD](https://github.com/RodinHD/RodinHD) — High-fidelity 3D avatar generation using diffusion models. (ECCV 2024)
- [glTF-Transform](https://github.com/donmccurdy/glTF-Transform) — Read, edit, and write 3D models in glTF/GLB format via Node.js or CLI.
- [Vulkan Tutorial](https://vulkan-tutorial.com/) — Step-by-step guide to the Vulkan graphics and compute API.
- [Vulkan.org — Learn](https://www.vulkan.org/learn) — Official Vulkan learning resources from the Khronos Group.
- [vkguide.dev](https://vkguide.dev/) — Practical guide to building a Vulkan renderer from scratch.

---

## AI & Machine Learning

### Tools & Frameworks

- [LlamaIndex](https://www.llamaindex.ai/) — Data framework for connecting LLMs to external data sources and building RAG pipelines.
- [LangChain](https://www.langchain.com/) — Framework for building LLM-powered applications with chains, agents, and memory.
- [Weights & Biases](https://wandb.ai/site) — ML experiment tracking, model monitoring, and dataset versioning platform.
- [Unsloth](https://unsloth.ai/) — Fine-tuning framework for LLMs, focused on speed and low memory usage.
- [LM Studio JS](https://github.com/lmstudio-ai/lmstudio-js) — JavaScript SDK for interacting with LM Studio's local model runtime.
- [OpenHands](https://github.com/OpenHands/OpenHands) — Platform for AI-powered software development agents.
- [opencode](https://opencode.ai/docs/) — Open source AI coding agent for the terminal.
- [Pi](https://pi.dev/) — Personal AI development environment.
- [Odysseus](https://github.com/pewdiepie-archdaemon/odysseus) — Self-hosted AI workspace.
- [Locally Uncensored](https://github.com/PurpleDoubleD/locally-uncensored) — All-in-one local AI app for chat, image generation, and video creation. Powered by Ollama & ComfyUI.
- [Voicebox](https://github.com/jamiepine/voicebox) — Open-source AI voice studio for cloning, dictation, and creation.
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — Agentic framework by Nous Research built on the Hermes model series.
- [LingBot World](https://github.com/Robbyant/lingbot-world) — Open-source world model research.
- [Deep Live Cam](https://github.com/hacksider/Deep-Live-Cam) — Real-time face swap and deepfake video tool.
- [Niantic Spatial](https://www.nianticspatial.com/en) - Robots, agents, and autonomous systems need world models grounded in physics and geometry, not imagination.

### Leaderboards & Benchmarks

- [Artificial Analysis](https://artificialanalysis.ai/leaderboards/models) — Independent benchmarks comparing LLM quality, speed, and cost across providers.
- [LLM Stats](https://llm-stats.com/) — Live stats and rankings across major language models.

---

## Security

### Blue Team & Defensive

- [OSV Scanner](https://github.com/google/osv-scanner) — Google's open source vulnerability scanner for project dependencies.
- [OWASP Cheatsheet](https://cheatsheetseries.owasp.org/index.html) - A concise collection of high value information on specific application security topics.
- [CyberDefenders](https://cyberdefenders.org/) — Blue team training platform with real-world DFIR and SOC challenges.
- [Wazuh](https://wazuh.com/) — Open source SIEM and XDR platform for threat detection, monitoring, and response.
- [Security Onion](https://securityonionsolutions.com/) — Open source Linux distro for enterprise security monitoring, threat hunting, and log management.
- [Splunk BOTS (Boss of the SOC)](https://bots.splunk.com/login?redirect=/) — Gamified blue team training environment and dataset for SOC skill-building.
- [Splunk Attack Range v4](https://www.splunk.com/en_us/blog/security/splunk-attack-range-v4-threat-detection-emulation.html) — Framework for emulating attacks and building/testing detections.

### Red Team & Offensive

- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) — Extensive list of payloads and bypass techniques for web application security testing.
- [SecLists](https://github.com/danielmiessler/SecLists) — Collection of wordlists for security testing: usernames, passwords, URLs, fuzzing data, and more.
- [Pentest Book](https://github.com/six2dez/pentest-book) — Comprehensive pentesting methodology and notes.
- [Pentest Wiki](https://github.com/nixawk/pentest-wiki) — Free online security knowledge base for pentesters and researchers.
- [InternalAllTheThings](https://github.com/swisskyrepo/InternalAllTheThings) — Active Directory and internal network attack techniques reference.
- [sqlmap](https://github.com/sqlmapproject/sqlmap) — Automatic SQL injection detection and exploitation tool.
- [Shannon (Lite)](https://github.com/KeygraphHQ/shannon) — Autonomous AI-powered white-box pentester for web apps and APIs.
- [Deep Eye](https://github.com/zakirkun/deep-eye) — AI-driven vulnerability scanner integrating multiple LLM providers for automated bug hunting and payload generation.
- [PANIX](https://github.com/Aegrah/PANIX) — Customizable Linux persistence tool for security research and detection engineering.
- [BloodHound Legacy](https://github.com/SpecterOps/BloodHound-Legacy) — Active Directory attack path analysis tool by SpecterOps.
- [Seatbelt](https://github.com/GhostPack/Seatbelt) — C# situational awareness tool for Windows post-exploitation enumeration.
- [JAWS](https://github.com/411Hall/JAWS) — PowerShell-based Windows local privilege escalation enumeration script.
- [Reconmap](https://github.com/reconmap/reconmap) — Collaborative penetration testing and vulnerability management platform.
- [OmniProx](https://github.com/ZephrFish/OmniProx) — IP rotation tool across GCP, Azure, Alibaba, and Cloudflare. Think FireProx but multi-provider.
- [Impacket](https://salsa.debian.org/python-team/packages/impacket) — Python library for working with network protocols; widely used in AD exploitation.
- [Pwnagotchi](https://github.com/evilsocket/pwnagotchi) — AI-powered Raspberry Pi tool for Wi-Fi handshake capture via passive monitoring.
- [Bjorn](https://github.com/infinition/Bjorn) — Network scanning and offensive security tool for Raspberry Pi with e-Paper display support.
- [MSOLSpray](https://github.com/dafthack/MSOLSpray) — Password spraying tool targeting Microsoft Online (Azure AD / O365).
- [EntraSpray](https://github.com/dunderhay/entraspray) — Password spraying tool targeting Microsoft Entra ID.
- [TeamFiltration](https://github.com/Flangvik/TeamFiltration) — Cross-platform framework for enumerating, spraying, and exfiltrating from Microsoft Teams and O365.

### General Security (AppSec / Recon / Scanning)

- [Shodan Cheat Sheet](https://github.com/DAEMON-404/Shodan_Cheet-Sheet) — Quick reference for Shodan search operators and filters.
- [BuiltWith](https://builtwith.com/) - Find out what websites are Built With.
- [WhatWeb](https://whatweb.net/) - Scan your domain or IP address to identify content management systems, JavaScript libraries, web servers, and more.
- [Wappalyzer](https://www.wappalyzer.com/) - Find accounts by the technologies they use.
- [CVSS User Guide](https://www.first.org/cvss/user-guide) — FIRST's official guide to the Common Vulnerability Scoring System for rating vulnerability severity.
- [KeePassXC](https://keepassxc.org/) — Open source, cross-platform password manager.

### Write-ups & Case Studies

- [Tesla XSS Bug Bounty Write-up](https://www.securityweek.com/tesla-awards-researcher-10000-after-finding-xss-vulnerability/) — SecurityWeek coverage of a researcher-found XSS vulnerability in Tesla's infrastructure.
- [Cloudflare July 2019 Outage — Regex Backtracking](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/#appendix-about-regular-expression-backtracking) — Cloudflare's post-mortem on a global outage caused by catastrophic regex backtracking (ReDoS).

---

## OSINT

- [OSINT Framework](https://github.com/lockfale/OSINT-Framework) — Visual map of OSINT tools and techniques organized by category.
- [Awesome OSINT](https://github.com/jivoi/awesome-osint) — Curated list of OSINT tools, resources, and techniques.
- [TCM OSINT Resources](https://github.com/TCM-Course-Resources/Open-Source-Intellingence-Resources) — Resource list from TCM Security's OSINT course.
- [SpiderFoot](https://spiderrfoot.com/) — Automated OSINT and attack surface monitoring platform.
- [Maltego](https://www.maltego.com/) — Link-analysis and data-gathering platform for OSINT investigations and threat intelligence.
- [GhostTrack](https://github.com/HunxByts/GhostTrack) — OSINT tool for tracking and gathering intelligence on targets.

---

## UI & Design

- [Shadcn](https://ui.shadcn.com/) — A set of beautifully designed components that you can customize, extend, and build on.
- [Huemint](https://huemint.com/) — AI-powered color palette generator for branding and UI.
- [Fluid Type Scale](https://www.fluid-type-scale.com/) — Generate CSS clamp-based fluid typography scales.

---

## Open Source & Dev Practice

- [Nodejs Best Practices](https://github.com/goldbergyoni/nodebestpractices) - The Node.js best practices list (July 2026).
- [GitHub Open Source Guide](https://github.com/github/opensource.guide) — Best practices for launching and maintaining open source projects.
- [Microsoft Engineering Playbook](https://github.com/microsoft/code-with-engineering-playbook) — Microsoft's internal engineering best practices: code reviews, CI/CD, testing, agile, and more.

---

## Awesome Lists

- [Awesome Algorithms](https://github.com/tayllan/awesome-algorithms) — Curated resources for learning and practicing algorithms.
- [Awesome Database Learning](https://github.com/pingcap/awesome-database-learning) — Papers, books, and courses on database internals and theory.
- [Awesome APIs](https://github.com/whizkydee/Awesome-APIs) — Collection of public APIs organized by category.
- [Awesome Fuzzing](https://github.com/secfigo/Awesome-Fuzzing) — Curated list of fuzzing resources, tools, and tutorials.
- [Awesome Node.js](https://github.com/sindresorhus/awesome-nodejs) — Sindre Sorhus's curated list of Node.js packages and resources.
- [Awesome React](https://github.com/enaqx/awesome-react) — Comprehensive collection of React ecosystem tools, libraries, and learning resources.
- [Awesome Agent Skills](https://github.com/heilcheng/awesome-agent-skills) — Skills, tools, and capabilities for AI coding agents (Claude, Codex, Copilot, VS Code).
- [Awesome Software Engineering](https://github.com/Alliedium/awesome-software-engineering) - A curated list of awesome software engineering resources.
- [Repos for Software Engineering Study](https://orozaskarov.medium.com/top-github-repos-for-free-software-engineering-study-resources-e8c36c696be6) - Some of the top GitHub repositories that are absolute goldmines.

---

## Community & Threads

- [Thread by @0xchromium](https://x.com/0xchromium/status/2063321324605280569)
- [Thread by @ai_rohitt](https://x.com/ai_rohitt/status/2065674564663996575)
- [Thread by @0xMovez](https://x.com/0xMovez/status/2058923765526864337)

---

## Education

*Certifications and structured learning materials, grouped by the topic they support.*

### Security — Blue Team & Defensive

- [DevSecOps Professional](https://www.practical-devsecops.com/certified-devsecops-professional/) - Certification teaches you to build automated security pipelines, manage vulnerabilities at scale, and drive the cultural change needed to make security everyone's responsibility.

### Security — Red Team & Offensive

- [GIAC GWAPT Certification](https://www.giac.org/certifications/web-application-penetration-tester-gwapt) — Web Application Penetration Tester certification by GIAC.
- [Real-World Bug Hunting (PDF)](https://github.com/Raunaksplanet/My-CyberSecurity-Store/blob/main/Books/Real-World%20Bug%20Hunting%20-%20A%20Field%20Guide%20to%20Web%20Hacking.pdf) — Peter Yaworski's field guide to web hacking and bug bounty hunting.
- [Metasploit Unleashed](https://www.offsec.com/metasploit-unleashed/) — Free, comprehensive guide to Metasploit from Offensive Security.

### Security — General

- [ISC2](https://www.isc2.org/about) - A non-profit organization which specializes in training and professional certifications for cybersecurity professionals.
- [Digital Skills & Job Platforms](https://digital-skills-jobs.europa.eu/en/cybersecurity-skills-academy) - The Cyber Skills Academy is an EU initiative aiming at addressing the growing cybersecurity skills and talent shortage in Europe.

### Cloud, DevOps & Infrastructure

- [Kubernetes KCNA](https://training.linuxfoundation.org/certification/kubernetes-cloud-native-associate/) - Proving you understand cloud native ecosystems will help you land that dream job.
- [Github Actions](https://learn.github.com/certification/ACTIONS) - This exam is designed for DevOps engineers, software developers, and IT professionals.
- [Terraform Associate](https://developer.hashicorp.com/certifications/infrastructure-automation) - Demonstrate your advanced Terraform production experience with the Terraform Authoring and Operations Professional certification.
- [AWS AI Practicioner](https://aws.amazon.com/certification/certified-ai-practitioner/) - Validates in-demand knowledge of artificial intelligence (AI), machine learning (ML), and generative AI concepts and use cases.
- [AWS Cloud Practicioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) - This is a good starting point on the AWS Certification journey for individuals with no prior IT or cloud experience switching to a cloud career or for line-of-business employees looking for foundational cloud literacy.
- [Linux Foundation IT Associate](https://training.linuxfoundation.org/certification/certified-it-associate/) - It is ideal for those getting started in an IT career as an administrator/engineer.

### AI & Machine Learning

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — The original transformer paper by Vaswani et al. (2017). Foundational reading for understanding modern LLMs.
- [Prompt Injection Attacks](https://arxiv.org/html/2601.17548v1) - A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems.
- [Neural Networks: Zero to Hero — Karpathy](https://karpathy.ai/zero-to-hero.html) — Andrej Karpathy's ground-up video series on building neural networks from scratch.
- [AI Engineer Roadmap](https://roadmap.sh/ai-engineer) — Structured roadmap for becoming an AI engineer, from fundamentals to deployment.
- [CS50 AI](https://cs50.harvard.edu/ai/) — Harvard's introduction to AI with Python. Covers search, knowledge, learning, neural networks, and language.
- [Elements of AI](https://www.elementsofai.com/) - The Elements of AI is a series of free online courses created by MinnaLearn and the University of Helsinki.
- [Microsoft AI For Beginners](https://microsoft.github.io/AI-For-Beginners/) — Open-source curriculum from Microsoft covering AI fundamentals across 24 lessons.
- [Prompt Engineering](https://www.promptingguide.ai/) - Prompt engineering skills help to better understand the capabilities and limitations of large language models.
- [Agents.md](https://agents.md/) - A dedicated, predictable place to provide the context and instructions to help AI coding agents work on your project.
- [Agent Skills](https://agentskills.io/home) — Learn how a standardized way to give AI agents new capabilities and expertise works.
- [Skills.sh](https://www.skills.sh/) — Reusable capabilities for AI agents. Install them with a single command.
- [Robots, Agents, and World Models — VT Engineering](https://eng.vt.edu/magazine/stories/fall-2023/ai.html) — Virginia Tech feature on AI and autonomous systems research. `[article to read]`

### General / Foundational CS

- [Universidade Aberta](https://portal.uab.pt/?lang=en) - Established in 1988, Universidade Aberta (UAb) is the single public distance education university in Portugal.
- [You Don't Know JavaScript](https://github.com/getify/You-Dont-Know-JS) - A book series (2 published editions) on the JS language.
- [Structure and Interpretation of Computer Programs](https://web.mit.edu/6.001/6.037/sicp.pdf) - It teaches fundamental principles of computer programming, including recursion, abstraction, modularity, etc...
- [Software Engineering](https://dn790001.ca.archive.org/0/items/bme-vik-konyvek/Software%20Engineering%20-%20Ian%20Sommerville.pdf) - A broad perspective on software processes, requirements, and design.
- [Computer Networking A Top-Down Approach](https://qige.io/network/Kurose-7.pdf) - Introduces this complex subject in a top-down manner, proceeding from the application layer toward the physical layer and familiarizing you with important concepts early in your study.
- [Cracking the Code Interview](https://dn760101.eu.archive.org/0/items/4-programming-interviews-exposed-4th-edition/Cracking-the-Coding-Interview-6th-Edition-189-Programming-Questions-and-Solutions.pdf) - Gives you the interview preparation you need to get the top software developer jobs.
- [Full Stack Open](https://fullstackopen.com/en/#course-contents) — Free deep-dive course from the University of Helsinki covering React, Node, GraphQL, TypeScript, and more.
- [Vercel Academy](https://vercel.com/academy) — Structured learning resources from Vercel covering Next.js, deployment, and frontend infrastructure.
- [Build Your Own X](https://github.com/codecrafters-io/build-your-own-x) - Master programming by recreating your favorite technologies from scratch.
- [Patterns.dev — React](https://www.patterns.dev/react/) — In-depth guide to React design patterns and rendering strategies.
- [RFC 9110 — HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110.html) — The current IETF standard defining HTTP semantics, shared across HTTP/1.1, HTTP/2, and HTTP/3.
- [Encrypted DNS in Browsers — Cloudflare](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) — Reference on DNS-over-HTTPS and how browsers implement encrypted DNS.

---
---

# Other Fields

## Hardware & Tinkering

- [How to Set Up a Raspberry Pi Email Server](https://www.sunfounder.com/blogs/news/how-to-set-up-a-raspberry-pi-email-server-a-complete-step-by-step-guide) — SunFounder step-by-step guide for self-hosting an email server on a Pi.

---

## Streaming & Broadcasting

- [LoL Esports Broadcasting Guide](https://github.com/SolitudeRA/LoL-Esports-Broadcasting-Guide) — Practical tips for high-quality esports streams: OBS setup, audio management, and scene switching.

### Platform Statistics & Analytics

- [Streams Charts](https://streamscharts.com/overview) — Live streaming analytics across Twitch, YouTube, Kick, and more.
- [Twitch Tracker](https://twitchtracker.com/statistics/games) — Historical and current game viewership statistics on Twitch.
- [Twitch Metrics](https://www.twitchmetrics.net/games/viewership) — Game viewership trends and channel analytics for Twitch.
- [Social Blade](https://socialblade.com/) — Creator growth tracking across Twitch, YouTube, TikTok, and other platforms.
- [KickStats](https://www.kickstats.com/) — Viewer and streamer statistics for the Kick platform.
- [Steam Charts](https://steamcharts.com/) — Concurrent player statistics for Steam games over time.
- [SullyGnome](https://sullygnome.com/games/watched) — Detailed Twitch analytics: hours watched, peak viewers, and game trends.

---

## Psychology of Games

- [Psychology of Games](https://www.psychologyofgames.com/about/) — Applied psychology concepts through the lens of video games.
- [The Psychological Appeal of Video Games (NIH)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6676913/) — Peer-reviewed paper on motivation, flow, and need satisfaction in gaming contexts.
- [Exploring the Psychology of Gaming](https://greatermanchester.ac.uk/blogs/exploring-the-psychology-of-gaming) — Greater Manchester overview of cognitive and behavioral research around gaming habits.

---

## Reading & Culture

*Non-technical reading, and writing/music-adjacent tools — kept as one topic since it's not meant to expand.*

- [The Demon-Haunted World — Carl Sagan](https://archive.org/details/B-001-001-709/page/n11/mode/2up) — Sagan's case for scientific thinking and skepticism. Free on the Internet Archive.
- [Tolkien Gateway](https://tolkiengateway.net/wiki/The_Silmarillion#Contents) - The Tolkien Gateway is a fan wiki that documents J. R. R. Tolkien's fantasy world of Middle-earth.
- [Psychological Types — C.G. Jung](https://archive.org/details/dli.ernet.7919/page/n11/mode/2up) — Jung's foundational work on psychological typology and individuation. Free on the Internet Archive.
- [Psychology and Alchemy — C.G. Jung](https://maypoleofwisdom.com/wp-content/uploads/2021/02/collected-works-of-c.g.-jung-volume-12-psychology-and-alchemy-pdfdrive-.pdf) — Volume 12 of Jung's Collected Works. Explores alchemical symbolism as a map of the unconscious.
- [Beyond Music Theory — Cadences and Negative Harmony](https://www.beyondmusictheory.org/cadences-and-negative-harmony/) — Theory deep dive on cadences and the concept of negative harmony.
- [Psychology of Intelligence Analysis](https://www.ialeia.org/docs/Psychology_of_Intelligence_Analysis.pdf) - Interesting application of cognitive psychology and decision analysis in intelligence analysis.
- [Information Theory — Britannica](https://www.britannica.com/science/information-theory/Physiology) — Overview of information theory concepts, including their application to physiological/neural signaling.
- [Pro Writing Aid](https://prowritingaid.com/) - ProWritingAid helps you craft, polish, and elevate your writing.
- [StudioBinder](https://www.studiobinder.com/) — Production management platform with screenwriting, shot list, and storyboard tools for filmmaking.
- [Scriptslug](https://www.scriptslug.com/) — Free repository of downloadable screenplays for film and TV.

*Last updated: August 2026*
