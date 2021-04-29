`openhab3` 
# openhab3 pihole Integration

# Requirements

1. Working [openhab3](https://www.openhab.org/) setup
1. [HTTP-Binding](https://www.openhab.org/addons/bindings/http/) installed
1. [JSON-Path-Transormation](https://www.openhab.org/addons/transformations/jsonpath/) installed


# How To

1. Add a new HTTP-Thing and configure it like shown in the image below
![thing_config.png](thing_config.png)
1. Add a `pihole.things` file to your openHab3 config
1. Add all paths you later want to display in a sitemap as a channel
    * an example can be found [here](pihole.things)
1. Add a `pihole.items` file to your openHab3 config
1. Create an item for each value you want to display or use in openHab
    * an example can be found [here](pihole.items)
1. Create a Sitemap and display the pihole values like shown in the image below
    * an example for the sitemap below can be found [here](pihole.sitemap)

![Example](sitemap_example.png)

