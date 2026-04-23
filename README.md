# Cloud Network Simulator
A sophisticated network simulation tool that models cloud infrastructure with dynamic traffic flows, congestion control, and real-time visualization. Built with Python, NetworkX, and Matplotlib.

## Project Description

This **Cloud Network Simulator** provides a comprehensive simulation environment for cloud network infrastructures, including routers, datacenters, and users. It models realistic network behavior with dynamic traffic flows, adaptive routing, congestion control mechanisms, and extensive performance metrics visualization.

### Key Capabilities

- **Dynamic Network Topology** - Create custom or default network configurations
- **Traffic Flow Simulation** - Model packet-level traffic with realistic patterns
- **Congestion Control** - Implement TCP-like congestion window management
- **Adaptive Routing** - Dynamic path selection based on link utilization
- **Performance Analytics** - Real-time metrics collection and visualization
- **Interactive Dashboard** - Comprehensive visualization suite

## Features

### Network Modeling
- Multiple node types (Routers, Datacenters, Users)
- Custom topology definition
- Bandwidth and delay constraints per link
- Link utilization tracking
- Adaptive routing algorithms

### Traffic Simulation
- Dynamic flow generation and expiration
- Multiple flow types (user-datacenter, datacenter-datacenter, user-router)
- Packet-level simulation
- TCP congestion window modeling
- Flow rate variability

### Metrics & Visualization
- Throughput monitoring per flow
- Latency tracking with congestion impact
- Packet loss calculation
- Link utilization heatmaps
- Real-time dashboards
- Time-series analysis
- Export to CSV for further analysis

### Configuration Options
- JSON configuration file support
- Manual interactive topology setup
- Customizable simulation parameters
- Adjustable traffic patterns

## Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/safiamussaratt/cloud-Network-Simulation.git
cd Cloud-Network-Simulation
```

2. Install required packages:
```bash
pip install matplotlib networkx pandas numpy seaborn
```

3. Run the simulator
```bash
python cloud_network_simulation.py
```

## Output Files
The simulator generates comprehensive outputs in the results/ directory:

### Dashboards (results/dashboards/)
- 00_main_dashboard.png - Complete overview dashboard
- 01_topology.png - Network topology visualization
- 02_throughput.png - Flow throughput over time
- 03_latency.png - Flow latency analysis
- 04_packet_loss.png - Packet loss metrics
- 05_link_utilization.png - Current link utilization
- 06_link_utilization_history.png - Utilization time-series
- 07_statistics.png - Summary statistics

### Data Export (results/csv_data/)
network_metrics.csv - Complete simulation metrics (time, flow_id, throughput, latency, packet_loss, congestion_window)
