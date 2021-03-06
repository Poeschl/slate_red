# Slate Red

[![hacs_badge](https://img.shields.io/badge/HACS-default-orange.svg)](https://github.com/custom-components/hacs)

My red"isch" variant of the [slate theme](https://github.com/seangreen2/slate_theme).

## Installation

### Home Assistant Community Store

Install it in the `Frontend` section of the Home Asssistant Community Store.


### Manual

Copy the `themes/slate_red.yaml` file to a local folder called `themes` on the same folder level as your `configuration.yaml`.

Also include the following in your `configuration.yaml`:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```
  
Restart Home Assistant and select your theme by clicking on your user's profile circle in the bottom left.

## Screenshots

![Lovelace](https://raw.githubusercontent.com/Poeschl/slate_red/master/assets/lovelace1.png)

![Lovelace](https://raw.githubusercontent.com/Poeschl/slate_red/master/assets/lovelace2.png)

![Lovelace](https://raw.githubusercontent.com/Poeschl/slate_red/master/assets/integrations.png)

![Lovelace](https://raw.githubusercontent.com/Poeschl/slate_red/master/assets/settings.png)

![Lovelace](https://raw.githubusercontent.com/Poeschl/slate_red/master/assets/devtools.png)


[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white)](https://www.buymeacoffee.com/Poeschl)
