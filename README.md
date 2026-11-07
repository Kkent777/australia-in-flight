# Australia in Flight

An interactive guide to Australian domestic aviation. Fifteen charts show which routes carry the most passengers, how traffic recovered after disruptions, and how airport activity compares with the population of nearby cities.

[Explore the charts](https://kkent777.github.io/australia-in-flight/) · [中文导览](https://kkent777.github.io/australia-in-flight/project/)

## Run locally

Run `python3 -m http.server 8000` from the repository root and open `http://localhost:8000`. The site uses HTML, CSS, JavaScript and Vega-Lite. Chart libraries and map boundaries load from a CDN.

## Data

The [data notes](data/README_data.md) document the BITRE aviation statistics, ABS population estimates and reference periods. The four CSV extracts are in `data/`. Chart specifications are in `specs/`. Third-party datasets and libraries retain their original rights.
