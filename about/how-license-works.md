---
layout: default-layout
title: Sample Page
keywords: sample, page
description: sample page
needAutoGenerateSidebar: true
---

# About t

## How license tracking works

All Dynamsoft SDKs that are compatible with [License 2.0]({{site.about}}terms.html#license-2.0) are designed to keep track of runtime usage and submit the usage data periodically.

### Dynamsoft Barcode Reader

On each device where the SDK is used, a UUID (Universally unique identifier) for that device is generated the first time the SDK runs. This UUID is cached on the device and presented in all usage reports that are sent to the License Tracking Server.

> Check out [the definition of a Device]({{site.about}}terms.html#device)
