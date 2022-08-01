# Stossy11's X1 Carbon 1st Gen macOS Repository
A repository of information and kexts for running macOS Mojave on the X1 Carbon 1st Generation.

Stossy11's X1 Carbon Specs:
- Model: 3443CTO
- BIOS: G6ETC5WW (2.85 )
- CPU: Intel Core i7-3667U @ 2.0 GHz 
- GPU: Intel HD Graphics 4000 
- RAM: 8GB DDR3L SDRAM 
- Bluetooth Card: Broadcom Corp. BCM20702 Bluetooth 4.0 [ThinkPad]
- Wireless Card: Intel Corporation Centrino Advanced-N 6205 [Taylor Peak] (rev 96) 

## What Works:
Virtually everything except what's listed below.

## What hopefully works but might not:
- Wireless. I've added a a new kext to the repository to try thanks to the OpenIntelWireless team (AirportItlwm wrapped in IO80211Family).

## What Doesn't Work:
- Microphone and microphone mute button don't register for some reason.
- Trackpoint works maybe 10% of the time. I have zero idea as to why.
- Audio usually doesn't work after sleep (requires an SSDT patch + Codec Commander or a program to restart AppleHDA.)
- Upgrading to Catalina / Big Sur / Monterey For Now.
- Facetime / iMessage / etc.

## Untested:
- Facetime / iMessage / etc.
- Mini-Displayport output
- Bluetooth Hand-Off
- Airport
- Lots of other things, I'm sure. 

## Potential Setbacks (if the recent Wi-Fi kext doesn't work):
- X1C1 uses a proprietary Wi-Fi adapter, and has a BIOS that can only be flashed unofficially with a SOIC-8 clip. Adapters exist to convert traditional Wi-Fi cards to Lenovo's proprietary standard, but whether or not these are compatible with any possible BIOS mods is yet to be seen, and may be a discouraging factor.
