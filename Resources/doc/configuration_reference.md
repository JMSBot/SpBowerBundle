SpBowerBundle Configuration Reference
=====================================

All available configuration options are listed below with their default values.

``` yaml
# app/config/config.yml
sp_bower:
    register_assets: true # Optional
    bin: /usr/bin/bower # Optional
    paths:
        # DemoBundle: ~
        DemoBundle:
            config_dir: Resources/config/bower # Can be relative to the bundles root directory or absolute
            asset_dir: ../../public/components # Can be relative to the config_dir directory or absolute
            json: components.json
            endpoint: https://bower.herokuapp.com
```
