---
layout: page
title: MacOS
has_children: false
permalink: /mac/macos
---

# MacOS

## Random MacOS Tips and Tricks

### List All Installed Software

#### Homebrew

List all software/apps/packages installed via [Homebrew](https://brew.sh/):

```
brew leaves
```

#### System Report

Get a list of all software/apps installed on your mac: `System Settings` --> `General` --> `System Report` --> `Software` --> `Applications`

#### `system_profiler`

From your terminal run:

```
system_profiler SPApplicationsDataType
```

May be best to pipe to a pager like `less` or output to a file for easier reading.