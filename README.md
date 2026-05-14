# koeki-search

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application to search and visualize data on public interest foundations in Japan.

## Demo

This project consists of two main pages:

1.  **Search Interface**: [https://code4fukui.github.io/koeki-search/](https://code4fukui.github.io/koeki-search/)
2.  **Data Dashboard**: A statistical map view, accessible from the search page.

## Features

### Search Interface
*   **Keyword Search**: Find foundations using keywords. Use spaces for AND logic and `|` for OR logic.
*   **Prefecture Filtering**: Narrow down results to a specific prefecture.
*   **National Scope Toggle**: Include or exclude foundations under the national jurisdiction of the Cabinet Office.
*   **Detailed View**: Click on a foundation in the results to expand and view its full details, including its address, representative, and business summary.
*   **External Links**: Directly access a foundation's official homepage and its page on the National Tax Agency's corporate number registry.

### Data Dashboard
*   **Interactive Map**: Visualize the number of public interest foundations across all prefectures on a tabular map of Japan.
*   **Statistical Insights**: Each prefecture on the map displays the total count of foundations and the number of foundations per 100,000 people.
*   **Choropleth View**: The map is color-coded to show the density of foundations, making it easy to compare regions.
*   **Drill-Down**: Click any prefecture on the map to instantly view a list of all foundations located there.

## Data
This project utilizes open data processed by the [Open Data of Public Interest Corporations](https://github.com/code4fukui/koeki-opendata) project.

The original data is sourced from the [Official Comprehensive Information Site for Public Interest Corporations (公益法人information)](https://www.koeki-info.go.jp/pictis-info/csa0001!show#prepage2).

## License
MIT License