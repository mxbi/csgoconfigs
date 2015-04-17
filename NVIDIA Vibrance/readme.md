# Nvidia Vibrance adjuster

This program increases the vibrance of colours while CSGO is running. This makes enemies and objects easier to see as their colours stand out more
**It only works for NVIDIA graphics cards**

You can have it running permanently in the background, it works by checking every five seconds whether CSGO is in the foreground and if it is then it increases the vibrance to 100% in the NVIDIA graphics drivers.
On almost all systems, this should have no performance impact.

## Disclaimer

I did not code this software. You can see the original post here on reddit: https://www.reddit.com/r/GlobalOffensive/comments/1y9wdz/digital_vibrance_observer_program_for_nvidia/
However the account that made it has since been deleted :/

Anyway, this tool **should** not VAC ban you.  All it does is to look whether "csgo.exe" is running and whether it is running in foreground by calling FindWindowW and GetForegroundWindow.
This is standard for a lot of programs so there is no reason why this would result in a VAC ban. However, I take no responsibility in what may happen when you use this tool.