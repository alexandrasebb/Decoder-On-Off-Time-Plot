# Shift On/Off Time Plot

A Python project to visualise shift patterns for workers or devices over a 24-hour period.

## Shift Pattern Visualiser

This Python script generates a plot of on/off times for workers or devices, such as decoders, allowing you to see their shift patterns clearly. The script processes predefined time data, converts it into a format suitable for plotting, and visualises it using matplotlib.

## Features

- **Shift Time Visualisation**: Creates a horizontal bar plot representing on/off intervals for each worker or decoder.
- **Customisable Data**: Easily modify the script to represent different workers, decoders, or time intervals.
- **Time Handling**: Correctly handles shifts that span across midnight.
- **Dynamic Plot**: Automatically adjusts to the number of workers or decoders.

## Getting Started

### Prerequisites

- Python 3.x
- `matplotlib`
- `pandas`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/shift_on_off_time_plot.git
   cd shift_on_off_time_plot
   ```

2. Install the required Python packages:

   ```bash
   pip install matplotlib pandas
   ```

### Running the Script

You can run the script using Python:

```bash
python shift_on_off_time_plot.py
```

### Usage

By default, the script plots shift times for a set of decoders. To customise it for different workers or decoders, modify the `decoder_times` dictionary in the script. 

For example, replace:

```python
decoder_times = {
    1: [('06:30:00 AM', '11:00:00 PM')],
    # Add more decoders and their times
}
```

With:

```python
shift_times = {
    'Worker 1': [('06:30:00 AM', '11:00:00 PM')],
    'Worker 2': [('07:00:00 PM', '10:30:00 PM')],
    # Add more workers and their shifts
}
```

After modifying the data, run the script to generate the updated plot. The output will include:

- A time series plot showing on/off intervals for each worker or decoder.
- The y-axis labelled with worker or decoder identifiers.
- The x-axis representing time in hours.

### Example Output

The plot will display:
- **Time** on the x-axis, showing the full 24-hour period.
- **Workers or Decoders** on the y-axis, with each interval represented by a horizontal line.
- **Different Colours** for each worker or decoder to distinguish their shift patterns.

## Customisation

Feel free to customise the script to:

- Represent different types of entities (e.g., machines, devices).
- Modify the plot appearance, such as colours and labels.
- Adapt time formats or add additional data visualisations.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements, bug fixes, or features you would like to add.

## Contact

For any questions or feedback, please reach out to:

Alexandra Boliver-Brown - aboliverbrown@hotmail.com  
GitHub: [alexandrasebb](https://github.com/alexandrasebb)
