# Speed Ricer

Vanilla packages for ricing.

## What is this?

This repo provides scripts and metadata to build Linux packages for some open source programs that are not available in the defacto package repositories.  This allows for easy installation of packages. 

## What distros or package managers does it support?

At this time Ubuntu but if anyone cares to provide packages for other systems I'm happy to take pull requests.  

## Where can I get these packages?

The Ubuntu PPA must be added to your system, and then you can install a package.

Add PPA:
```
sudo add-apt-repository -y ppa:kgilmer/speed-ricer
```

Install a package:
```
sudo apt install polybar
```

## Contributions and Feedback

Yes please.

## Goals

* Support people that want to create their own desktop environments.
* Enable others to use this repo to publish to their own PPA or other repositories.