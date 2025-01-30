1. InitializeApplication Subgraph:

Loads the necessary external resources, including the Chart.js library, Bootstrap Icons CSS, Tailwind CSS, and a custom font (Inter).
Sets up custom styles, such as the background color and a hover effect for the metric cards.
Initializes the DOM elements, setting the initial values for the metrics and progress bars.
Initializes the CPU usage and memory usage charts, setting up the data and options.
Adds event listeners for the refresh button click and online/offline events.
2. UpdateMetrics Subgraph:

Generates random values for CPU usage, memory usage, and network usage.
Updates the CPU usage metric, including the display, progress bar, and chart data.
Updates the memory usage metric, including the display, progress bar, and chart data.
Updates the network usage metric, including the display and progress bar.
Checks the user's network connection status and updates the network status display and icon.
3. RefreshMetrics Subgraph:

Triggers the metrics update by calling the updateMetrics function.
The flow of the application is as follows:

1. The application starts by initializing the necessary resources, setting up the styles, and configuring the DOM elements and charts.

2. The updateMetrics function is called periodically (every 2 seconds) to simulate the update of the application's metrics.

3. The updateMetrics function generates random values for CPU usage, memory usage, and network usage, and updates the corresponding metrics and charts.

4. The network status is also checked and updated based on the user's online/offline state.

5. The refresh button triggers the updateMetrics function, allowing the user to manually refresh the metrics.
