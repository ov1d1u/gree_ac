# Gree AC Custom Component for Home Assistant
Disclaimer: because I'm lazy, this README.md was mostly generated with ChatGPT.

This integration is basically the official Gree integration modified to disable the audible feedback beeps from the air conditioner unit, thanks to a patched `greeclimate` library from [@namezys](https://github.com/namezys).

## Features

- Control your Gree AC units directly from Home Assistant.
- Enjoy a quieter experience with the beeps disabled.
- Simple installation process with HACS.

## Differences from Official Integration

The functionality of this custom integration is essentially the same as the official Gree integration provided by Home Assistant. However, it includes a patched version of the `greeclimate` library, which disables the beeps from the unit, providing a more serene environment.

## Installation Instructions

You can easily install the Gree AC Custom Component using the Home Assistant Community Store (HACS):

### Prerequisites

Before you start, ensure you have the following prerequisites:

- Home Assistant installed and running.
- HACS (Home Assistant Community Store) installed.

### Installation Steps

1. **Open HACS in Home Assistant:**
   - Navigate to the HACS section in your Home Assistant dashboard.

2. **Add the Custom Repository:**
   - Click on the "Integrations" tab.
   - Click on the three-dot menu in the upper right corner and select "Custom Repositories."
   - In the "Repository" field, enter the URL: `https://github.com/ov1d1u/gree_ac`.
   - In the "Category" dropdown, select "Integration."
   - Click the "Add" button.

3. **Install the Integration:**
   - Search for "Gree AC" in the HACS integrations search bar.
   - Click on "Gree AC" from the search results.
   - Click the "Install" button.

4. **Restart Home Assistant:**
   - After installation, restart Home Assistant to load the new custom component.

5. **Configure the Integration:**
   - Once Home Assistant has restarted, navigate to "Configuration" > "Devices & Services."
   - Click "Add Integration" and search for "Gree AC."
   - Follow the configuration instructions to set up your Gree AC units.

## Acknowledgements

- This custom component incorporates the `greeclimate` library patched by [@namezys](https://github.com/namezys) to disable the beeps from the AC unit.
- Original Gree integration for Home Assistant.

## Support

For any issues or feature requests, please visit the [GitHub Issues page](https://github.com/ov1d1u/gree_ac/issues) for this repository.