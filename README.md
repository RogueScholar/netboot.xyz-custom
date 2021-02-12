# RogueScholar/netboot.xyz-custom

## Install prerequisites

To use this repository you need to install the base netboot.xyz image, a Keybase account and the Keybase client.

* [Netboot.xyz Home Page](https://netboot.xyz/)
* [Join Keybase](https://keybase.io/)
* [Install the Keybase client](https://keybase.io/download)

## Chainloading

If you just want to boot your iPXE-enabled system using one of the utilities in
the menu, you need only navigate to an iPXE shell prompt and issue this command:

```bash
chain --autofree https://raw.githubusercontent.com/RogueScholar/netboot.xyz-custom/master/custom.ipxe
```
