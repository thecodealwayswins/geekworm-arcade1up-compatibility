# Arcade1UP/Geekworm LVDS to HDMI/VGA Compatibility List

A list of verified devices/combinations of the Geekworm LVDS to HDMI and Arcade1Up PCBs for upgrading monitors, as well as some useful information & resources. This will help you pick devices that work with upgrading your arcade cabinet monitor or TV.

- [Compatible Device Combos](#compatible-device-combos)
- [Submitting Devices](#submitting-devices)
- [Correcting Inaccuracies](#correcting-inaccuracy)
- [Resources](#resources)
- [Acknowledgements](#acknowledgements)
- [Note](#note)
- [Contributors](#contributors)


## Compatible Device Combos

| Brand         | Model #              | Size* | Board | PCB Group   | Adapter        | See It | Video  |
| ------------- | -------------------- | ----- | ----- | ----------- | ----------     | ------ | ------
| Asus          | VG278                | 27    | V1.5  | VS/BB       |                | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_asus_vg278.gif)     | [link](https://www.youtube.com/watch?v=FllN1r_UOLg&t=1242s)
| Dell          | P1914Sf              | 14    | V1.5  | VS/BB       | HDMI to VGA    | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_dell_p1914sf.gif) |[link](https://youtu.be/I8MovSVPnP4?t=19)       |
| GeChic        | 1101P                | 11.6  | V1.5  | VS/BB       |                | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_gechic_1101p.gif)       |[link](https://www.youtube.com/watch?v=qbcmKnASI-Q&t=1s)      |
| Samsung       | S22F350FH            | 22    | V1.5  | VS/BB       |                | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_samsung_s22f350.gif)      |[link](https://youtu.be/I8MovSVPnP4?t=12)        |
| TCL           | 43S405               | 43    | V1.5  | VS/BB       |                | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_tcl_43s405.gif)       |[link](https://youtu.be/I8MovSVPnP4?t=15)         |
| WiiMaxit      | M1020                | 10    | V1.5  | VS/BB       |                | [🖼](./compat-data/v1.5/vs-bb/vsbb_v15_wiimaxit_m1020.gif)      |[link](https://youtu.be/ZbNe2T2hxqU?t=393)

<span style="font-size:10pt;font-style:italic">* size is provided in inches</span>

<span style="font-size:10pt;font-style:italic">**VS/BB**: X-Men vs SF, Marvel vs Capcom, Big Blue</span>


## Submitting Devices
Your help is greatly appreciated, and we all benefit as people looking for devices can save time and money looking for monitors to upgrade our cab. This is especially as this is a bootstrapped project, with no official support at this time from either Arcade1UP or Geekworm. To submit a device, please create an issue, including:

- the specific Geekworm model (e.g. V1.5, V20, etc)
- the arcade PCB you are testing with.
- (preferable) the pin configurations which worked.
- a link to a video demonstrating things working with this specific setup. Preferably as a GIF to streamline things, but not necessary.
- (optional) any known issues to be aware of -- not to include pin configs that don't work, as this is primarily an inclusionary vs exclusionary list.
- if it is your first time contributing, please provide a name and link to add to the contributors section below.

Alternatively, if this proves to be difficult due to familiarity with GitHub, please feel free to email me (scroll down to end of this document for more info).

⚠ *Please do not submit info about devices that do not work. This is because it may dissuade others from trying, and there is always a possibility that your board may have manufacturing defects* ⚠

Over time, how to do this will be documented more clearly. But again any help is appreciated here.

## Correcting Inaccuracies
If you have a monitor listed that turns out has some pin config wrong or the board was falsely listed, please let us know by creating an issue.

## Resources

### Official Website: https://geekworm.com/products/lvds-to-hdmi-adapter-board-converter-with-lvds-cable

### Geekworm Discord: https://discord.gg/HTur7gv9

### Tutorial/Troubleshooting Video incl/ Audio: https://youtu.be/I8MovSVPnP4


## Acknowledgements

Thanks to [TheRealSmilebit](https://www.youtube.com/channel/UCCEIy55LJfntICD4uJti9mw) for creating the Geekworm Discord, which was created well before this list here. There are also many other people including [Kong](https://www.youtube.com/c/KongsRUs) and [RoTeNdO](https://www.youtube.com/channel/UCdHcbiIRYGNVBkI0COdzLww) who did things very early on with that there, testing as they went and trying things to provide some idea that this can be used to connect to an external monitor via LVDS (not to exclude anyone if that has been done). And obviously, Geekworm and Arcade1UP for inventing the things that this is oriented around.

## Note

This is an early work in progress, and this document will evolve over time. With that, if you notice anything that is not ideal, not intuitive, or think that something being done is just a bad idea, please feel free to create an issue with a suggestion for discussion, or email the maintainer @ thecodealwayswins@gmail.com.

This is not a how-to so please do not post issues related to getting started in this repository.

For those types of issues, there is the resources above, or the [Geekworm Discord](https://discord.gg/HTur7gv9).

Also keep in mind that this is not an official/paid project; please expect a reasonable amount of time to get a reply on things.

## Contributors

- [MadDad's Gaming](https://www.youtube.com/channel/UCXE89cKW0VKh0Sv5MgC6IrQ)
- [The Code Always Wins](https://www.youtube.com/c/TheCodeAlwaysWins)

Have something to add? Submit your working model/PCB/board version and a vid link and help everyone else out at the same time @ thecodealwayswins@gmail.com.
Please make the subject obvious e.g. "Geekworm V1.5 LVDS to HDMI Entry"