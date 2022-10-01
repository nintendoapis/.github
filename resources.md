Resources
===

This page lists some resources for using Nintendo's smart device app APIs.

https://discord.com/invite/4D82rFkXRv - [samuelthomas2774/nxapi#12](https://github.com/samuelthomas2774/nxapi/issues/12)

Documentation
---

Paw project with Nintendo Account, Coral, imink, nxapi and SplatNet 2 APIs.

https://discord.com/channels/998657768594608138/998673874805862450/1012076509906870324 - [@samuelthomas2774](https://github.com/samuelthomas2774)

Nintendo Account, Coral and SplatNet 2 API documentation. (Coral API information is mostly out of date.)

https://github.com/ZekeSnider/NintendoSwitchRESTAPI - [@ZekeSnider](https://github.com/ZekeSnider)

TypeScript definitions for Nintendo Account OIDC, imink, flapg, Coral, Moon, SplatNet 2, NookLink and SplatNet 3 APIs from nxapi. (If you are using Nintendo's APIs in a TypeScript project you should import these from nxapi instead of copying them.)

https://github.com/samuelthomas2774/nxapi/blob/main/src/api/na.ts - Nintendo Account API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/f.ts - imink/flapg/nxapi znca API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/coral-types.ts - Coral API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/moon-types.ts - Moon API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/splatnet2-types.ts - SplatNet 2 API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/nooklink-types.ts - NookLink API types  
https://github.com/samuelthomas2774/nxapi/blob/main/src/api/splatnet3-types.ts - SplatNet 3 API types

Documentation for Nintendo Account OIDC and Coral JWTs and SplatNet 2 session cookies.

https://gitlab.fancy.org.uk/samuel/nxapi/-/wikis/Nintendo-tokens - [@samuelthomas2774](https://github.com/samuelthomas2774)

API libraries
---

### nxapi

JavaScript/TypeScript library for Nintendo Switch Online, Nintendo Switch Parental Controls, SplatNet 2 and NookLink APIs, with a scriptable command line interface.

https://github.com/samuelthomas2774/nxapi - [@samuelthomas2774](https://github.com/samuelthomas2774)

### pynso

Python library for Nintendo Switch Online, SplatNet 2 and NookLink APIs.

https://github.com/Jetsurf/pynso - [@Jetsurf](https://github.com/Jetsurf) and [@xlatb](https://github.com/xlatb)

### nxapi Coral API proxy

Intermediary API server for the Nintendo Switch Online app API. Handles Nintendo Account and Coral authentication automatically.

https://github.com/samuelthomas2774/nxapi/blob/main/docs/cli.md#api-proxy-server - [@samuelthomas2774](https://github.com/samuelthomas2774)

Coral API authentication
---

Coral uses this horrible client authentication thing. These APIs are used to call a function in the app to generate some data to prove to Nintendo that you are probably Nintendo's app.

- https://github.com/samuelthomas2774/nxapi/discussions/10

### imink API

API for generating `f` tokens required to authenticate to the Coral API.

https://github.com/JoneWang/imink/wiki/imink-API-Documentation - [@JoneWang](https://github.com/JoneWang)  
https://github.com/imink-app/f-API - [@JoneWang](https://github.com/JoneWang)

### nxapi znca API, nsotokengen

API servers for generating `f` tokens required to authenticate to the Coral API, using an Android device/emulator with Frida.

https://github.com/samuelthomas2774/nxapi-znca-api - [@samuelthomas2774](https://github.com/samuelthomas2774)  
https://github.com/clovervidia/nsotokengen - [@clovervidia](https://github.com/clovervidia)

Other
---

### Nintendo app versions

Latest release information for the Nintendo Switch Online and Nintendo Switch Parental Controls apps from iTunes, Google Play and Nintendo's JP/EU websites, and SplatNet 3.

https://github.com/nintendoapis/nintendo-app-versions - [@samuelthomas2774](https://github.com/samuelthomas2774)

Release notifications via Discord: https://discord.com/channels/998657768594608138/998659415462916166

### SplatNet 3 app resources

Archived original and formatted JS/CSS and other assets used in SplatNet 3.

Request access via Discord.
