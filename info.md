{% if prerelease %}
# ATTENTION: This is a pre-version of HA Floorplan!
{% endif %}

<img style="max-width: 200px;width: 100%;text-align:center;display:block;margin:0 auto;" src="https://github.com/ExperienceLovelace/ha-floorplan/blob/master/docs/assets/images/logo-200x200.png?raw=true" alt="HA Floorplan Logo">

# HA Floorplan

**Floorplan for Home Assistant - your imagination (almost) defines the limits**



### 📚 Read the [documentation](https://experiencelovelace.github.io/ha-floorplan/) 📚

You'll find information about:
- Installation
- Examples
- Options
- _And more..._


### Features

- Make Floorplan(s) with SVG-files
- Trigger states, visualize states and more
- Call services and more, for even more options
- Use as Lovelace-card, or as a panel
- _It's hard to mention everything in a list like this, so **give it a try**_ 🥳

<img style="border: 3px solid #26c7fb;border-radius: 10px;max-width: 350px;width: 100%;box-sizing: border-box;" src="https://github.com/ExperienceLovelace/ha-floorplan/blob/master/docs/assets/images/home/floorplan-background_with_floorplanner.png?raw=true" alt="SVG Preview">


#### Ressource template for Home Assistant

```yaml
resources:
  - url: /hacsfiles/ha-floorplan/floorplan.js
    type: module
```
