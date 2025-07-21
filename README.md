# LEO-Satellite-Network-Simulation
#Hypatia - LEO Satellite Network Simulation Framework
# Hypatia - LEO Satellite Network Simulation Framework

## Overview
Hypatia is a comprehensive Python-based simulation framework designed for modeling and analyzing Low Earth Orbit (LEO) satellite constellations such as Kuiper, Starlink, and Telesat. This framework enables researchers to simulate satellite network states and communication links, and to evaluate network performance under realistic conditions.

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
## Navigate to the project directory:
```bash
cd hypatia

Install Python dependencies:
```bash
pip install -r requirements.txt

## You can follow the documentation in the docs folder to build and install ns-3 modules.


## Usage
- Generate satellite constellation states using the provided Python scripts.

- Run network simulations via ns-3 integration modules.

- Analyze and visualize simulation results with included plotting tools.

  ## Example Commands
```bash
python3 scripts/satellite_state_generator.py --constellation starlink
./ns3 run hypatia-simulation

## Results
The framework supports visualization of satellite orbits, communication link quality, and network performance metrics.

Challenges and Solutions
Resolved compilation errors by patching ns-3 modules.

Optimized simulation runtime through event scheduling improvements.

References
Hypatia GitHub Repository (original)

Related research papers and documentation in the /docs folder

Contact
Aqib Mushtaq — Master’s Student and Research Engineer
Email: aqibmushtaq2024@gmail.com
LinkedIn: linkedin.com/in/aqib-mushtaq8

yaml
Copy



