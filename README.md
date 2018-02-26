# pkg-hunspell

RPM packaging of Hunspell for SailfishOS

To build and install:

```
export SFARCH=armv7hl; mb2 -t SailfishOS-$SFARCH -s build

export SFARCH=armv7hl; sb2 -t SailfishOS-$SFARCH -m sdk-install -R rpm -i <LOCATION OF RPM>
```
