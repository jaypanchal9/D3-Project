# Road Accidents Analysis of Melbourne, Victoria

This project visualizes road accidents data in the Australian state of Victoria from 2018 to 2022 using a tree diagram and an interactive timeline. Built with D3.js, HTML, and CSS, the visualization allows users to explore accident trends by speed zones, weekdays, and years.

## Features

- **Interactive Tree Diagram**: Displays accident counts grouped by speed zones (≤50 km/h, 50-100 km/ph, and 100-110 km/ph).
- **Interactive Timeline**: Accident counts per day of the week, connected interactively with the tree diagram.
- **Hover Interaction**: Highlight nodes and timeline bars, and display detailed accident data via tooltips.
- **Color Legend**: Sequential color scale representing accident counts.

## Technologies Used
- **D3.js** (Data-Driven Documents)
- **HTML5**
- **CSS3**

## Project Structure
- `Road_Accident_code.html`: Core HTML and JavaScript implementation.
- `color-legend.js`: Module for generating color legends in D3.js visualizations.
- `accident_data.csv`: Contains accident counts per year, speed zone, and day of the week.
- `roads_hierarchy.json`: Defines the hierarchical structure used in the tree diagram (by speed zones and years).

## Setup

Clone this repository and open `Road_Accident_code.html` in a web browser. Ensure you have an internet connection as the project relies on external D3.js CDN.

## Data Sources
- Accident data sourced from official Victoria road accident statistics (included as `accident_data.csv`).

## References
- [D3 Tree Diagram Tutorial](https://www.developer.com/design/creating-a-tree-diagram-with-d3-js/)
- [D3 Color Legend](https://observablehq.com/@d3/color-legend)
- [ColorBrewer](https://colorbrewer2.org/)
- [Ying Yang](https://github.com/yingyangvis)
  
## Contributors
- [Jay Panchal](https://github.com/jaypanchal9)

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.
