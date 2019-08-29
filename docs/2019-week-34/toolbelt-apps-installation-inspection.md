---
title: Toolbelt apps installation inspection
description: “waiting for proper translation”
date: “29/08/2019"
git: “https://github.com/vtex-apps/release-notes”
---

# Toolbelt apps installation inspection

VTEX IO Toolbelt now inspects if route conflicts can occur in your workspace as a result of installing a new app.

## How it works

The inspection is automatically applied when an app is installed in a workspace using the command `vtex install`. If there is any verified route risk, the app installation is frozen.

To ignore this inspection and install the app even if when it generates route conflicts, simply type in the `-f` parameter at the end of the command, such as `vtex install -f`.

## Main advantages

In addition to stifling route conflicts in any workspace, an automated inspection also entails greater fluidity of the development process.

## What you need to do

Make sure your **VTEX IO Toolbelt** is updated to version **2.67.0**.