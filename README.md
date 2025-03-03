# Various *OpenWRT* packages of *Graphite*-related projects

Supported OpenWRT version: **24.04**.

## Packages

* [go-graphite/go-carbon](https://github.com/go-graphite/go-carbon)
* [go-craphite/carbonapi](https://github.com/go-graphite/carbonapi)
* [grobian/carbon-c-relay](https://github.com/grobian/carbon-c-relay)

## Installation

### Download and run installation script

```sh
wget -qO - https://roedal.github.io/graphite-feed/graphite-feed.sh | sh
```

### Update package list

```sh
opkg update
```

### Install required package(s)

```sh
opkg install go-carbon carbonapi
```
