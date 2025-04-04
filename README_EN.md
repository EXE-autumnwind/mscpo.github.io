# Minecraft Server Collective Promotion Organization

[Add Your Server to the Homepage](https://github.com/MSCPO/mscpo.github.io/issues/new/choose)

-------------
Languages：English;[中文](README.md)

-------------

Submitting Servers
------------------

Before submitting a server, please make sure that your server meets the following requirements:

1. Joined the MSCPO Committee and became an associate member

If your server meets the above requirements, please follow these steps to submit your server:

1. Fork this repository and clone it locally.
2. Modify the `servers/en/ServerList.yaml` file and add the following:

``` yaml
- title: example
  icon:
    src: /server_icons/example.jpg
  type: Java/Geyser/Bedrock
  version: Your server version
  desc: example desc
  link: https://example.com
```

> The `icon:` field can be modified to a single character, and it can also switch between dark and light modes.

For example:

``` yaml
  icon:
    dark: /dark-feature-icon.svg
    light: /light-feature-icon.svg
```

``` yaml
  icon:
    src: /cool-feature-icon.svg
```

``` yaml
  icon: 🛠️
```

3. (Optional) If you need to display the server icon, please add the icon to the `servers/public/server_icons/` directory.
4. Push to your repository and then submit a pull request.

## Special Thanks

### ZUY Studio

[ZUYCraft](https://mc.zuyst.top/) provided a website node for us.

[Server Collective Promotion Organization (MSCPO)](https://mscpo.zuyst.top) [https://mscpo.zuyst.top](https://mscpo.zuyst.top)

### MFT Server Alliance

[MFT Server Alliance](https://mc.mscaome.top/) provided a website node for us.

[Server Collective Promotion Organization (MSCPO)](https://mscpo.mscaome.top) [https://mscpo.mscaome.top](https://mscpo.mscaome.top)

### Info

![Alt](https://repobeats.axiom.co/api/embed/40f1d6f2bafcf731a005ddad0f4a0178ce8e6c46.svg "Repobeats analytics image")

### Contributors

Contributors who helped us add servers

[![Contributors](https://contrib.rocks/image?repo=MSCPO/mscpo.github.io)](https://github.com/MSCPO/mscpo.github.io/graphs/contributors)

> Respect to all the participants above!
