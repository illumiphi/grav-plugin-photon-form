<a href="https://photon-platform.net/">
    <img src="https://photon-platform.net/user/images/photon-logo-banner.png" alt="photon" title="photon" align="right" height="120" />
</a>


# photon ✴ Form

## 0.1.0

---


> structure, style and logic for Form componenents

- [configuration](#configuration)
- [templates](#templates)
- [scaffolds](#scaffolds)
- [scss](#scss)
- [assets](#assets)
- [languages](#languages)

# configuration
blueprints.yaml

fields:
- enabled
- built_in_css
- built_in_js

Before configuring this plugin, you should copy the `user/plugins/photon-form/photon-form.yaml` to `user/config/plugins/photon-form.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```
enabled: true
built_in_css: true
built_in_js: true

description: Custom Text added by the **photon-form** plugin (disable plugin to remove)
```

Note that if you use the admin plugin, a file with your configuration, and named photon-form.yaml will be saved in the `user/config/plugins/` folder once the configuration is saved in the admin.


# blueprints

```sh
blueprints
└── form.yaml
```

### Form
form.yaml
extends: article
fields:
- features
  - header.form.description

# templates

```sh
templates
```

# assets

```sh
assets
├── form.css
└── form.js
```


## Installation

- all photon plugins are installed as git submodules. More on that later.



## Configuration


## Usage

Select template type when creating a new page

## Credits


## To Do

- [ ] Future plans, if any


copyright &copy; 2020
