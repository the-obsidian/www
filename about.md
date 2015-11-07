---
layout: page
title: About
permalink: /about/
---

Need to get in touch?  Shoot an email to [staff@obsidian.gg](mailto:staff@obsidian.gg) and we will get back with you ASAP.

## Staff Roles

You can always see who's who in game with `/players`.  Our staff is split into two roles:

### Operator

Operators primarily handle the "operations" of the server (planning, maintaining server software, etc.).  Operators also assist the guardians with maintaining the server community.

### Guardian

Guardians are responsible for making sure players feel welcome and have a fun experience on the server.  Guardians may act as arbitrators for any disputes between players.  

Guardians have access to the server logs and can view any changes made to the server or any messages sent publicly or privately in chat.  Guardians can kick players if necessary, or permanently ban players in extreme cases.

We carefully select our staff - we are first and foremost concerned with building a wonderful community and do not allow our staff to abuse their (limited) power.  If you have any questions or feedback, feel free to [get in touch](mailto:staff@obsidian.gg).

## Plugins

We keep everything simple and as close to vanilla SMP as possible.  The server has a few plugins installed to aid with general administration:

### Prism

Logging and rollback plugin - we haven't had any reason to use this thus far, however should any griefing take place, Prism will help with the identification and rollback.  WorldEdit and WorldGuard are also installed to assist with rollback.

### CommandHelper

This plugin is used to implement custom command aliases as well as all custom server behavior.  We have replaced many other plugins with simple CommandHelper scripts.

### WorldBorder

Our world border is set with a radius of 6000 around (0,0).  WorldBorder ensures the world stays that size and also pre-generates the terrain.

### Dynmap

Generates our server map.

### PermissionsEx

Used to customize the permissions and control the premium group.  Currently evaluating moving the group management to custom CommandHelper scripts to remove another dependency.

### Slack

For logging, a copy of the console is sent to a private Slack channel.

### Buycraft

Integrates our donation store with the server.
