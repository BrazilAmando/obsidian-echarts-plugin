# ECharts for Obsidian

This plugin allows you to render ECharts visualizations in Obsidian.

## Features

- Render ECharts graphs in your notes
- Support for various chart types
- Real-time preview in editing mode

## Installation

1. Open Obsidian Settings
2. Go to Third-party plugin
3. Make sure Safe mode is off
4. Click Browse community plugins
5. Search for "ECharts"
6. Click Install
7. Once installed, close the community plugins window and activate the newly installed plugin

## Usage

To create an ECharts visualization, use the following syntax in your Obsidian notes:

```echarts
{
  "title": {
    "text": "ECharts Getting Started Example"
  },
  "tooltip": {},
  "legend": {
    "data": ["sales"]
  },
  "xAxis": {
    "data": ["Shirts","Cardigans","Chiffons","Pants","Heels","Socks"]
  },
  "yAxis": {},
  "series": [{
    "name": "sales",
    "type": "bar",
    "data": [5, 20, 36, 10, 10, 20]
  }]
}