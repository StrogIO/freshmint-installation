# Stog start-me guide

```
This is a cheatsheet for a headless start-up of StogIO project:
```

### You should have next nodes:
1. Micro Sd card 1g
2. [Shift register SN74HC595N](https://www.google.com/search?ei=0DchXICgCYLpsAfwnI6YAg&q=sn74hc595n+buy&oq=sn74hc595n+buy&gs_l=psy-ab.3..0i22i30.1840.2875..3073...0.0..0.354.772.0j3j0j1......0....1..gws-wiz.......0j0i71.4ucEJDY_b8o)
3. Raspberry
4. Card reader for microSd if don't have one
5. 8channals relay, 5v
6. Power USB adapter

## Installation

In general amazon GreenGrass tutorial: [Setting Up a Raspberry Pi](https://docs.aws.amazon.com/greengrass/latest/developerguide/module1.html) is what we building

```
Tip: remember path to folders where you work
```

1. Download [Raspbian Stretch Lite](https://www.raspberrypi.org/downloads/raspbian/);
2. Download [Fetcher](https://www.balena.io/etcher/);
3. Unzip archive and using Fetcher burn OS to sd card; reconnect sd card to start new session;
4. Using [next steps](https://www.raspberrypi.org/forums/viewtopic.php?t=191252#p1200524) set-up wifi and ssh connections;
5. Plug sd-card to raspberry;
6. Form point 9 to 13 of [amazon GreenGrass tutorial](https://docs.aws.amazon.com/greengrass/latest/developerguide/module1.html) Setting Up a Raspberry Pi;

next steps are installing Amazon GreenGrass software
