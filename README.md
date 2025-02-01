# Health Monitoring for High Performance Computing (HPC) Systems

Iowa State University - Senior Design Project

Authors: Eric Hedgren, Tate Myers, Eli Newlin, Gavin Fisher, Max Rohrer

Client: Lockheed Martin

## Sensors/Data
1. CPU Sensors
    - Temperature: Measures the temperature of the CPU to prevent overheating.
    - Load: CPU usage percentage for each core.
    - Clock Speed: Current operating frequency of the CPU.
    - Voltage: Power supply to the CPU.

2. GPU Sensors
    - Temperature: Measures the GPU temperature.
    - Load: GPU utilization percentage.
    - Memory Usage: Amount of memory used by the GPU.
    - Power Consumption: Power used by the GPU.
    - Clock Speed: Operating frequency of the GPU.

3. Memory (RAM) Sensors
    - Usage: Percentage of memory being used.
    - Temperature: Temperature of the memory modules.
    - Latency: Latency in memory access.

4. Disk Sensors
    - Temperature: Temperature of the hard drives or SSDs.
    - Read/Write Speed: Current data transfer rate.
    - I/O Operations: Number of input/output operations per second (IOPS).
    - Capacity: Available storage space.

5. Network Sensors
    - Bandwidth Usage: Amount of data being sent and received.
    - Latency: Time taken for data to travel across the network.
    - Error Rate: Number of network packet errors.
    - Connection Speed: Current speed of the network interface.

6. Power Supply Sensors
    - Voltage: Voltage levels supplied by the power unit to the system.
    - Current: Current flowing from the power supply.
    - Power Consumption: Total power usage (could be an aggregate or broken down by components like CPU, GPU, etc.).
    - Temperature: Temperature of the power supply unit.

10. System Performance Metrics

    - Throughput: Data processing rate (e.g., instructions per second or FLOPS).
    - Running Jobs: All the currently running jobs
    - Jobs in queue/scheduled: All the jobs that are in the queue or are scheduled
    - Error Rate: System errors or failed computations.