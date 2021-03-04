# Highlight Autodetect Off Plugin

The **Highlight Autodetect Off** Plugin is an extension for [Grav CMS](http://github.com/getgrav/grav). Switches off auto-detection of syntax highlight.
This plugin solves the problem: by default, the "Highlight" plugin highlights syntax in all code blocks and you need to specify each of those as "plaintext" to disable highlighting.

## Installation

### Manual Installation

To install the plugin manually, download the zip-version of this repository and unzip it under `/your/site/grav/user/plugins`. Then rename the folder to `highlight-autodetect-off`. You can find these files on [GitHub](https://github.com/alexey-rasskazov/grav-plugin-highlight-autodetect-off).

You should now have all the plugin files under

    /your/site/grav/user/plugins/highlight-autodetect-off
	
## Configuration

Before configuring this plugin, you should copy the `user/plugins/highlight-autodetect-off/highlight-autodetect-off.yaml` to `user/config/plugins/highlight-autodetect-off.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```yaml
enabled: true
```

Note that if you use the Admin Plugin, a file with your configuration named highlight-autodetect-off.yaml will be saved in the `user/config/plugins/`-folder once the configuration is saved in the Admin.

## Usage

Just install it to disable auto-detection