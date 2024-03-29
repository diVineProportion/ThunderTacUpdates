### Changelog

> **2.2.2**  *2021-5-20*
> - add open cfg option for nix
> - impose 1s pause when not in battle (reduce CPU)
> - add roll filter
> - add experimental gunfire

> **2.2.1**  *2021-4-23*
> - fix update killer

> **2.2.0**  *2021-4-23*
> - set_filename() now returns pathlib object instead of string
> - implement new location detection system
> - retain original location detection system as fallback
> - fix archive naming from acmi.zip to zip.acmi
> - disabled ctrl+c block

> **2.1.15**  *2021-3-25*
> - updated url for fetch wtunits.json
> - wtunits will download every time (~350kb)

> **2.1.14**  *2021-3-25*
> - replaced waiting animation with message to start aces.exe
> - change depth for pysnooper client debug

> **2.1.13**  *2021-2-23*
> - enable mqtt statistics reporting

> **2.1.12**  *2021-2-23*
> - revert to state altitude

> **2.1.11**  *2021-2-23*
> - added internet shortcut to ftp folder (windows users)
> - use more accurate altitude reading fixed
> - fallback for planes with lacking instrumentation
> - enabled flag to bypass update check
> - enabled flag for debug with stdout

> **2.1.10**  *2021-2-21*
> - temp removal of control surface controls

> **2.1.9**  *2021-2-21*

> **2.1.8**  *2021-2-19*

> **2.1.7**  *2021-2-19*
> - attempt fix for Japanese i18n
> - temp disable all MQTT
> - switch alt from state["H, m"] to indicators["altitude_10k"]/["altitude_hour"]
> - add option for neutral or unknown/undetermined team identification

> **2.1.6**  *2021-2-17*

> **2.1.5**  *2021-2-12*
> - reworked get_user_alias for better encoding detection
> - add Japanese to get_window_title list

> **2.1.4**  *2021-2-10*
> - properly handle Japanese system local

> **2.1.3**  *2021-2-10*

> **2.1.2**  *2021-2-10*
> - sync changelog to version

> **2.1.1**  *2021-2-10*
> - revert tqdm to old method

> **2.1.0**  *2021-2-10*
> - automatic updates
> - automatic name discovery
> - automatic session discovery

> **2.0.0**  *2021-2-10*
> - major update; old versions incompatible

> **1.0.0**  *2021-2-10*
