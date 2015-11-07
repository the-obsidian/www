---
layout: page
title: Plugins
permalink: /plugins/
---

We keep everything simple and as close to vanilla SMP as possible.  The server has a few plugins installed to aid with general administration:

## Prism

Logging and rollback plugin - we haven't had any reason to use this thus far, however should any griefing take place, Prism will help with the identification and rollback.  WorldEdit and WorldGuard are also installed to assist with rollback.

## CommandHelper

This plugin is used to implement custom command aliases as well as all custom server behavior.  We have replaced many other plugins with simple CommandHelper scripts.

## WorldBorder

Our world border is set with a radius of 6000 around (0,0).  WorldBorder ensures the world stays that size and also pre-generates the terrain.

## Dynmap

Generates our server map.

## PermissionsEx

Used to customize the permissions and control the premium group.  Currently evaluating moving the group management to custom CommandHelper scripts to remove another dependency.

## Slack

For logging, a copy of the console is sent to a private Slack channel.

## Buycraft

Integrates our donation store with the server.
