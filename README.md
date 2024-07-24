# Matterbridge Home Assistant Addon

This Home Assistant Add-On populates entities of the home assistant instance as a Matter-bridge.

You can find the changelog [here](https://github.com/t0bst4r/matterbridge-home-assistant/releases).

# Supported Entity Domains
See the main project for a [list of supported entities](https://github.com/t0bst4r/matterbridge-home-assistant?tab=readme-ov-file#supported-entities).

# Installation

Open Home Assistant and navigate to the addon settings.
![Home Assistant Settings](docs/hass-settings.png)

Open up the Add-On store and open the "Repositories" menu in the top-right corner.
![!Home Assistant Add-On Store](docs/hass-addon-store.png)

Enter the URL of the GitHub Repo to the list of your add-on
repositories (`https://github.com/t0bst4r/matterbridge-home-assistant-addon`).
![Home Assistant Add Repository](docs/hass-add-repo.png)

After the repository is added, refresh your Add-On Store page and find the Add-On in your list of Add-Ons.
![Home Assistant Add-On Store with the new Add-On](docs/hass-addon-store-with-repo.png)

Open the Add-On page and click "install".
![Home Assistant Matterbridge Add-On](docs/hass-matterbridge-addon.png)

**Before starting the plugin** open the configuration tab and enter your configuration.

![Home Assistant Matterbridge Add-On Configuration](docs/hass-matterbridge-configuration.png)

Start the addon and find the commissioning QR code in the Add-On logs or the web ui.
This code can be used to connect your Matter clients (like Alexa, Apple Home or Google Home) to the bridge.

![Matterbridge commissioning code](docs/matterbridge-commissioning.png)

# Contributors

[![Contributors](https://contrib.rocks/image?repo=t0bst4r/matterbridge-home-assistant-addon)](https://github.com/t0bst4r/matterbridge-home-assistant-addon/graphs/contributors)

---

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/t0bst4r)
