---
hide:
  - toc
---
# snowk-job-elec
## :material-file-code: ``snowk-job-elec``

!!! bug "This Addon is still in development"
    Please be aware that this Addon is still in its development stage, no Addon comes out of the development stage until I'm satisfied that it is entirely where I want it to be. As per our promises, no Addon will be abandoned during development.

---
## **Information about this addon**
This is a **job addon** and adds an extra job for your players to mess around with and earn money from, players will be able to head over to an NPC location and begin a new job working for the marked NPC — upon doing so they will be able to go around the city repairing various electrical boxes and public utility.
!!! warning "Dependencies, *These are required for this addon to function*"
    :material-file-code: **qtarget** ``Price: Free`` ``Developer: Noms`` ``Type: Click Menu`` [``Download``](https://forum.cfx.re/t/qtarget-a-re-written-and-optimised-third-eye-solution/3984356)
    <br>
    :material-file-code: **ESX** ``Price: Free`` ``Type: Framework`` [``Download``](https://github.com/esx-framework)

!!! note "Supports, *These are supported and optional, addon will function without them*"
    :material-file-code: **swt_notifications** ``Price: Free`` ``Developer: Switty6`` ``Type: Click Menu`` [``Download``](https://github.com/Switty6/swt_notifications)
    <br>

---
## **Configuration Guide**
When configuring any of my addons please note that the advanced configuration will not be supported if you change it, such configurations are built for people with more technical knowledge and if you change this you are presumed to know what you're doing thus you will be given no support.

**Simple Config Information**
=== "Framework"

    ``` lua
    simpleConfig = {
      Framework = "ESX",
    }
    --[[
      Supported: ESX
      None aka "" is not supported. This configuration is required.
    --]]
    ```

=== "Menu"

    ``` lua
    simpleConfig = {
      Menu = "qtarget",
    }
    --[[
      Supported: qtarget
      None aka "" is not supported. This configuration is required.
    --]]
    ```

=== "Notify"

    ``` lua
    simpleConfig = {
      Notify = "swt",
    }
    --[[
      Supported: swt
      None aka "" is allowed, this is an optional configuration.
    --]]
    ```

---
## **Technical Information**
| Title| Information||||
||||||
| Last Update| `3rd of March, 2022.`||||
| Contributors| `Katie` `Averul`||||
| Script Type| `Job`||||
| Release| `Unreleased`||||


[Get This Addon](#){ .md-button .md-button--primary } [Get All My Addons](#){ .md-button }