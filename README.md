# pwnagotchi-beacon-plugins
Custom plugin repository

Edit your `/etc/pwnagotchi/config.toml` to look like this

```TOML
main.custom_plugin_repos = [
    "https://github.com/arturandre/pwnagotchi-beacon-plugins/archive/master.zip",
    ]
```
Then run this command: `sudo pwnagotchi plugins update`
