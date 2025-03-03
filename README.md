# Various *OpenWRT* packages of *Graphite*-related projects

> [!IMPORTANT]
> The only supported *OpenWRT* version is **24.04**.

## Packages

* [go-graphite/go-carbon](https://github.com/go-graphite/go-carbon)
* [go-graphite/carbonapi](https://github.com/go-graphite/carbonapi)
* [grobian/carbon-c-relay](https://github.com/grobian/carbon-c-relay)

  Three variants:

  * `carbon-c-relay-full`
  * `carbon-c-relay-nossl`
  * **`carbon-c-relay-tiny`**

## Installation

### Download and run [installation script](https://github.com/RoEdAl/graphite-feed/blob/main/openwrt/graphite-feed.sh)

```sh
wget -qO - https://roedal.github.io/graphite-feed/graphite-feed.sh | sh
```

### Update package list

```sh
opkg update
```

### Install required package(s)

```sh
opkg install go-carbon carbonapi carbon-c-relay-tiny
```
