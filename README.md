# Australia in Flight

An interactive data story about Australia's domestic aviation network, created by **Chenglin Li** with **HTML, CSS, JavaScript and Vega-Lite**.

**[Explore the live visualisation](https://kkent777.github.io/fit2179-dv2/)**

[中文项目介绍与分析发现](https://kkent777.github.io/fit2179-dv2/project/)

The project connects routes, airports and population context to explore network concentration, changes in passenger activity, capacity utilisation and regional dependence on air travel.

## Explore

- Route maps and ranked comparisons for major domestic connections.
- Airport concentration and passenger/movement comparisons.
- Monthly route patterns and the disruption and recovery visible in the supplied series.
- Passenger-per-resident views that connect airport activity with urban population.

## Run locally

Serve the repository with a local static web server so the browser can load CSV and JSON files:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. No build step is required. Vega libraries are loaded from a CDN, so the page needs internet access for those dependencies.

## Repository

| Path | Contents |
| --- | --- |
| `index.html` | Story structure and chart containers |
| `styles.css` | Page layout and visual styling |
| `main.js` | Chart loading and interaction wiring |
| `specs/` | Vega-Lite chart specifications |
| `data/` | Cleaned CSV extracts and provenance notes |

## Data and context

See [data/README_data.md](data/README_data.md) for the source workbook names, periods and transformations associated with each extract. Different charts cover different reference periods; the displayed data is a saved snapshot, not a live aviation feed.

This began as the FIT2179 Data Visualisation 2 project. The repository name is retained so the existing published URL continues to work. The site and underlying data are presented with their original provenance; inclusion here does not grant additional rights to third-party datasets or libraries.

中文：这个作品用地图、趋势和交互图表讲述澳大利亚国内航空网络，展示数据整理、Vega-Lite 编码、页面组织与可视化叙事能力。

[中文项目简介（PDF）](docs/portfolio/Project-Brief-ZH.pdf)
