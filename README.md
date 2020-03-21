# QGIS2Wegue 

A QGIS plugin for creating [Wegue](https://github.com/meggsimum/wegue) configurations based on a QGIS project.

## Disclaimer

This plugin is still work in progress. Supported formats so far:
- `WMS`
- `WFS`
- `XYZ`
- `KML`
- `GeoJSON`

## Installation

On Ubuntu/Debian:

```shell
# enter QGIS plugin directory
cd ~/.local/share/QGIS/QGIS3/profiles/default/python/plugins
# download plugin
git clone https://github.com/meggsimum/qgis2wegue
```

- restart QGIS
- open the plugin manager and activate the plugin
- the plugin should show up in the toolbar


## Usage

- Add all your desired layers to QGIS
- Open the plugin, chose a filepath and click `OK`
- Now you have a configuration file that works with Wegue 