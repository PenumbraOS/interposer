# Ai Pin Interposer

An interposer is a device that allows you to connect to the Ai Pin over ADB + USB. This unlocks the device for additional uses such as openPin's projects.

> [!NOTE]
> Access over ADB requires the leaked Humane ADB cert. In order to access the device over ADB without finding the cert, you can use [openPin Hub](https://openpin.org) or [a custom ADB client](https://github.com/PenumbraOS/adb_remote_auth).

## Setup

[Follow the preparation instructions](preparation.md) to allow your Ai Pin to use an interposer.

We have two different endorsed mechanisms for obtaining an interposer:

## Purchase

![Etsy interposer](https://i.etsystatic.com/45058225/r/il/f825aa/6845282543/il_1588xN.6845282543_tvpl.jpg)

Community member GoinGhost is [selling ready-made interposers on Etsy](https://www.etsy.com/shop/darkmoonlabs).

## PCB (Recommended)

![Assembled interposers](https://github.com/MaxMaeder/OpenPin/raw/master/.github/assets/interposers.jpg)

[Learn more](https://github.com/MaxMaeder/OpenPin)

This option is the recommended interposer solution due to its high quality and ease of construction. It does require fabrication of a PCB and fine SMD soldering ability.

Design by [@MaxMaeder](https://github.com/MaxMaeder).

## Full DIY (Discouraged)

![](https://github.com/agg23/ai-pin-interposer/raw/master/images/Docked%20Pin.jpg)

> [!WARNING]  
> Due to assembly difficulties, this design is not recommended.

[Learn more](https://github.com/agg23/ai-pin-interposer)

This option is able to be built completely DIY (with the help of a 3D printer). It requires fine soldering ability, but less than that required by SMD components.

Design by [@agg23](https://github.com/agg23).
