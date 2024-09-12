# Queue Management System

## Overview

This Queue Management System is a web-based simulation tool designed to model and analyze queuing scenarios. It provides real-time visualization of server occupancy, queue length, and generates comprehensive statistics for queue performance analysis. [WebApp](https://queuing-data-collector.onrender.com/)



## Features

- **Dynamic Server Configuration**: Easily set up multiple service points.
- **Real-time Simulation**: Watch as customers enter, wait, and leave the system.
- **Interactive Controls**: Manually add customers or stop the simulation at any time.
- **Detailed Analytics**: Get insights on waiting times, service times, and overall system efficiency.
- **Data Export**: Download customer data and queue metrics in CSV format for further analysis.
- **Responsive Design**: User-friendly interface that works on various devices.

## Technology Stack

- **Backend**: Flask (Python)
- **Frontend**: Vue.js, Axios for API calls
- **Styling**: Custom CSS with animations

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/queue-management-system.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

4. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Set the number of servers and start the simulation.
2. Use the "Customer Enter" button to add new customers to the queue.
3. Click "Leave" on occupied servers to complete customer service.
4. Stop the simulation to view summary statistics and download data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to all contributors who have helped shape this project.
- Inspired by real-world queue management challenges in various industries.
