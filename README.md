# APEX WebView Region Plugin

Oracle APEX Region Plugin for displays pages from the same application or other sites

# Features

- Show content from another page, application or site.

# Install

- Import plugin file **region_type_plugin_com_eportela_webview.sql** into the Shared Components > Plugins.

# Usage

- Put into your page the WebView plugin region, go to attributes and configure it:

Item | Description 
--- | --- 
**Source Type** | Select the source type for the URL of the component. Available options include: Item, PL/SQL Expression, PL/SQL Function, SQL Query and Static Text
**Item** | The value of the selected Item is the URL of the component.
**PL/SQL Expression** | The return value of the PL/SQL expression is the URL of the component.
**PL/SQL Function** | The return value of the PL/SQL Function is the URL of the component.
**SQL Query** | The SQL query returns one row with one column, that is the URL of the component.
**Static Text** | The entered text is the URL of the component.
**Styles** | Specify the styles of the component.
**CSS Classes** | Specify the CSS Classes of the component.

# Demo

Demo is avalaible [here](https://apex.oracle.com/pls/apex/f?p=1448:3::::::)

