# NX-NONET

SaltyNX plugin that fake no available internet connection to avoid NAG on some games without without enabling AirPlane mode.

You need masagrator SaltyNX fork installed.
https://github.com/masagrator/SaltyNX/releases

Put NX-NONET.elf to `/SaltySD/plugins`

This plugin just hook `nn::nifm::IsNetworkAvailable()` and always return `0` to tell games no network is available.

# Thanks to:

- masagrator for the forked SaltyNX and NX-FPS where this plugin is based on
