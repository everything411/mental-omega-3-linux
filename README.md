# Mental Omega 3 For Linux

## What's this?

An unofficial Mental Omega 3 repack for linux.

## What's in it?

- An latest self-contained linux-x64 universal OpenGL build of [xna-cncnet-client](xna-cncnet-client) based on .NET 8.0
- Modified ini files in Resources folder to adapt the latest version of xna-cncnet-client
- Binary-patched version of Syringe.exe to use with wine
- Auxiliary scripts for linux
- ALL game resources needed for playing

## How to?

- Add `ddraw.dll` to the override dll lists of your wine prefix to use cnc-ddraw
- (optional) Edit wine-dta.sh to adjust game launch wine command line
- (optional) Edit MentalOmegaClient.sh to adjust client command line
- Run `MentalOmegaClient.sh` and enjoy!
- (optional) Change the user name in game

## Download Link

https://mega.nz/file/FqUTUYCT#p3nmA_iY2xOJIOc_kK94EPNxRXnx302KzOU0SGb8We4

## What's working
- Campaign
- Skirmish

## What's not working
- Multi Player
- Chinese language pack (lead to crash when Campaign loading)

## For MAC users

This linux-x64 build of Mental Omega 3 client cannot run on mac directly but you can compile your build of [xna-cncnet-client](xna-cncnet-client) targeted macos. The `ini`s in Resources is ok for you.
