[< Go back to Home](../index.md)

# Configuration

Dwains Theme configuration is loaded from the files inside the folder `dwains-theme/configs/`.

**If you edit something inside a file of the `dwains-theme/configs/` folder, you always need to reload the theme configuration for any changes to be visible. Go to the more page and click on theme settings, there you can click Reload theme configuration. Or do a service call in the developer tools `dwains_theme.reload`**

This folder can have the following files: `global.yaml`, `house_information.yaml`, `scenes.yaml`, `cameras.yaml`, `persons.yaml`, `rooms.yaml`, `icons.yaml`, `more_page.yaml` and `dynamic_page.yaml`.

Only the files `global.yaml`, `rooms.yaml` and `icons.yaml` are required!

*HINT: You can always look in the `dwains-theme/configs-samples` folder files for some inspiration.*

*HINT: For the icons I mostly use Font Awesome, [How to choose and use an icon](../how-tos/how-to-choose-icon.md).*

*HINT: Some entries can have a single entity or a group [read here how to make a group](https://www.home-assistant.io/integrations/group/).*

## Configuration
* [global.yaml](global.md)
* [rooms.yaml](rooms.md)
* [house_information.yaml](house_information.md)
* [scenes.yaml](scenes.md)
* [cameras.yaml](cameras.md)
* [persons.yaml](persons.md)
* [icons.yaml](icons.md)
* [more_page.yaml](more_page.md)
* [dynamic_page.yaml](dynamic_page.md)