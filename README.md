# LEO-Satellite-Network-Simulation
#Hypatia - LEO Satellite Network Simulation Framework
# Hypatia - LEO Satellite Network Simulation Framework

## Overview
Hypatia is a comprehensive Python-based simulation framework designed for modeling and analyzing Low Earth Orbit (LEO) satellite constellations such as Kuiper, Starlink, and Telesat. This framework enables researchers to simulate satellite network states, communication links, and evaluate network performance under realistic conditions.

## Key Features
- Simulation of satellite states and communication links (Ground-to-Satellite and Inter-Satellite links)
- Support for multiple constellation models including Kuiper, Starlink, and Telesat
- Integration with ns-3 simulator for network simulation and data analysis
- Tools for satellite constellation state generation and visualization

## System Requirements
- Linux operating system (Ubuntu 18.04 or later recommended)
- Python 3.7 or higher
- ns-3 network simulator with required dependencies
- Additional Python packages: numpy, exputil, matplotlib, and others (see `requirements.txt`)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hypatia.git


Navigate to the project directory:

bash
Copy
cd hypatia
Install Python dependencies:

bash
Copy
pip install -r requirements.txt
Build and install ns-3 modules as per instructions in the docs folder.

Usage
Generate satellite constellation states using provided Python scripts.

Run network simulations using ns-3 integration modules.

Analyze and visualize results with included plotting tools.

Example Commands
bash
Copy
python3 scripts/satellite_state_generator.py --constellation starlink
./ns3 run hypatia-simulation
Results
Includes detailed visualizations of satellite orbits, communication link quality, and network performance metrics.

Challenges and Solutions
Addressed compilation errors by patching ns-3 modules.

Optimized simulation runtime by refining event scheduling.

References
Hypatia GitHub Repository (original)

Research papers and documentation provided in /docs

Contact
Aqib Mushtaq
Email: aqibmushtaq2024@gmail.com
LinkedIn: linkedin.com/in/aqib-mushtaq8


