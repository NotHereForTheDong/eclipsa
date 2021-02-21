# eclipsa
Checkm8 PoC tool for A8, A8X and A9 devices that allows you to boot untrusted images (macOS only, credits: checkra1n team).

*DFU --> eclipsa-nonce --> unsigned ibss/ibec --> nonce will be set to 0x1111111111111111*

*you can change nonce within eclipsa.c if needed*

Small update by NotHereForTheDong to allow for setting nonce in DFU on all supported platforms
