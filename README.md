# Neutron Star Finder

The Neutron Star Finder is a Python-based tool designed for Elite Dangerous players to locate neutron stars in the game's galaxy. It offers two main functionalities:

1. Find the nearest neutron star to a given system.
2. Locate neutron stars along a path between two systems within a specified search radius.

This tool uses the [EDSM (Elite Dangerous Star Map)](https://www.edsm.net/) API to fetch system coordinates and a local database of neutron stars for efficient searching from [spansh.co](https://spansh.co.uk/plotter).

[![requests](https://img.shields.io/badge/requests-2.31.0-blue)](https://requests.readthedocs.io/)
[![json](https://img.shields.io/badge/json-1.6.3-blue)](https://pypi.org/project/jsons/)
[![math](https://img.shields.io/badge/math-3.13.0-blue)](https://docs.python.org/3/library/math.html)
[![numpy](https://img.shields.io/badge/numpy-1.24.0-blue)](https://numpy.org/)
[![tabulate](https://img.shields.io/badge/tabulate-0.9.0-blue)](https://pypi.org/project/tabulate/)

## Features

- Find the nearest neutron star to any given system in Elite Dangerous.
- Discover neutron stars along a route between two systems.
- Customizable search radius for path-based searches.
- Color-coded console output for better readability.
- Integration with EDSM API for up-to-date system information.

## Installation

### Python

1. Clone this repository:

```bash
git clone https://github.com/BattlemasterLoL/ed-neutron-star-finder.git
```

2. Navigate to the project directory:

```bash
cd neutron-star-finder
```

3. Install the required libraries:

```bash
pip install requests numpy
```

4. Ensure you have the `systems_neutron.json` file in the same directory as the script. This file should contain a list of known neutron star systems in Elite Dangerous.

Program can also be downloaded using the [most current release](https://github.com/BattlemasterLoL/ed-neutron-star-finder/releases).

### Executable (.exe)

For users who prefer a standalone executable version of the application, follow these steps:

1. Download the latest `.exe` version from the Releases page.

2. Extract the downloaded ZIP file (if applicable) to a location of your choice.

3. Ensure the `systems_neutron.json` file is present in the same directory as the .exe file. This file is essential for the program to function correctly.

4. Double-click the `.exe` file to run the application.

#### Notes

- If you encounter any issues running the `.exe` file, make sure that your system meets the necessary requirements and that all files are correctly placed in the same directory.

- For optimal performance, it is recommended to keep the application and the `systems_neutron.json` file together.

## Dependencies

- requests
- json
- math
- numpy
- tabulate

## Usage

Run the script:

```
python neutron_star_finder.py
```

Follow the on-screen prompts to:

1. Find the nearest neutron star to a specific system.
2. Find neutron stars along a path between two systems.
3. Quit program.

For path-based searches, you can specify the search radius in light-years.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/BattlemasterLoL/ed-neutron-star-finder/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [EDSM API](https://www.edsm.net/) for providing the star system coordinate data
- [spansh.co](https://spansh.co.uk/plotter) for providing neutron star data
- The Elite Dangerous community for inspiration and support
