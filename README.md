# Virtual Infrastructure Monitoring

## Overview
This project provides a **monitoring solution** for virtualized infrastructure, allowing users to track key system performance metrics such as **CPU usage, memory utilization, and network activity**. It logs performance data, generates visual insights, and provides a summary of system health.

## Features
- **Automated Performance Logging** – Captures real-time VM performance metrics.
- **Graphical Data Visualization** – Generates graphs to analyze performance trends.
- **System Health Reports** – Provides concise status updates on system health.
- **Easy-to-Use Jupyter Notebook** – Run all functionalities within a single notebook.

## Project Structure
```
📂 virtual-infra-monitoring
│── virtual_infra_monitoring.ipynb   # Jupyter Notebook with scripts
│── vm_performance_graph.png         # Graph of system performance trends
│── vm_performance_log.csv           # Logged performance metrics
│── vm_status.txt                    # Summary report of VM health
│── README.md                         # Project documentation
```

## Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/Janhvi-Pandya/virtual-infra-monitoring.git
cd virtual-infra-monitoring
```

### 2. Run the Jupyter Notebook
```bash
jupyter notebook virtual_infra_monitoring.ipynb
```

### 3. Output Files
- **vm_performance_log.csv** – Contains recorded system performance data.
- **vm_performance_graph.png** – A visualization of performance trends.
- **vm_status.txt** – A summary report of system health.

## Technologies Used
- **Python** – Data processing & automation
- **Matplotlib** – Graph generation
- **Pandas** – Data handling
- **Jupyter Notebook** – Execution environment

## Contributing
Contributions are welcome! If you'd like to improve this project, feel free to:
1. **Fork the repository**
2. **Submit issues**
3. **Open a pull request**
