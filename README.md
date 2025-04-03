# Energy-Efficient-CPU-Scheduler
 Develop a CPU scheduling algorithm that minimizes energy consumption without compromising performance. The algorithm should be suitable for mobile and embedded systems where power efficiency is critical.
# ⚡ Energy-Efficient CPU Scheduler

The **Energy-Efficient CPU Scheduler** is an application that helps to minimize energy consumption while ensuring high performance in task scheduling. This project is especially useful for mobile, embedded, and low-power systems where energy efficiency is a priority. The scheduler uses a priority-based scheduling algorithm to efficiently schedule tasks, and it visualizes task execution through a Gantt chart, providing both energy consumption statistics and efficiency metrics.

This project demonstrates how energy-aware CPU scheduling algorithms can be implemented to optimize energy usage without compromising the performance or responsiveness of a system.

## Features

- **Task Scheduling Algorithm**: Tasks can be added with unique IDs, burst times (execution time), and priorities (1 to 5). 
- **Energy Consumption Calculation**: Calculates the energy consumed by each task based on its burst time and priority.
- **Efficiency Metrics**: Displays the overall scheduling efficiency, which is computed based on the total energy consumed relative to the total burst time.
- **Gantt Chart Visualization**: The execution timeline of tasks is shown on a Gantt chart, providing a clear visual representation of task scheduling.
- **Theme Toggle**: Switch between a **dark** or **light** theme for the user interface based on personal preference.
- **Task Management**: Add, view, and remove tasks easily from the GUI.
- **Error Handling**: The app includes validation and error handling for incorrect task input to ensure smooth operation.

## Requirements

To run this project, you need Python 3.x and the following Python libraries:

- **tkinter**: For the graphical user interface (GUI).
- **matplotlib**: For visualizing the Gantt chart.

### Installing Dependencies

To install the required dependencies, run the following command:

```bash
pip install matplotlib
