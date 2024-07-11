# 🚁 UAV Network Simulation with ns-3 📡

## 📚 Introduction

This study employs the ns-3 library to simulate drone networks and ground station communication, extracting signal data like signal-to-noise ratio and drone specifics. The ns-3's object factory feature enables flexible creation of various entities, including UAVs. The linked script is compatible with ns-3 version 3.21.

## 🌟 Features

- 🛰️ Simulation of UAV networks
- 📊 Signal data extraction (e.g., signal-to-noise ratio)
- 🏗️ Flexible entity creation using ns-3's object factory
- 📡 Ground station communication simulation

## 🚀 Getting Started

### Prerequisites

- ns-3 (version 3.21)
- C++ compiler

### Installation

1. Clone the repository:
```
   git clone https://github.com/yourusername/uav-network-simulation.git
```

2. Navigate to the project directory:
   ```
   cd uav-network-simulation
   ```
   
3. Compile the simulation:
   ```
   ./waf configure --enable-examples
   ./waf build
   ```
## 🖥️ Usage

Run the simulation using:
```
./waf --run uav_network_simulation
```

## 📊 Output

The simulation generates the following output files:
- `Fanetex.xml`: NetAnim XML trace
- `Fanetex.tr`: ASCII trace metrics

## 🛠️ Configuration

You can modify simulation parameters in the `uav_network_simulation.cc` file, such as:
- Number of WiFi nodes
- Mobility models
- Network topology

Happy simulating! 🚀🛰️