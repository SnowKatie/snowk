---
hide:
  - toc
---
<figure markdown>
  ![Banner Logo](../images/jobs.png)
</figure>
# snowk-jobs-elec
## :material-file-code: ``snowk-jobs-elec``

- [x] Currently maintained and supported!

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
    :material-file-code: **mythic_progbar** ``Price: Free`` ``Developer: HalCroves`` ``Type: Progress Bar`` [``Download``](https://github.com/HalCroves/mythic_progbar)

---
## **Configuration Guide**
When configuring any of my addons please note that the advanced configuration will not be supported if you change it, such configurations are built for people with more technical knowledge and if you change this you are presumed to know what you're doing thus you will be given no support.

**Simple Config: ``Required Dependencys``**
=== "framework"

    ``` lua
    simpleConfig.framework = "ESX"
    --[[
      Supported: ESX
      None aka "" is not supported. This configuration is required.
    --]]
    ```

=== "menu"

    ``` lua
    simpleConfig.menu = "qtarget"
    --[[
      Supported: qtarget
      None aka "" is not supported. This configuration is required.
    --]]
    ```

**Simple Config: ``Optional Addons``**
=== "notify"

    ``` lua
    simpleConfig.notify = "swt"
    --[[
      Supported: swt
      None aka "" is allowed, this is an optional configuration.
    --]]
    ```

=== "cdGarage"

    ``` lua
    simpleConfig.cdGarage = true
    --[[
      This should be set to true if you are using the addon cdGarage.
    --]]
    ```
**Simple Config: ``Other Configs``**

=== "npcLocation"

    ``` lua
    simpleConfig.npcLocation.coords = vector3(738.6884, 135.3527, 79.7287)
    simpleConfig.npcLocation.heading = 221.3609
    --[[
      These two values are for where your NPC spawns, the first is the location with an X, Y and Z coord. The second
      is a heading which is the direction he'll be facing.
    --]]
    ```

=== "vehicleLocation"

    ``` lua
    simpleConfig.vehicleLocation.coords = vector3(738.6884, 135.3527, 79.7287)
    simpleConfig.vehicleLocation.heading = 221.3609
    --[[
      These two values are for where your Vehicle spawns, the first is the location with an X, Y and Z coord. The second
      is a heading which is the direction it'll be facing.
    --]]
    ```

=== "payPerRepair"

    ``` lua
    simpleConfig.payPerRepair = 200
    --[[
      This is the payment per repair done, for example if a player does 10 jobs they'll get 10 * 200 = 2000
    --]]
    ```

=== "repairTime"

    ``` lua
    simpleConfig.repairTime = 10
    --[[
      The time (in seconds) that a repair takes before completion.
    --]]
    ```

=== "repairJobsMin & repairJobsMax"

    ``` lua
    simpleConfig.repairJobsMax = 14
    simpleConfig.repairJobsMin = 5 
    --[[
      These control the maximum and minimum jobs you will have per shift. It'll be randomized between these two values, Max being of course, the Max.
      And min, you guessed it; The min.
    --]]
    ```

---
## **Technical Information**
| Title| Information||||
||||||
| Last Update| `4th of March, 2022.`||||
| Contributors| `Katie` `Averul`||||
| Script Type| `Job`||||
| Release| `Pre-release`||||


[Get This Addon](https://snowk.tebex.io/category/2054875){ .md-button .md-button--primary }