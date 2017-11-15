# hass-dominos-panel
Custom panel for displaying nearest dominos menu in Home Assistant.

## Installation
Assuming you have the Dominos component enabled in your Home Assistant installation, download the ha-panel-dominos.html and save it in `<config dir>/panels/` (you might have to create the directory if it doesn’t exist)

Add the following to your config to enable the panel:

```
panel_custom:
  - name: dominos
    sidebar_title: Dominos
    sidebar_icon: mdi:pizza
    url_path: dominos
```

Then make sure to edit your config file so that the Dominos config includes `show_menu: 1`