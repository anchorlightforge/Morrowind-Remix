# Morrowind-Remix
A custom configuration for RTX Remix designed to improve compatibility with TES III: Morrowind.

Note that this repo is only provided for initial testing and is not ready for general use.  While compatibility has significantly improved since Remix's open-source debut, there are a number of issues that still need to be addressed through this mod before it is ready for non-testing purposes.

## Setup

1. Download [RTX Remix 0.2.0(https://github.com/NVIDIAGameWorks/rtx-remix/releases/tag/remix-0.2.0) from the official Nvidia GameWorks repository and include its contents in the Morrowind folder.
2. Download the latest Bridge-Remix build from the Nvidia GameWorks repository and include its contents in the Morrowind folder.  Accept any overwrites. Last tested commit: [41bcd9d](https://github.com/NVIDIAGameWorks/bridge-remix/actions/runs/5417656570)
3. Download the latest PathologicClassicRTX fork of DXVK-Remix -- this is a custom DXVK-Remix fork with additional ImGui options to make configuration easier.  Accept any overwrites. Last tested commit: [db60ae7](https://github.com/anchorlightforge/dxvk-remix/actions/runs/5428912856)
4. Use the configuration provided to make sure that Morrowind is configured correctly and will start on launch.

## Disclaimer:
All of the code provided respects the original terms of service provided with the original RTX Remix project.  While DXVK-Remix and Bridge-Remix are subject to the MIT and ZLib licenses, a number of its dependencies are not. For the full terms of service, see [Remix Third Party Licenses](https://github.com/NVIDIAGameWorks/dxvk-remix/blob/93090f265153fb72f29b29af0b628d257d1ebf70/ThirdPartyLicenses.txt).
Morrowind-Remix is in no way, shape or form endorsed or affiliated with Bethesda Softworks, Bethesda Game Studio, Zenimax Media, or Microsoft.  No assets from the original game will be provided in this repo.
