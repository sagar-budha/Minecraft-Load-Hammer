# Minecraft Load Hammer

**Minecraft Load Hammer** is a network load testing tool designed to simulate multiple concurrent connections to a Minecraft server. It helps server administrators, developers, and network engineers assess the server’s performance by sending large data packets and simulating real-world traffic. This tool can uncover performance bottlenecks, network congestion, and assess the server's ability to handle heavy loads.

Whether you are testing your own server infrastructure or simulating various network conditions, Minecraft Load Hammer provides the insights you need to ensure stability and performance during peak traffic.

## Features:
- **Simulates Multiple Concurrent Connections**: The tool allows you to simulate any number of clients (threads) connecting to your Minecraft server concurrently. This is useful for stress testing to ensure the server can handle multiple users.
- **Sends Large Data Packets**: By sending large packets (ranging from 100MB to 1GB), the tool mimics the data load that users might generate during gameplay, particularly when interacting with complex systems like large worlds or active player interactions.
- **Calculates Packet Loss**: During the simulation, the tool tracks the number of failed connection attempts and computes packet loss as a percentage, offering a clear indicator of network issues.
- **Customizable Load Settings**: You can define the number of simulated connections, packet size, delay between connections, and other parameters, enabling flexible and controlled testing.
- **Simple Python Script**: Built using only standard Python libraries, the tool is easy to run and modify, making it accessible to both novice users and experienced developers.

## Requirements:
- **Python 3.x** (Ensure Python is installed on your system)
- **Libraries**: No additional libraries are required, as the tool relies on standard Python libraries:
  - `socket` (for establishing TCP connections)
  - `threading` (for simulating concurrent clients)
  - `time` (for controlling connection delays)
  - `os` (for generating random data payloads)

## Installation:

### 1. Clone the repository:
To get started, clone this repository to your local machine using Git:

```bash
git clone https://github.com/Fdydhchxy54645/Minecraft-Load-Hammer.git
```

### 2. navigate into the project directory:

```bash
cd Minecraft-Load-Hammer
```
### 3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
    
### 4.Run Script:
```bash
python3 MCLM.py
```
