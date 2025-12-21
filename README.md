# Network Worm Spread Visualization Tool - README

## Overview
This is an interactive web-based simulation tool that visualizes how network worms spread across different network topologies. The tool allows users to:

- Choose network topologies (Star, Ring, Tree, Mesh)
- Select threat profiles (Worm, Virus, Trojan)
- Deploy security defenses using a budget-based system
- Visualize worm propagation in real-time
- Practice incident response with cost-graded outcomes

## Features

### 🎯 Core Simulation
- **Real-time Visualization**: Watch worm spread across dynamically generated networks
- **Multiple Topologies**: Simulate Star, Ring, Tree, and Mesh networks
- **Threat Models**: Choose between Worm, Virus, and Trojan Horse behaviors
- **Budget Mode**: Manage limited funds for security purchases and incident response
- **Interactive Controls**: Isolate nodes, cut links, and deploy recovery measures

### 🛡️ Security Shop
Purchase defenses using a security budget:
- **Honeypots** ($2,000) - Trap worms in decoy nodes
- **Firewall** ($4,000) - Reduce spread probability
- **Auto IPS** ($5,000) - Automatically isolate infected nodes
- **Hardening** ($6,000) - Reduce vulnerability
- **Backup** ($8,000) - Faster recovery and critical node protection

### 📊 Analytics & Reporting
- Live telemetry dashboard
- Infection spread timeline chart
- Financial impact tracking
- Performance grading (A-F based on capital preserved)
- Detailed incident reports

### 📚 Educational Content
- Built-in mitigation strategies for each topology
- Incident response guides
- Historical context of famous worm attacks

## Quick Start

1. **Clone or Download** the repository
2. **Open `index.html`** in any modern web browser
3. **Configure Network**:
   - Select topology type
   - Choose threat profile
   - Set node count
   - Configure budget
4. **Set Security Budget**:
   - Enter total security budget (minimum $15,000)
   - Purchase defenses from the Security Shop
5. **Generate Network** and select Patient Zero
6. **Start Simulation** and respond to the outbreak
7. **Review Report** with grade and financial outcomes

## Key Controls

- **▶ Start**: Begin worm propagation
- **⏸ Pause**: Pause/resume simulation
- **✂️ Cut Link Mode**: Manually sever network connections (-$500 each)
- **🛡 Isolate Network**: Quarantine entire network (-$5,000)
- **Recover**: Deploy anti-malware teams (-$10,000)
- **🔄 Reset System**: Start new simulation

## Grading System

Your response is graded based on percentage of initial capital preserved:

| Grade | Capital Retained | Performance |
|-------|-----------------|-------------|
| A | >80% | Excellent - Quick containment with minimal cost |
| B | >50% | Good - Contained but with some losses |
| C | >0% | Survived - Severe damage or costly response |
| F | $0 | Disaster - Unchecked spread or crippling response |

## Technical Details

- **Frontend**: Pure HTML5, CSS3, and JavaScript
- **Visualization**: Canvas-based rendering with Chart.js for analytics
- **No Dependencies**: Works offline after download
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## Learning Objectives

This tool helps understand:
- How network worms propagate
- The importance of different network topologies
- Cost-benefit analysis of security measures
- Incident response timing and strategy
- Financial implications of cybersecurity decisions

## Related Resources

The accompanying presentation (`Network Worm Spread Visualization Tool.pdf`) provides:
- Historical context of major worm attacks
- Detailed explanations of worm behavior
- Defense strategies and best practices
- Educational context for the simulation

## License

Educational Use - For academic and training purposes.

---

**Note**: This is a simulation tool for educational purposes. Real-world network security requires professional expertise and appropriate tools.
